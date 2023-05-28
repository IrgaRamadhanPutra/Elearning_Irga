# Elearning_Irga

NAMA : IRGA RAMADHAN PUTRA 
<br>
KELAS : 312010067
<br>
// layout account

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView2"
        android:layout_width="370dp"
        android:layout_height="52dp"
        android:text="Search"
        android:textColor="#000000"
        tools:layout_editor_absoluteX="20dp"
        tools:layout_editor_absoluteY="279dp" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="368dp"
        android:layout_height="52dp"
        android:text="Reset Password"
        android:textColor="#000000"
        tools:layout_editor_absoluteX="20dp"
        tools:layout_editor_absoluteY="351dp" />

    <TextView
        android:id="@+id/textView4"
        android:layout_width="363dp"
        android:layout_height="56dp"
        android:text="Log Out"
        android:textColor="#000000"
        tools:layout_editor_absoluteX="21dp"
        tools:layout_editor_absoluteY="441dp" />

    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="16dp"
        android:layout_marginEnd="16dp"
        app:cardCornerRadius="8dp"
        app:cardElevation="4dp"
        app:cardUseCompatPadding="true"
        android:textColor="@color/pinkMuda"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toTopOf="@id/textView2"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent">


        <LinearLayout
            android:layout_width="357dp"
            android:layout_height="232dp"
            android:background="#FFC0CB"
            android:orientation="horizontal"
            android:padding="16dp">


            <ImageView
                android:id="@+id/imageView2"
                android:layout_width="316dp"
                android:layout_height="156dp"
                android:layout_gravity="center_horizontal|bottom"
                android:layout_marginBottom="16dp"
                android:layout_weight="1"
                android:src="@mipmap/ic_launcher" />


            <Switch
                android:id="@+id/switch1"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content" />

        </LinearLayout>

    </androidx.cardview.widget.CardView>



    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="72dp"
        android:layout_height="61dp"
        android:layout_weight="1"
        android:src="@mipmap/home"
        tools:layout_editor_absoluteX="16dp"
        tools:layout_editor_absoluteY="654dp" />

    <ImageView
        android:id="@+id/imageView9"
        android:layout_width="72dp"
        android:layout_height="61dp"
        android:layout_weight="1"
        android:src="@mipmap/warning"
        tools:layout_editor_absoluteX="115dp"
        tools:layout_editor_absoluteY="654dp" />

    <ImageView
        android:id="@+id/imageView11"
        android:layout_width="72dp"
        android:layout_height="61dp"
        android:layout_weight="1"
        android:src="@mipmap/book"
        tools:layout_editor_absoluteX="227dp"
        tools:layout_editor_absoluteY="654dp" />

    <ImageView
        android:id="@+id/imageView10"
        android:layout_width="72dp"
        android:layout_height="61dp"
        android:layout_weight="1"
        android:src="@mipmap/account"
        tools:layout_editor_absoluteX="323dp"
        tools:layout_editor_absoluteY="654dp" />

![image](https://user-images.githubusercontent.com/101645216/236657446-deac1b6d-52c7-463c-9bac-96cb6f849ece.png)

</androidx.constraintlayout.widget.ConstraintLayout>




// layout home

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".dashboard">


  <ImageView
      android:id="@+id/imageView3"
      android:layout_width="60dp"
      android:layout_height="58dp"
      app:srcCompat="@mipmap/home"
      tools:layout_editor_absoluteX="16dp"
      tools:layout_editor_absoluteY="657dp" />

  <ImageView
      android:id="@+id/imageView13"
      android:layout_width="60dp"
      android:layout_height="58dp"
      app:srcCompat="@mipmap/warning"
      tools:layout_editor_absoluteX="314dp"
      tools:layout_editor_absoluteY="657dp" />

  <ImageView
      android:id="@+id/imageView8"
      android:layout_width="60dp"
      android:layout_height="58dp"
      app:srcCompat="@mipmap/account"
      tools:layout_editor_absoluteX="109dp"
      tools:layout_editor_absoluteY="657dp" />



  <ImageView
      android:id="@+id/imageView12"
      android:layout_width="60dp"
      android:layout_height="58dp"
      app:srcCompat="@mipmap/book"
      tools:layout_editor_absoluteX="208dp"
      tools:layout_editor_absoluteY="657dp" />


  <androidx.cardview.widget.CardView
      android:layout_width="410dp"
      android:layout_height="293dp"
      android:layout_margin="16dp"
      android:background="@drawable/oval_shape"
      app:cardCornerRadius="8dp"
      tools:layout_editor_absoluteX="-2dp"
      tools:layout_editor_absoluteY="8dp">

    <LinearLayout
        android:layout_width="386dp"
        android:layout_height="281dp"
        android:layout_margin="16dp"
        android:background="#87CEEB"
        android:gravity="center"
        android:orientation="vertical">

    <LinearLayout
        android:layout_width="384dp"
        android:layout_height="281dp"
        android:layout_margin="16dp"
        android:background="#ADD8E6"
        android:gravity="center"
        android:orientation="vertical">

      <LinearLayout
          android:layout_width="match_parent"
          android:layout_height="wrap_content"
          android:gravity="center_vertical"
          android:orientation="horizontal">

        <ImageView
            android:layout_width="60dp"
            android:layout_height="wrap_content"
            android:layout_marginEnd="8dp"
            android:src="@mipmap/menu" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="E Learning"
            android:textColor="#FFFFFF"
            android:textSize="35sp"
            android:textStyle="bold" />

        <ImageView
            android:layout_width="36dp"
            android:layout_height="30dp"
            android:layout_marginStart="8dp"
            android:src="@mipmap/cari" />

      </LinearLayout>

      <LinearLayout
          android:layout_width="match_parent"
          android:layout_height="wrap_content"
          android:orientation="horizontal"
          android:padding="16dp">


        <TextView
            android:layout_width="179dp"
            android:layout_height="108dp"
            android:layout_weight="1"
            android:paddingStart="16dp"
            android:text="Online Education"

            android:textColor="#FFFFFF"
            android:textSize="32sp"
            android:textStyle="bold" />

        <ImageView
            android:layout_width="162dp"
            android:layout_height="128dp"
            android:layout_marginEnd="16dp"
            android:background="@drawable/oval_shape"
            android:src="@mipmap/toga" />

      </LinearLayout>

    </LinearLayout>

  </androidx.cardview.widget.CardView>

  <androidx.constraintlayout.helper.widget.Flow
      android:layout_width="148dp"
      android:layout_height="287dp"
      android:background="#D3D3D3"
      tools:layout_editor_absoluteX="16dp"
      tools:layout_editor_absoluteY="349dp" />

  <androidx.constraintlayout.helper.widget.Flow
      android:layout_width="156dp"
      android:layout_height="286dp"
      android:background="#D3D3D3"
      tools:layout_editor_absoluteX="231dp"
      tools:layout_editor_absoluteY="350dp" />
  <ImageView
      android:id="@+id/imageView14"
      android:layout_width="71dp"
      android:layout_height="78dp"
      app:srcCompat="@mipmap/book"
      tools:layout_editor_absoluteX="49dp"
      tools:layout_editor_absoluteY="368dp" />

  <ImageView
      android:id="@+id/imageView15"
      android:layout_width="79dp"
      android:layout_height="74dp"
      app:srcCompat="@mipmap/piagam"
      tools:layout_editor_absoluteX="49dp"
      tools:layout_editor_absoluteY="457dp" />

  <ImageView
      android:id="@+id/imageView16"
      android:layout_width="77dp"
      android:layout_height="67dp"
      app:srcCompat="@mipmap/teacher"
      tools:layout_editor_absoluteX="49dp"
      tools:layout_editor_absoluteY="543dp" />

  <androidx.constraintlayout.widget.Group
      android:id="@+id/group"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content"
      tools:layout_editor_absoluteX="69dp"
      tools:layout_editor_absoluteY="262dp" />

  <ImageView
      android:id="@+id/imageView17"
      android:layout_width="84dp"
      android:layout_height="74dp"
      app:srcCompat="@mipmap/people"
      tools:layout_editor_absoluteX="268dp"
      tools:layout_editor_absoluteY="368dp" />

  <ImageView
      android:id="@+id/imageView18"
      android:layout_width="80dp"
      android:layout_height="69dp"
      app:srcCompat="@mipmap/paper"
      tools:layout_editor_absoluteX="269dp"
      tools:layout_editor_absoluteY="457dp" />

  <ImageView
      android:id="@+id/imageView19"
      android:layout_width="82dp"
      android:layout_height="74dp"
      app:srcCompat="@mipmap/paper1"
      tools:layout_editor_absoluteX="270dp"
      tools:layout_editor_absoluteY="543dp" />

  <androidx.constraintlayout.widget.Guideline
      android:id="@+id/guideline2"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content"
      android:orientation="horizontal"
      app:layout_constraintGuide_end="381dp" />

  <EditText
      android:id="@+id/editTextTextPersonName4"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content"
      android:ems="10"
      android:inputType="textPersonName"
      android:text="Categry"
      tools:layout_editor_absoluteX="16dp"
      tools:layout_editor_absoluteY="304dp" />


</androidx.constraintlayout.widget.ConstraintLayout>



![image](https://user-images.githubusercontent.com/101645216/236657426-51942a36-a103-4b7d-a55f-c9c672552af8.png)
