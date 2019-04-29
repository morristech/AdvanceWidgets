# AdvanceWidgets
Customized views like TextView, Edittext, Layouts,RoundImageView, Zoom ImageView etc.

How to
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.MdFarhanRaja:AdvanceWidgets:1.2'
	}
  



# AdvanceTextView

    <com.farhan.widgets.AdvanceTextView
        android:layout_width="match_parent"
        android:layout_height="45dp"
        android:gravity="center"
        android:text="With Corner Radius"
        app:atv_borderColor="@color/colorAccent"
        app:atv_borderEnable="true"
        app:atv_borderWidth="1.5dp"
        app:atv_cornerRadius="5dp"
        app:textAllCaps="false" />

    <com.farhan.widgets.AdvanceTextView
        android:layout_width="match_parent"
        android:layout_height="45dp"
        android:layout_marginTop="30dp"
        android:gravity="center"
        android:text="With Custom Corner Radius"
        app:atv_borderColor="@color/colorAccent"
        app:atv_borderEnable="true"
        app:atv_borderWidth="1.5dp"
        app:atv_bottomLeftCornerRadius="5dp"
        app:atv_bottomRightCornerRadius="5dp"
        app:atv_customCornerRadius="true" />

    <com.farhan.widgets.AdvanceTextView
        android:layout_width="match_parent"
        android:layout_height="45dp"
        android:layout_marginTop="30dp"
        android:gravity="center"
        android:text="With Custom Font"
        app:atv_borderColor="@color/colorAccent"
        app:atv_borderEnable="true"
        app:atv_borderWidth="1.5dp"
        app:atv_bottomLeftCornerRadius="50dp"
        app:atv_customCornerRadius="true"
        app:atv_fontPath="good_times.ttf"
        app:atv_topLeftCornerRadius="50dp" />
	
All Attributes:

        app:atv_cornerRadius=""
        app:atv_borderEnable=boolean
        app:atv_borderColor=color
        app:atv_borderWidth=dimention
        app:atv_backgroundColor=color
        app:atv_fontPath=font path with extention
        app:atv_customCornerRadius=boolean
        app:atv_topLeftCornerRadius=dimention
        app:atv_topRightCornerRadius=dimention
        app:atv_bottomLeftCornerRadius=dimention
        app:atv_bottomRightCornerRadius=dimention
