# Ex.No:10 To create a option menu to display menu items.


## AIM:

To create a option menu to display menu items using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as optionmenu and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout using UI components in activity_main.xml.

Step 6: Display the calculator operation in MainActivity file.

Step 7: Save and run the application.


## PROGRAM:
```
/*
Program to print the text “optionmenu”.
Developed by:Eswari S
Registeration Number :212221220012
*/
```

## Activity_main.xml:
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
```

              xmlns:tools="http://schemas.android.com/tools"
          
android:layout_width="match_parent"
          
android:layout_height="match_parent"
          
android:orientation="vertical"
          
android:padding="16dp"
          
tools:context=".MainActivity">

<TextView
    android:id="@+id/messageTextView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:text="Select an option from the menu"
    android:textSize="25dp" />
```

## MainActivity.java:

package com.example.optionmenu;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

import android.view.Menu;

import android.view.MenuItem;

import android.widget.TextView;

import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

```

private TextView messageTextView;

@Override
protected void onCreate(Bundle savedInstanceState) {

  super.onCreate(savedInstanceState);
  setContentView(R.layout.activity_main);

  messageTextView = findViewById(R.id.messageTextView);
}

@Override
public boolean onCreateOptionsMenu(Menu menu) {

  getMenuInflater().inflate(R.menu.options_menu, menu);
  return true;
}

@Override
public boolean onOptionsItemSelected(MenuItem item) {
  int itemId = item.getItemId();

  switch (itemId) {
      case R.id.menu_item_1:
          messageTextView.setText("Option 1 selected");
          return true;
      case R.id.menu_item_2:
          messageTextView.setText("Option 2 selected");
          return true;
      case R.id.menu_item_3:
          messageTextView.setText("Option 3 selected");
          return true;
      default:
          return super.onOptionsItemSelected(item);
  }
}
```

## Option_View.xml:
```
<item
  android:id="@+id/menu_item_1"
  android:title="Option 1"
  android:textSize="25dp"/>
<item
  android:id="@+id/menu_item_2"
  android:title="Option 2"
  android:textSize="25dp"/>
<item
  android:id="@+id/menu_item_3"
  android:title="Option 3"
  android:textSize="25dp"/>
```

## OUTPUT

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/0b39abaf-de76-42a2-93ce-2a2c0a77dc63)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/e52a65ec-39c3-4246-b317-a92750ae6c90)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/949f89e9-7339-4dcb-a08e-f9f7b89119e3)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/61600ecb-1e3c-4ab3-915f-3ab539928106)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/42e43b59-98fa-444f-8550-a66cdfda6bff)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/65ab49d5-3baf-47ed-8ac9-11f81a45c2b8)



## RESULT
Thus a Simple Android Application to create a option menu to display menu items using Android Studio is developed and executed successfully.


