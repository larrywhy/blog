---
layout: default
title: "android note"
date: 2015-02-04 23:14:10
---

# Unlock Your Screen JP .

I want to make a apps. that can unlock smart phone screen.

Similar to Unlock your screen apps , it is a japanese version.

# Purpose

For the purpose of practing Japanese .

To help people learn japanese by unlocking the screen.

---

Here are some notes about this project:

1. [adb command](http://style77125tech.pixnet.net/blog/post/17556680-%5Bandroid%5D-%E4%BD%BF%E7%94%A8adb%E6%8C%87%E4%BB%A4)

2. image must be **lowercase a-z, numbers 0-9 and underscore** in **drawable** directory, and the filename must begin on lowercase a-z.

3. add an **imageView** controls in **activity_main.xml**, then add `android:src="@drawable/your_image"`. 

4. In android, all resource will be generated to R.java, it can be seen the resource id in values base-16 (hexadecimal) for compiler.

5. An image is 3000 by 3000 pixels. If 4 bytes per pixel, how many MB of memory are required? -> 3000 * 3000 * 4 = 36000000 bytes = 36 MB.

6. Add images to **Project/res/drawable-hdpi/**, that is fine to add images to different Bitmaps, just put it on the correct directory. 

7. Modify the **main.xml**(which is at the directory **Project/res/layout/**), it can be alternated to different size(e.g. **landscape orientation**), just create a new directory named **layout-land**, and copy **main.xml** to the new directory.

8. **res/values** is used to hold default resource values.

9. Here are the qualifier names list: **Language, LayoutDirection, smallestWidth, Night mode, Screen orientation,etc. link:[qualifiers](http://developer.android.com/guide/topics/resources/providing-resources.html)
