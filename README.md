juahya
======

juahya is android real time xml layout inflater<br />

version 1.0 2014-05-22
###     
    support android view
         CheckBox －－》IFCheckBox
         EditText －－》IFEditText
         ImageView－－》IFImageView
         TextView－－》IFTextView
    support android layout   
         LinearLayout－－》IFLinearLayout
         RelativeLayout－－》IFRelativeLayout
what can juahya do ?
======

you can use juahya to prase your custom layout xml file from internet,sdcard,sqlite ...<br />
###
    how to build your custom view inflater
        1.add IFXXX on com.xml.inflate.inflater
            xxx is android view
        2.config you IFxxx to com.xml.inflate.factory.IFLalterSImpleLinearLayoutFactory
        3.change your xml layout you can  see some of the things juahya used in his magic tricks ,

###
    how to build your custom juahyaview inflater
        1.add IFJxxx on com.xml.inflate.inflater.juahya
            IFJxxx is extends IFXXX and add juahya ATTRIBUTE
        2.config you IFxxx to com.xml.inflate.factory.IFLalterSImpleLinearLayoutFactory
        3.change your xml layout you can  see some of the things juahya used in his magic tricks
eg file [test.xml](jixieshi999.github.io/ilife/juahya/test.xml)
###
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="fill_parent" android:layout_height="fill_parent" android:orientation="vertical" >
        <!-- ......layout...... -->
        <TextView   android:layout_width="wrap_content"  android:layout_height="wrap_content"  
            android:text="输入用户名" />
    </LinearLayout>
Acknowledgements
======

[Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader) for the img lazy loader<br />


======
ps : after finish it i thought it is like a html praser lol<br />

