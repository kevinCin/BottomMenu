
# BottomBar


## Version 1.0 released!

[The latest version before that can be found in the v1 branch](https://github.com/kevinjam/Bottom-Bar-Android)

* Cleaner code and Easy to use
* No more unnecessary stuff or spaghetti mess
* Now the look, feel and behavior is defined in XML, as it should be
* No more nasty regressions, thanks to the automated tests
* **Everything is a little different compared to earlier, but it's for the greater good!**

[How to contribute](https://github.com/kevinjam/Bottom-Bar-Android/master/README.md#contributions)

[Changelog](https://github.com/kevinjam/Bottom-Bar-Android/master/CHANGELOG.md)

## What?

A custom view component that mimics the new [Material Design Bottom Bar](https://www.google.com/design/spec/components/bottom-navigation.html).

## Does it work on my HTC Phone ....Yes?

Nope. The minSDK version is **API level 11 (Honeycomb).**

## Gimme that Gradle sweetness, pls?

```Gradle
compile 'com.kevinjanvier.hackmtn:bottom-Menu:1.0'
```

**Maven:**
```xml
<dependency>
  <groupId>com.kevinjanvier.hackmtn</groupId>
  <artifactId>bottom-Menu</artifactId>
  <version>1.0</version>
  <type>pom</type>
</dependency>
```

## How?

You can add items by **writing a XML resource file**.

### What about Tablets?

Specify a different layout for your activity in.

**res/layout/activity_main.xml:**

```xml
 <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="50dp"
                android:orientation="vertical"
                android:layout_weight="1"
                android:id="@+id/contact">

                <ImageView

                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:layout_marginTop="10dp"
                    android:background="@drawable/ic_people"/>
                <com.kevinjanvier.hackmtn.customfonts.MyTextView


                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="Contact"
                    android:letterSpacing="0.1"
                    android:textSize="12dp"
                    android:textAlignment="center"
                    android:textColor="#000"/>
            </LinearLayout>
```

### I will Add more Stuff Once I get time

Easy-peasy!


Send me a pull request with modified README.md to get a shoutout!

## Contributions

Feel free to create issues and pull requests.

When creating pull requests, **more is more:** I'd like to see ten small pull requests separated by feature rather than all those combined into a huge one.

## License

```
BottomBar library for Android
Copyright (c) 2017 Kevin Janvier Chinabalire(https://github.com/kevinjam).

Licensed under the Apache License, Version 1.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-1.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
