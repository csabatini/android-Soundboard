android-Soundboard
================
A simple soundboard application for Android

![android-Soundboard Screenshot](http://i.imgur.com/eTKxZdX.png)

Usage
----
To add your own audio clips, place them in in the res\raw directory.

Then, update the arrays in res\values\arrays.xml with labels and resource IDs. Example:

```xml
...
<string-array name="labels">
    <item>One</item>
    <item>Two</item>
    <item>Three</item>
    ...
</string-array>

<integer-array name="ids">
    <item>@raw/one</item>
    <item>@raw/two</item>
    <item>@raw/three</item>
    ...
</integer-array>
...
```