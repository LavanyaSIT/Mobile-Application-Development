# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by:LAVANYA S
Registeration Number :212221220030
*/
```
## Activity_main.xml:

<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">
```
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textSize="40dp"
    android:text="Hello World!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```
## MainActivity.java:
```
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle; import android.widget.Toast;

public class MainActivity extends AppCompatActivity {
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStart() {
    super.onStart();
    Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
    toast.show();
}
@Override
protected void onRestart() {
    super.onRestart();
    Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onPause() {
    super.onPause();
    Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
    toast.show();![image](https://github.com/Roselineb/Mobile-Application-Development/assets/128909895/fcd214fc-b2e8-429d-83db-86b8f6d38913)
    
}
protected void onResume() {
    super.onResume();
    Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStop() {
    super.onStop();
    Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onDestroy() {
    super.onDestroy();
    Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
    toast.show();
}
```
## OUTPUT
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/99ea67e7-3acd-4477-af00-5c0ee340122f)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/02d2acc0-c925-4c5c-9959-73838e9f30ba)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/78dfa3f6-44c6-4249-b529-9adaa2dac6ad)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/f5643fd2-c3cc-4029-a85a-fbbf4d755fbc)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/68ed61b4-9a00-4919-99f6-089a9c18957e)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/2c623a7b-4860-49c3-8207-140823cb6c3c)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/38dc5a90-0f0f-40cb-9f78-acc2a54015b1)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/b61eed0f-170d-4f5d-afec-910549406eb0)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/e31c434c-3f17-4f40-be0a-dc78984095fe)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/7f07b8db-a178-41b8-86e9-a0c33e889dc2)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/bf2c283f-9d5c-431b-b03d-667709099428)
![image](https://github.com/suryacse05/Mobile-Application-Development/assets/130207418/5a258c6c-04de-40fc-9390-2b55896c8d92)

















## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
