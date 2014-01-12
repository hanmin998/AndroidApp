AndroidApp
==========

Some Simple  Android-Apps
--------------------------------
        Android实习实例。
-------------------------------    
    ### Day_1：
    主要介绍了<LinearLayout></LinearLayout>布局下的各种控件的相关属性，
    <LinearLayout>:
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/LinearLayout1"
    android:layout_width="match_parent" 
    android:layout_height="match_parent"
    android:gravity="left" 
    android:background="#000000"
    android:orientation="vertical" />

    <TextView>：
    <TextView
        android:id="@+id/textView1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/web"
        android:autoLink="web"
        android:background="@drawable/a"
        tools:context=".MainActivity" />
    <!-- web。。。超链接 -->
    <!-- @string/。。。。是定义布局属性的唯一方式 -->
    <Button>:
    <Button
        android:id="@+id/button1"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:text="@string/email"
        android:autoLink="email" />"
    <EditText>:
    <EditText
        android:id="@+id/editText1"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:hint="@string/please_input"/>"
        ### Day_01：
        关于微信的登陆页面实现。


