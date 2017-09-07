# AnimationBottomBar

I saw a awesome bottomBar Design from [dribbble](https://dribbble.com/shots/2071319-GIF-of-the-Tapbar-Interactions),and I make it come true.
just like this
  
![](http://oe38oe3ti.bkt.clouddn.com/17-9-6/16156701.jpg)
# How to use
```xml
 <com.mran.bottombar.AnimationBottomBar
      android:layout_width="match_parent"
      android:layout_height="100dp"
      android:id="@+id/bottomBar"
      app:textColor="@color/colorAccent"
      app:backgruond="@color/white"
      app:textSize="16sp"
      app:selectTextColor="@color/blue"
  />
```
```java
 AnimationBottomBar mAnimationBottomBar;
 mAnimationBottomBar = (AnimationBottomBar) findViewById(R.id.bottom);
 mAnimationBottomBar.addItem(new BottomItem(R.drawable.h, "one"))
                    .addItem(new BottomItem(R.drawable.h, "two"))
                    .addItem(new BottomItem(R.drawable.h, "three"))
                    .addItem(new BottomItem(R.drawable.h, "four"))
                    .addItem(new BottomItem(R.drawable.h, "five"))
                    .build();
```