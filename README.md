# Agenda_SQlite

LABORATORIO 2.2

trabajo realizado por:
  -Miranda M. Jhonn C.
  -Catucuago V. Juan P.
  _Moyano A. Darwin D.

Para ver mis repositorios puedes acceder a mi perfil y conocer más sobre mis proyectos

Perfil GitHub: Dzhon251 (github.com)

Construcción de un aplocativo en Android Studio en el lengiaje java.

![image](https://github.com/Dzhon251/Agenda_SQlite/assets/133244354/8df88af9-56d8-4498-92a0-6b9bf826025d)
![image](https://github.com/Dzhon251/Agenda_SQlite/assets/133244354/50beca9a-321b-47b9-9e8f-93ccaea6af75)
![image](https://github.com/Dzhon251/Agenda_SQlite/assets/133244354/7ffe4ac0-be8a-49bc-b6b5-f6b1e7516d9e)
![image](https://github.com/Dzhon251/Agenda_SQlite/assets/133244354/4fc32e2a-f11f-4211-9022-af95893d3577)
![image](https://github.com/Dzhon251/Agenda_SQlite/assets/133244354/a0abed38-57f1-409c-93fe-1afebcd17472)




CÓDIGO DEL PROYECTO

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:paddingBottom="20dp"
    android:paddingLeft="20dp"
    android:paddingRight="20dp"
    android:paddingTop="20dp">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="120dp"
            android:layout_gravity="center_horizontal"
            android:layout_marginTop="40dp"
            android:src="@drawable/espe_logo"
            android:contentDescription="TODO"
            tools:ignore="ContentDescription,HardcodedText" />

        <TextView
            android:id="@+id/textView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="AGENDA"
            android:textAlignment="center"
            android:textSize="20sp" />

        <TextView
            android:id="@+id/textView3"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nombre:" />

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <EditText
                android:id="@+id/txtNombre"
                android:layout_width="247dp"
                android:layout_height="wrap_content"
                android:ems="10"
                android:inputType="text" />

            <Button
                android:id="@+id/btnBuscar"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Buscar"
                android:background="@color/colorTurquoise"/>
        </LinearLayout>

        <TextView
            android:id="@+id/textView5"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Telefono" />

        <EditText
            android:id="@+id/txtTelefono"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:ems="10"
            android:inputType="text" />

        <TextView
            android:id="@+id/textView6"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Correo Electronico" />

        <EditText
            android:id="@+id/txtCorreo"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:ems="10"
            android:inputType="text" />

        <Button
            android:id="@+id/btnAgregar"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="10dp"
            android:background="@color/colorTurquoise"
            android:backgroundTint="@color/colorTurquoise"
            android:text="Agregar" />

        <Button
            android:id="@+id/btnEditar"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Editar"
            android:layout_marginTop="10dp"
            android:background="@color/colorTurquoise"/>

        <Button
            android:id="@+id/btnEliminar"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Eliminar"
            android:layout_marginTop="10dp"
            android:background="@color/colorTurquoise"/>

        <Button
            android:id="@+id/btnMostrar"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Mostrar"
            android:layout_marginTop="10dp"
            android:background="@color/colorTurquoise"/>
    </LinearLayout>
</RelativeLayout>
