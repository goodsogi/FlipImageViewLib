This library is deprecated. You should be compatible API 14+ and make your own animations. Just rotate on your axis and add a small Z translation.

FlipImageView
==================

Description
-----------
Small android lib allowing you to flip an imageview easily, by extending FlipImageView.

This lib is based on the FlipAnimator by coomar. All the credits goes to him.

Check the sample app here https://play.google.com/store/apps/details?id=fr.castorflex.android.flipimageview

XML Usage
---------
```xml
<fr.castorflex.android.flipimageview.library.FlipImageView
       xmlns:fiv="http://schemas.android.com/apk/res-auto"
       android:id="@+id/imageview"
       android:layout_width="match_parent"
       android:layout_height="match_parent"
       android:src="@drawable/YOUR_DEFAULT_DRAWABLE"
       fiv:flipDrawable="@drawable/YOUR_FLIPPED_DRAWABLE"
       fiv:flipDuration="YOUR_DURATION_IN_MS"
       fiv:flipInterpolator="@android:anim/YOUR_INTERPOLATOR"
       fiv:flipRotations="none|x|y|z"
       fiv:isAnimated="true|false"
       fiv:isFlipped="true|false"/>
```

You will find a more detailed explanation here http://castorflex.github.io/blog/2013/04/16/flip-your-imageviews/

License
-------

```
"THE BEER-WARE LICENSE" (Revision 42):
You can do whatever you want with this stuff.
If we meet some day, and you think this stuff is worth it, you can buy me a beer in return.
```

[![Analytics](https://ga-beacon.appspot.com/UA-32954204-2/FlipImageView/readme)](https://github.com/igrigorik/ga-beacon)
