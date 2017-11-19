# Updates for Android Support v26, and announce the library only support API 14+

# Support font family

* Put your own font in the res/font folder, and the developer can identity it from ids.
* Use in XML or code.
* Download the font using FontRequest method or set the attributes in layout and style.
* If your font doesn't exist on Google, you can trust your font provider to download your font.

# Support emoji

* Add the support dependency in Gradle, and require Google Play Service v11(Current, it is Beta version).
* API 19+
* If you don't use Google Play Service, you can change the dependency. However, it will occupy your device 7MB.

# Textview autosizing

* autoSizeTextType
* autoSizePresetSizes: font boundaries(array)
* min/max text size
* DynamicAnimation

# Others
* There is other sections to talk about it(Android Animations Spring to Life)
* VertorDrawable
* Fixed the fill rule of SVG bug in API 24.
* ActionBarDrawableToggle

# PreferenceDataStore

* Save Preference in cloud and asynchronous in local.
* If you want to use it, you need to check the callback and timeout in the main thread.


**Fixed issue:** after the drawer slides, the hamburger button will be animated. You need to write the one code to fix it.

# Features in the video from the comment
* TextView autosizing
* DynamicAnimation
* Vector Drawable
* Animated Vector Drawable
* Form Factors
* Android TV Leanback
* Notable Changes
* CloudDataStore
* FrameMetricsAggregator
* ActionBarDrawableToggle
