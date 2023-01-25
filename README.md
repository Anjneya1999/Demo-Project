<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <RelativeLayout
        android:layout_height="wrap_content"
        android:layout_width="match_parent">
        
        <androidx.cardview.widget.CardView
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:elevation="10dp"
            app:cardCornerRadius="10dp"
            app:cardElevation="10dp">

        <com.smarteist.autoimageslider.SliderView
            android:id="@+id/imageSlider"
            android:layout_width="match_parent"
            android:layout_height="310dp"
            app:sliderAnimationDuration="600"
            app:sliderAutoCycleDirection="back_and_forth"
            app:sliderAutoCycleEnabled="true"
            app:sliderIndicatorAnimationDuration="600"
            app:sliderIndicatorGravity="center_horizontal|bottom"
            app:sliderIndicatorMargin="15dp"
            app:sliderIndicatorOrientation="horizontal"
            app:sliderIndicatorPadding="3dp"
            app:sliderIndicatorRadius="3dp"
            app:sliderIndicatorSelectedColor="@color/teal_200"
            app:sliderIndicatorUnselectedColor="@color/teal_200"
            app:sliderScrollTimeInSec="1"
            app:sliderStartAutoCycle="true" >

            <ImageView
                android:layout_width="match_parent"
                android:src="@mipmap/ic_launcher"
                android:layout_height="280dp"/>

            </com.smarteist.autoimageslider.SliderView>
        </androidx.cardview.widget.CardView>
    </RelativeLayout>


</LinearLayout>



