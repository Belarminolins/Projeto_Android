<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:weightSum="1"
    android:background="#1e90ff"
    android:gravity="center"
    android:id="@+id/telalogin">




    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="E-mail"
        android:textAlignment="center"
        android:id="@+id/edtemail"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Senha"
        android:textAlignment="center"
        android:inputType="textPassword"
        android:ems="10"
        android:id="@+id/edtsenha"/>


    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:id="@+id/btentrar"
            android:layout_width="180dp"
            android:layout_height="wrap_content"
            android:text="Entrar"
            android:textColor="#0000ff"/>


        <Button
            android:id="@+id/btrecuperar"
            android:layout_width="180dp"
            android:layout_height="wrap_content"
            android:text="Recuperar Senha"
            android:textColor="#0000ff"/>


    </LinearLayout>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="não tem conta ainda? Crie uma!"
        android:textStyle="bold"
        android:textSize="16dp"
        android:layout_marginTop="20dp"
        android:textColor="#fff"
        android:gravity="center"
        android:id="@+id/txtcadastro"
        />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Entrar pelo Facebook!"
        android:textStyle="bold"
        android:textSize="16dp"
        android:layout_marginTop="20dp"
        android:textColor="#fff"
        android:gravity="center"
        android:id="@+id/txtfacebook">
        
    </TextView>

