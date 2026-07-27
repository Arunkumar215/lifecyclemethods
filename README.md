# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


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

Program to print the text “Hello World”.
Developed by:Kavi M S
Registeration Number :212223220044
package com.example.lifecyclemethods;

import android.os.Bundle;
import android.widget.Toast;

import androidx.activity.EdgeToEdge;
import androidx.appcompat.app.AppCompatActivity;
import androidx.core.graphics.Insets;
import androidx.core.view.ViewCompat;
import androidx.core.view.WindowInsetsCompat;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate called", Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(), "onStart called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"onRestart called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"onPause called",Toast.LENGTH_LONG);
        toast.show();

    }
    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"onStop called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"onResume called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast= Toast.makeText(getApplicationContext(),"onDestroy called",Toast.LENGTH_LONG);
        toast.show();
    }
}

```

## OUTPUT
<img width="1917" height="962" alt="Screenshot 2026-07-21 092754" src="https://github.com/user-attachments/assets/31942693-cbf3-4f7e-9899-be7e9624e896" />
<img width="1917" height="1015" alt="Screenshot 2026-07-21 092803" src="https://github.com/user-attachments/assets/19f5248e-8d80-4a39-a7ee-5c1533b983de" />
<img width="1916" height="955" alt="Screenshot 2026-07-23 114806" src="https://github.com/user-attachments/assets/5150744b-fba8-424a-b0b8-c02015b854e8" />
<img width="1911" height="968" alt="Screenshot 2026-07-23 114843" src="https://github.com/user-attachments/assets/d052c38a-3b0f-4a92-b82d-0b253bbd2a8c" />




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
