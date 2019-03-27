# CheckBoxGroup
Android CheckBoxGroup Library

[![](https://jitpack.io/v/grath92/CheckBoxGroup.svg)](https://jitpack.io/#grath92/CheckBoxGroup)


### Add it in your root build.gradle at the end of repositories:

```sh
allprojects {
   repositories {
		  ...
		  maven { url 'https://jitpack.io' }
	 }
}
```

### Add the dependency:

```sh
  dependencies {
	     implementation 'com.github.grath92:CheckBoxGroup:1.0.1'
  }
```


### Use it on your app:

```sh
   <com.gkrath.CheckBoxGroup
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@android:color/white"
        android:orientation="vertical">
        <CheckBox
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Good"/>

        <CheckBox
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Bed"/>
        <CheckBox
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Average"/>
    </com.gkrath.CheckBoxGroup>
```

```sh
   <com.gkrath.CheckBoxGroup
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="@android:color/white"
        android:layout_marginTop="@dimen/activity_vertical_margin"
        android:orientation="vertical">
        <CheckBox
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Male"/>

        <CheckBox
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Female"/>
    </com.gkrath.CheckBoxGroup>
```


