CircleIndicator
===============
a lightweight viewpager indicator like in nexus 5 launcher 

![CircleIndicator](/screenshot.gif)

Gradle
------------

**version 1.1.0 (```minSdkVersion="14"```)**
```groovy
dependencies {
    compile 'me.relex:circleindicator:1.1.0@aar'
}
```


**version 1.0.0 (```minSdkVersion="8"```)**
```groovy
dependencies {
    compile 'com.nineoldandroids:library:2.4.+'
    compile 'me.relex:circleindicator:1.0.0@aar'
}
```

Usage
--------
```xml
	<me.relex.circleindicator.CircleIndicator
        android:layout_width="fill_parent"
        android:layout_height="40dp"/>
```

#####Properties:

* `app:ci_width`
* `app:ci_height`
* `app:ci_margin`
* `app:ci_animator`
* `app:ci_drawable`


