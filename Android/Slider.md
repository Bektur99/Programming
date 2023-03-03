<FrameLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@color/white"
        app:layout_constraintTop_toTopOf="parent">

        <com.google.android.material.slider.Slider
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:stepSize="1"
            android:tickMark="@drawable/ic_range_slider_tick_mark"
            android:valueFrom="0"
            android:valueTo="1000"
            app:haloColor="@color/blue"
            app:thumbColor="@color/white"
            app:thumbRadius="10dp"
            app:thumbStrokeColor="@color/blue"
            app:thumbStrokeWidth="1.5dp"
            app:tickColor="@color/blue"
            app:tickVisible="true" />
    </FrameLayout>