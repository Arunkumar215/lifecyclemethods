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
Developed by: Magesh C M
Registeration Number : 212223220053
*/
 

package com.example.lifecyclemethod;

import android.os.Bundle;
import android.widget.Toast;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);

        setContentView(R.layout.activity_main);
        Toast.makeText(getApplicationContext(),"onCreate Called", Toast.LENGTH_LONG).show();

    }

    @Override
    protected void onStart(){
        super.onStart();
        Toast.makeText(getApplicationContext(),"onStart Called", Toast.LENGTH_LONG).show();
    }

    protected void onRestart(){
        super.onRestart();
        Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_SHORT).show();
    }
    protected void onPause(){
        super.onPause();
        Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_SHORT).show();
    }
    protected void onResume(){
        super.onResume();
        Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_SHORT).show();
    }
    protected void onStop(){
        super.onStop();
        Toast.makeText(getApplicationContext(),"onStop Called",Toast.LENGTH_LONG).show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_SHORT).show();
    }



}
```

## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/497a62fa-e3b7-4441-a5cb-50fb9e3fa660" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e6c901c2-daee-4d79-be7f-efdb35aedbca" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/855a6848-090d-40ad-8a65-2d548e329b93" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fab0c95b-db4c-4918-bbe9-6ec34109f0de" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/573dd8c5-45fc-45c1-a319-4bf0cf9cb5e2" />

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
