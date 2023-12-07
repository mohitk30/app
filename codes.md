### ---------------lab 1 (display hello world in the screen)-------------
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/helloWorldTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World"
        android:textSize="24sp"
        android:textColor="#FF0000"
        android:layout_centerInParent="true"
        android:background="#FFFFFF" />

</RelativeLayout>
```

```
package your.package.name; // Replace with your actual package name

import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}
```

### ---------------lab 2 (design visting card)-------------
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 android:background="#FFFFFF"
 tools:context=".MainActivity">
 <TextView
 android:id="@+id/textView4"
 android:layout_width="371dp"
 android:layout_height="wrap_content"
 android:layout_alignParentStart="true"
 android:layout_alignParentLeft="true"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginStart="28dp"
 android:layout_marginLeft="28dp"
 android:layout_marginEnd="12dp"
 android:layout_marginRight="12dp"
 android:layout_marginBottom="219dp"
 android:text="Address:ASKB Campus, Anandnagar, | Bangalore - 560 024"
 android:textAlignment="center"
 android:textSize="24sp" />

<TextView
 android:id="@+id/textView5"
 android:layout_width="250dp"
 android:layout_height="wrap_content"
 android:layout_alignParentStart="true"
 android:layout_alignParentLeft="true"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginStart="87dp"
 android:layout_marginLeft="87dp"
 android:layout_marginEnd="73dp"
 android:layout_marginRight="73dp"
android:layout_marginBottom="157dp"
 android:text="Ph No: 9108380566"
 android:textAlignment="center"
 android:textSize="24sp" />
 <TextView
 android:id="@+id/textView6"
 android:layout_width="367dp"
 android:layout_height="wrap_content"
 android:layout_alignParentStart="true"
 android:layout_alignParentLeft="true"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginStart="25dp"
 android:layout_marginLeft="25dp"
 android:layout_marginEnd="19dp"
 android:layout_marginRight="19dp"
 android:layout_marginBottom="64dp"
 android:text="Email Id: uzma.sulthana@atria.edu"
 android:textAlignment="center"
 android:textSize="24sp" />

<TextView
 android:id="@+id/textView3"
 android:layout_width="367dp"
 android:layout_height="66dp"
 android:layout_alignParentStart="true"
 android:layout_alignParentLeft="true"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginStart="32dp"
 android:layout_marginLeft="32dp"
 android:layout_marginEnd="12dp"
 android:layout_marginRight="12dp"
 android:layout_marginBottom="287dp"
 android:text="Assistant Professor-ISE"
 android:textAlignment="center"
 android:textSize="24sp" />

 <ImageView
 android:id="@+id/imageView3"
 android:layout_width="155dp"
 android:layout_height="98dp"
 android:layout_alignParentEnd="true"
android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="12dp"
 android:layout_marginRight="12dp"
 android:layout_marginBottom="495dp"
 app:srcCompat="@drawable/aitlogo" />

 <View
 android:id="@+id/view"
 android:layout_width="wrap_content"
 android:layout_height="4dp"
 android:layout_alignParentBottom="true"
 android:layout_marginBottom="487dp"
 android:background="#4444" />

 <TextView
 android:id="@+id/textView2"
 android:layout_width="176dp"
 android:layout_height="wrap_content"
 android:layout_alignParentStart="true"
 android:layout_alignParentLeft="true"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginStart="95dp"
 android:layout_marginLeft="95dp"
 android:layout_marginEnd="140dp"
 android:layout_marginRight="140dp"
 android:layout_marginBottom="401dp"
 android:text="Uzma Sulthana"
 android:textAlignment="center"
 android:textSize="24sp"
 android:textStyle="bold" />

 <TextView
 android:id="@+id/textView7"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="99dp"
 android:layout_marginRight="99dp"
 android:layout_marginBottom="495dp"
 android:layout_toStartOf="@+id/imageView3"
 android:layout_toLeftOf="@+id/imageView3"
 android:text="AIT"
 android:textColor="#E91E63"
 android:textSize="36sp"
 android:textStyle="bold" />
</RelativeLayout>
```

```
package com.example.visitingcardapplication;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
public class MainActivity extends AppCompatActivity {
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 }
}
```

### ---------------lab 3 (design calculator)-------------

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".MainActivity">
 <TextView
 android:layout_width="209dp"
 android:layout_height="60dp"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
android:layout_marginEnd="108dp"
 android:layout_marginRight="108dp"
 android:layout_marginBottom="530dp"
 android:text="Simple Calci"
 android:textSize="36sp"
 app:layout_constraintBottom_toBottomOf="parent"
 app:layout_constraintLeft_toLeftOf="parent"
 app:layout_constraintRight_toRightOf="parent"
 app:layout_constraintTop_toTopOf="parent" />
 <EditText
 android:id="@+id/editText2"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="115dp"
 android:layout_marginRight="115dp"
 android:layout_marginBottom="364dp"
 android:ems="10"
 android:hint="Enter the Number 2"
 android:inputType="textPersonName"
 android:text=""
 android:textColorHighlight="#FFFFFF" />
 <EditText
 android:id="@+id/editText1"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="110dp"
 android:layout_marginRight="110dp"
 android:layout_marginBottom="439dp"
 android:ems="10"
 android:hint="Enter the Number 1"
 android:inputType="textPersonName"
 android:text=""
 android:textColorHighlight="#FFFFFF" />
 <Button
 android:id="@+id/button"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="260dp"
 android:layout_marginRight="260dp"
 android:layout_marginBottom="175dp"
 android:text="ADD"
 android:textStyle="bold"
 android:onClick="add"
 app:backgroundTint="#E8F381" />
 <Button
 android:id="@+id/button3"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="266dp"
 android:layout_marginRight="266dp"
 android:layout_marginBottom="61dp"
 android:text="MUL"
 android:onClick="mul"
 app:backgroundTint="#A1FAA4" /><Button
 android:id="@+id/button4"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="108dp"
 android:layout_marginRight="108dp"
 android:layout_marginBottom="63dp"
 android:text="DIV"
 android:onClick="div"
 app:backgroundTint="#E6C28C" />
 <Button
 android:id="@+id/button2"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
android:layout_marginEnd="105dp"
 android:layout_marginRight="105dp"
 android:layout_marginBottom="182dp"
 android:text="SUB"
 android:onClick="sub"
 app:backgroundTint="#ECA9A9" />
 <TextView
 android:id="@+id/tv1"
 android:layout_width="86dp"
 android:layout_height="61dp"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="202dp"
 android:layout_marginRight="202dp"
 android:layout_marginBottom="274dp"
 android:text="0"
 android:textSize="36sp" />
</RelativeLayout>
```

```
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.TextView;
public class MainActivity extends AppCompatActivity {
EditText e1,e2;
TextView tv;
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 e1 =(EditText)findViewById(R.id.editText1);
 e2 = (EditText)findViewById(R.id.editText2);
 tv= (TextView)findViewById(R.id.tv1);
 }
 public void add(View v){
 int a1=Integer.parseInt(e1.getText().toString());
 int a2= Integer.parseInt(e2.getText().toString());
 int result=a1+a2;
tv.setText(""+result);
 }
 public void sub(View v){
 int a1=Integer.parseInt(e1.getText().toString());
 int a2= Integer.parseInt(e2.getText().toString());
 int result=a1-a2;
 tv.setText(""+result);
 }
 public void mul(View v){
 int a1=Integer.parseInt(e1.getText().toString());
 int a2= Integer.parseInt(e2.getText().toString());
 int result=a1*a2;
 tv.setText(""+result);
 }
 public void div(View v){
 float a1=Integer.parseInt(e1.getText().toString());
 float a2= Integer.parseInt(e2.getText().toString());
 float result=a1/a2;
 tv.setText(""+result);
 }
}
```

### ----Lab-4 ( checking user name and password is correct)-----

```
package com.example.app;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.TextView;
import android.widget.Toast;
import android.util.Patterns;


public class MainActivity extends AppCompatActivity {
    EditText etUsername, etPassword;
    Button btnStatus;
    TextView tvLoginStatus;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        etUsername = (EditText) findViewById(R.id.etUsername);
        etPassword = (EditText) findViewById(R.id.etPassword);
        btnStatus = (Button) findViewById(R.id.button);
        tvLoginStatus = (TextView) findViewById(R.id.tvLoginStatus);

        btnStatus.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                check(); 
            }
        });
    }

public void check(){
        if(etUsername.getText().toString().equals("mohit") && etPassword.getText().toString().equals("1234")){
            tvLoginStatus.setText("Login successful");
        }else{
            Toast.makeText(this, "Login fail", Toast.LENGTH_LONG).show();
        }
    }
}
```

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"

    android:layout_width="match_parent"
    android:layout_height="match_parent"
    >
    <TextView
        android:id="@+id/tvName"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="21dp"
        android:layout_marginTop="49dp"
        android:text="User Name"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/etUsername"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/tvName"
        android:layout_alignBottom="@+id/tvName"
        android:layout_alignParentEnd="true"
        android:layout_marginEnd="23dp"
        android:ems="10"
        android:inputType="textPersonName" />

    <TextView
        android:id="@+id/tvPass"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/tvName"
        android:layout_below="@+id/etUsername"
        android:layout_marginTop="32dp"
        android:text="Password"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/etPassword"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/tvPass"
        android:layout_alignBottom="@+id/tvPass"
        android:layout_alignStart="@+id/etUsername"
        android:ems="10"
        android:inputType="textPassword" />
    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/etPassword"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="38dp"
        android:text="LOGIN"
        />
    <TextView
        android:id="@+id/tvLoginStatus"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/button"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="100sp"
        />
</RelativeLayout>
```

### ---Lab 5(checking is the email valid or not)--------

```
package com.example.app;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.TextView;
import android.widget.Toast;
import android.util.Patterns;

public class MainActivity extends AppCompatActivity {
    EditText etUsername, etPassword;
    Button btnStatus;
    TextView tvLoginStatus;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        etUsername = (EditText) findViewById(R.id.etUsername);
        etPassword = (EditText) findViewById(R.id.etPassword);
        btnStatus = (Button) findViewById(R.id.button);
        tvLoginStatus = (TextView) findViewById(R.id.tvLoginStatus);

        btnStatus.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) { 
                validateEmail();
            }
        });
    }

 
public void validateEmail(){

        String emailToText = etUsername.getText().toString();
        if (!emailToText.isEmpty() && Patterns.EMAIL_ADDRESS.matcher(emailToText).matches()) {
            Toast.makeText(this, "Email Verified !", Toast.LENGTH_SHORT).show();
        } else {
            Toast.makeText(this, "Enter valid Email address !", Toast.LENGTH_SHORT).show();
        }
    }
}
```

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"

    android:layout_width="match_parent"
    android:layout_height="match_parent"
    >
    <TextView
        android:id="@+id/tvName"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="21dp"
        android:layout_marginTop="49dp"
        android:text="User Name"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/etUsername"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/tvName"
        android:layout_alignBottom="@+id/tvName"
        android:layout_alignParentEnd="true"
        android:layout_marginEnd="23dp"
        android:ems="10"
        android:inputType="textPersonName" />

    <TextView
        android:id="@+id/tvPass"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/tvName"
        android:layout_below="@+id/etUsername"
        android:layout_marginTop="32dp"
        android:text="Password"
        android:textSize="18sp" />

    <EditText
        android:id="@+id/etPassword"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/tvPass"
        android:layout_alignBottom="@+id/tvPass"
        android:layout_alignStart="@+id/etUsername"
        android:ems="10"
        android:inputType="textPassword" />
    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/etPassword"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="38dp"
        android:text="LOGIN"
        />
    <TextView
        android:id="@+id/tvLoginStatus"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/button"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="100sp"
        />
</RelativeLayout>

```


### ---------lab 6(different layouts in android 3, types)------

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"

    android:layout_width="match_parent"
    android:layout_height="match_parent"
    >

    <TextView
        android:id="@+id/layoutText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="21dp"
        android:layout_marginTop="49dp"
        android:text="RelativeLayout"
        android:textSize="18sp" />

    <TextView
        android:id="@+id/date1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="21dp"
        android:layout_marginTop="98dp"
        android:text="Date"
        android:textSize="18sp" />

    <TextView
        android:id="@+id/time1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="21dp"
        android:layout_marginTop="147dp"
        android:text="Time"
        android:textSize="18sp" />

</RelativeLayout>
```

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"

    android:layout_width="match_parent"
    android:layout_height="match_parent"
    >

    <TextView
        android:id="@+id/layoutText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="0dp"
        android:layout_marginTop="49dp"
        android:text="LinearLayout"
        android:textSize="18sp" />

    <TextView
        android:id="@+id/date1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="0dp"
        android:layout_marginTop="98dp"
        android:text="Date"
        android:textSize="18sp" />

    <TextView
        android:id="@+id/time1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="0dp"
        android:layout_marginTop="147dp"
        android:text="Time"
        android:textSize="18sp" />

</LinearLayout>
```

```
<?xml version="1.0" encoding="utf-8"?>
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/layoutText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="0dp"
        android:layout_marginTop="49dp"
        android:text="FrameLayout"
        android:textSize="18sp" />

    <TextView
        android:id="@+id/date1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="0dp"
        android:layout_marginTop="98dp"
        android:text="Date"
        android:textSize="18sp" />

    <TextView
        android:id="@+id/time1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="0dp"
        android:layout_marginTop="147dp"
        android:text="Time"
        android:textSize="18sp" />

</FrameLayout>
```

```
package com.example.lab6_1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import java.util.Calendar;
import java.util.Date;

import android.text.format.DateFormat;
import android.widget.TextView;
import java.text.SimpleDateFormat;
public class MainActivity extends AppCompatActivity {


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        TextView time_text;
        TextView date_text;
        date_text = (TextView) findViewById(R.id.date1);
        time_text = (TextView) findViewById(R.id.time1);

        Date d = new Date();
        CharSequence date  = DateFormat.format("HH:mm:ss", d.getTime());
        CharSequence time  = DateFormat.format("MMMM d, yyyy ", d.getTime());
        time_text.setText("Time: "+time);
        date_text.setText("Date: "+date);

    }
}
```

### ------Lab 7(counter in android)----

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:ignore="MissingConstraints"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/cntText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Counter: 1 "
        android:layout_marginTop="40dp"
        android:layout_marginLeft="40dp"
          />

    <Button
        android:id="@+id/strBtn"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="80dp"
        android:layout_marginLeft="40dp"
        android:text="Start" />
    <Button
        android:id="@+id/stpBtn"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="80dp"
        android:layout_marginLeft="180dp"
        android:text="Stop" />

</RelativeLayout>
```

```
package com.example.lab_8_201210030;
import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.os.Handler;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {
    TextView cntValueText;
    Button startBtn;
    Button stopBtn;
    static  Integer c;
    static Boolean stop;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        c=1;
        startBtn= (Button) findViewById(R.id.strBtn);
        stopBtn= (Button) findViewById(R.id.stpBtn);

        cntValueText=(TextView) findViewById(R.id.cntText);
        startBtn.setEnabled(true);
        stopBtn.setEnabled(false);

        startBtn.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                        stop=true;
                        startBtn.setEnabled(false);
                        stopBtn.setEnabled(true);
                        new Handler().postDelayed(new Runnable() {
                            @Override
                            public void run() {

                                if(stop) {
                                    c=c+1;
                                    cntValueText.setText("Counter: " + c.toString());
                                    onClick(startBtn);
                                }
                            }
                        }, 1000 );

                }

        });
        stopBtn.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                stop=false;
                c=1;
                startBtn.setEnabled(true);
                stopBtn.setEnabled(false);
                cntValueText.setText("Counter: " + c.toString());
            }
        });
}}
```

### ------Lab 8( changing background in app)--

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".MainActivity">
 <Button
 android:id="@+id/button1"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentRight="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="167dp"
 android:layout_marginRight="167dp"
 android:layout_marginBottom="409dp"
 android:text="CLICK HERE" />
</RelativeLayout>
```

```
package com.example.wallpaperchangeapplication;
import androidx.appcompat.app.AppCompatActivity;
import android.app.WallpaperManager;
import android.graphics.Bitmap;
import android.graphics.BitmapFactory;
 
25 Mobile Application Development
Department of Information Science & Engineering, Atria Institute of Technology 25
import android.graphics.drawable.BitmapDrawable;
import android.graphics.drawable.Drawable;
import android.os.Bundle;
import android.os.Handler;
import android.view.View;
import android.widget.Button;
import android.widget.Toast;
import java.io.IOException;
import java.util.Timer;
import java.util.TimerTask;
public class MainActivity extends AppCompatActivity {
 Button wallpaperChange;
 Timer mytimer;
 Drawable drawable;
 WallpaperManager wpm;
 int prev=1;

 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 mytimer=new Timer();
 wpm = WallpaperManager.getInstance(this);
 wallpaperChange=(Button)findViewById(R.id.button1);
 wallpaperChange.setOnClickListener(new View.OnClickListener() {
 @Override public void onClick(View view) {
 setwallpaper();
 }
 });
 }
private void setwallpaper() {
 Toast.makeText(this,"setting Wallpaper please wait.",Toast.LENGTH_LONG).show();
 mytimer.schedule(new TimerTask() {
 @Override
 public void run()
 {
 if(prev==1) {
 drawable = getResources().getDrawable(R.drawable.i1); prev = 2;
 }
 else if(prev==2) {
 drawable = getResources().getDrawable(R.drawable.i2); prev=3;
 }
else if(prev==3) {
 drawable = getResources().getDrawable(R.drawable.i3); prev=4;
 }
 else if(prev==4) {
 drawable = getResources().getDrawable(R.drawable.i4); prev=5;
 }
 else if(prev==5) {
 drawable = getResources().getDrawable(R.drawable.i5); prev=1;
 }
 Bitmap wallpaper = ((BitmapDrawable)drawable).getBitmap(); try {
 wpm.setBitmap(wallpaper);
 }
 catch (IOException e)
 { e.printStackTrace();
 }
 }
 },0,30000);
 }
 }
```

### ---- Lab 9(custom app bar )----

```
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fitsSystemWindows="true"
    android:orientation="vertical">

    <androidx.appcompat.widget.Toolbar
        android:id="@+id/toolbar"
        android:minHeight="?attr/actionBarSize"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:titleTextColor="@android:color/white"
        android:background="?attr/colorPrimary">
    </androidx.appcompat.widget.Toolbar>
</LinearLayout>
```

```
package com.example.viewsapp;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.Menu;
import androidx.appcompat.widget.Toolbar;

public class MainActivity extends AppCompatActivity {
    Toolbar toolbar;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Find the toolbar view inside the activity layout
          toolbar = (Toolbar) findViewById(R.id.toolbar);
        // Sets the Toolbar to act as the ActionBar for this Activity window.
        // Make sure the toolbar exists in the activity and is not null
        setSupportActionBar(toolbar);
    }

    // Menu icons are inflated just as they were with actionbar
    @Override
    public boolean onCreateOptionsMenu(Menu menu) {
        // Inflate the menu; this adds items to the action bar if it is present.
        getMenuInflater().inflate(R.menu.menu_main, menu);
        return true;
    }
}
```

```
<menu xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto">
    <item
        android:id="@+id/miCompose"
        android:icon="@drawable/nitlogo"
        app:showAsAction="ifRoom"
        android:title="Compose">
    </item>
    <item
        android:id="@+id/miProfile"
        android:icon="@drawable/profile"
        app:showAsAction="ifRoom|withText"
        android:title="Profile">
    </item>

    <item
        android:id="@+id/miLogout"
        android:icon="@drawable/logout"
        app:showAsAction="ifRoom|withText"
        android:title="Logout">
    </item>
</menu>
```

### -- lab 10 ( google maps api)----

*to be added*

### --- Lab 11 (Three types of sensors)-----

1. proixmity sensor
```
package com.example.sensorapp;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.content.Context;
import android.hardware.Sensor;
import android.hardware.SensorEvent;
import android.hardware.SensorEventListener;
import android.hardware.SensorManager;
import android.widget.TextView;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    // Creating variables for text view,  manager and our sensor.
    TextView sensorStatusTV;
    SensorManager sensorManager;
    Sensor proximitySensor;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        sensorStatusTV = findViewById(R.id.sensorStatusTV);
        // calling sensor service.
        sensorManager = (SensorManager) getSystemService(Context.SENSOR_SERVICE);

        // from sensor service we are calling proximity sensor
        proximitySensor = sensorManager.getDefaultSensor(Sensor.TYPE_PROXIMITY);

        // handling the case if the proximity sensor is not present in users device.
        if (proximitySensor == null) {
            Toast.makeText(this, "No proximity sensor found in device.", Toast.LENGTH_SHORT).show();
            finish();
        } else {
            // registering our sensor with sensor manager.
            sensorManager.registerListener(proximitySensorEventListener,
                    proximitySensor,
                    SensorManager.SENSOR_DELAY_NORMAL);
        }
    }

    // calling the sensor event class to detect the change in data when sensor starts working.
    SensorEventListener proximitySensorEventListener = new SensorEventListener() {
        @Override
        public void onAccuracyChanged(Sensor sensor, int accuracy) {
            // method to check accuracy changed in sensor.
        }

        @Override
        public void onSensorChanged(SensorEvent event) {
            // check if the sensor type is proximity sensor.
            if (event.sensor.getType() == Sensor.TYPE_PROXIMITY) {
                if (event.values[0] == 0) {
                    // here we are setting our status to our textview. if sensor event return 0 then object is closed
                    // to sensor else object is away from sensor.
                    sensorStatusTV.setText("Near");
                } else {
                    sensorStatusTV.setText("Away");
                }
            }
        }
    };
}
```

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/container"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/sensorStatusTV"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:layout_centerInParent="true"
        android:textAlignment="center"
        android:textSize="50dp" />

</RelativeLayout>
```

2. light sensor
```
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
 
    <TextView
        android:id="@+id/light_level"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerInParent="true"
        android:textSize="20sp" />
 
</RelativeLayout>
```

```
package com.example.sensorapp;
import androidx.appcompat.app.AppCompatActivity;

import android.content.Context;
import android.hardware.Sensor;
import android.hardware.SensorEvent;
import android.hardware.SensorEventListener;
import android.hardware.SensorManager;
import android.os.Bundle;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {
    private SensorManager sensorManager;
    private TextView lightLevel;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        lightLevel = (TextView) findViewById(R.id.light_level);
        sensorManager = (SensorManager) getSystemService(Context.SENSOR_SERVICE);
        Sensor sensor = sensorManager.getDefaultSensor(Sensor.TYPE_LIGHT);
        sensorManager.registerListener(listener, sensor, SensorManager.SENSOR_DELAY_NORMAL);

    }
    @Override
    protected void onDestroy() {
        super.onDestroy();
        if (sensorManager != null) {
            sensorManager.unregisterListener(listener);
        }
    }
    private SensorEventListener listener = new SensorEventListener() {
        @Override
        public void onSensorChanged(SensorEvent event) {
// The value of the first subscript in the values array is the current light intensity
            float value = event.values[0];
            lightLevel.setText("Current light level is " + value + " lx");
        }
        @Override
        public void onAccuracyChanged(Sensor sensor, int accuracy) {
        }
    };
}
```

3. accelerometer sensor
```
package com.example.sensorapp;
import android.graphics.Color;
import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    // create variables of the two class
    private Accelerometer accelerometer;
    private Gyroscope gyroscope;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // instantiate them with this as context
        accelerometer = new Accelerometer(this);
        gyroscope = new Gyroscope(this);

        // create a listener for accelerometer
        accelerometer.setListener(new Accelerometer.Listener() {
            //on translation method of accelerometer
            @Override
            public void onTranslation(float tx, float ty, float ts) {
                // set the color red if the device moves in positive x axis
                if (tx > 1.0f) {
                    getWindow().getDecorView().setBackgroundColor(Color.RED);
                }
                // set the color blue if the device moves in negative x axis
                else if (tx < -1.0f) {
                    getWindow().getDecorView().setBackgroundColor(Color.BLUE);
                }
            }
        });
        // create a listener for gyroscope
        gyroscope.setListener(new Gyroscope.Listener() {
            // on rotation method of gyroscope
            @Override
            public void onRotation(float rx, float ry, float rz) {
                // set the color green if the device rotates on positive z axis
                if (rz > 1.0f) {
                    getWindow().getDecorView().setBackgroundColor(Color.GREEN);
                }
                // set the color yellow if the device rotates on positive z axis
                else if (rz < -1.0f) {
                    getWindow().getDecorView().setBackgroundColor(Color.YELLOW);
                }
            }
        });
    }
    // create on resume method
    @Override
    protected void onResume() {
        super.onResume();

        // this will send notification to both the sensors to register
        accelerometer.register();
        gyroscope.register();
    }
    // create on pause method
    @Override
    protected void onPause() {
        super.onPause();

        // this will send notification in both the sensors to unregister
        accelerometer.unregister();
        gyroscope.unregister();
    }
}
```

```
package com.example.sensorapp;

import android.content.Context;
import android.hardware.Sensor;
import android.hardware.SensorEvent;
import android.hardware.SensorEventListener;
import android.hardware.SensorManager;

public class Accelerometer {

    // create an interface with one method
    public interface Listener {
        // create method with all 3 axis translation as argument
        void onTranslation(float tx, float ty, float ts);
    }

    // create an instance
    private Listener listener;

    // method to set the instance
    public void setListener(Listener l) {
        listener = l;
    }

    private SensorManager sensorManager;
    private Sensor sensor;
    private SensorEventListener sensorEventListener;

    // create constructor with
    // context as argument
    Accelerometer(Context context) {
        // create instance of sensor manager
        sensorManager = (SensorManager) context.getSystemService(Context.SENSOR_SERVICE);
        // create instance of sensor
        // with type linear acceleration
        sensor = sensorManager.getDefaultSensor(Sensor.TYPE_LINEAR_ACCELERATION);

        // create the sensor listener
        sensorEventListener = new SensorEventListener() {
            // this method is called when the device's position changes
            @Override
            public void onSensorChanged(SensorEvent sensorEvent) {
                // check if listener is different from null
                if (listener != null) {
                    // pass the three floats in listener on translation of axis
                    listener.onTranslation(sensorEvent.values[0], sensorEvent.values[1], sensorEvent.values[2]);
                }
            }
            @Override
            public void onAccuracyChanged(Sensor sensor, int i) {

            }
        };
    }
    // create register method sensor notifications
    public void register() {
        // call sensor manger's register listener pass the required arguments
        sensorManager.registerListener(sensorEventListener, sensor, SensorManager.SENSOR_DELAY_NORMAL);
    }

    // create method to unregister sensor notifications
    public void unregister() {
        // call sensor manger's unregister listener pass the required arguments
        sensorManager.unregisterListener(sensorEventListener);
    }
}
```

```
package com.example.sensorapp;
import android.content.Context;
import android.hardware.Sensor;
import android.hardware.SensorEvent;
import android.hardware.SensorEventListener;
import android.hardware.SensorManager;

public class Gyroscope {
    // create an interface with one method
    public interface Listener {
        // create method with all 3 axis translation as argument
        void onRotation(float tx, float ty, float ts);
    }
    // create an instance
    private Listener listener;
    // method to set the instance
    public void setListener(Listener l) {
        listener = l;
    }
    private SensorManager sensorManager;
    private Sensor sensor;
    private SensorEventListener sensorEventListener;

    // create constructor with context as argument
    Gyroscope(Context context) {

        // create instance of sensor manager
        sensorManager = (SensorManager) context.getSystemService(Context.SENSOR_SERVICE);

        // create instance of sensor with type gyroscope
        sensor = sensorManager.getDefaultSensor(Sensor.TYPE_GYROSCOPE);
        // create the sensor listener
        sensorEventListener = new SensorEventListener() {

            // this method is called when device's position changes
            @Override
            public void onSensorChanged(SensorEvent sensorEvent) {
                // check if listener is different from null
                if (listener != null) {
                    // pass the three floats in listener on rotation of axis
                    listener.onRotation(sensorEvent.values[0], sensorEvent.values[1], sensorEvent.values[2]);
                }
            }

            @Override
            public void onAccuracyChanged(Sensor sensor, int i) {

            }
        };
    }
    // create register method for sensor notifications
    public void register() {
        // call sensor manager's register listener and pass the required arguments
        sensorManager.registerListener(sensorEventListener, sensor, SensorManager.SENSOR_DELAY_NORMAL);
    }

    // create method to unregister sensor notifications
    public void unregister() {
        // call sensor manager's unregister listener and pass the required arguments
        sensorManager.unregisterListener(sensorEventListener);
    }
}
```

```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Accelerometer"
        android:textColor="#0F9D58"
        android:textSize="42dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

### ------Lab 12(road trip interface application)-------------

/// to be added..........





### ---------------lab 13 (add outlet to road trip app)-------------
/// to be added..........


