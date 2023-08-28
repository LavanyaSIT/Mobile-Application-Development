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
Program to print the text “Hello World”.

# Activity_main.xml:
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
```
```
</androidx.constraintlayout.widget.ConstraintLayout>
```
# MainActivity.java:

```
package com.example.myapplication;
```
import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle; import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

```
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
Developed by: ESWARI S Registeration Number :212221220012

## OUTPUT
![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/e0a06bce-fd11-4a73-86e8-699b06859536)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/80219e85-4965-4cf3-ac66-cd8182eed5da)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/d98a0503-20af-45f7-afd8-b92c11770e18)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/f642bbf1-369e-4c9d-a930-d061acf11531)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/5cdd0012-6d0c-43da-b9f9-8c9ebe67a55e)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/83f962b0-d66a-4452-ba80-43b2a7df9c92)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/6d0d8e47-c382-447f-b6ac-34cb0b72698a)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/799b72e8-3b5c-4be3-8e41-097258c1ec10)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/02cfe21f-6407-4ad4-909c-2e497f320120)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/c65dc6f8-9e81-4ed3-8b21-12c3fa88868b)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/d72ea4dc-3149-459c-82d0-3eaf944d892c)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/5f5d70e7-e7ca-4246-bfa8-686c219d85a2)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/f682781d-77f2-48fd-b2ad-82f8c81f7f42)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/e6e72037-e6e2-4120-9b09-0bcfe961d264)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/bf1b6e3d-3d26-4acd-869c-726d17f364c5)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/eccbfa02-c1b0-4449-8657-15755eace798)

![image](https://github.com/ieswaris/Mobile-Application-Development/assets/127847210/a3a257a8-88aa-4fcc-b94d-60fbf2087276)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
