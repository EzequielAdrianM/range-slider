# range-slider
Android range slider library.

# Screenshot

![range-slider Screenshot](Screenshot.gif)

# Setup

* In your `build.gradle` :

```gradle
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
    implementation 'com.github.EzequielAdrianM:range-slider:1.1'
}
```

* [Sample](sample/src/main)

# API

* `public void setOnValueChangedListener(OnValueChangedListener onValueChangedListener)`
* `public void setRangeValues(ArrayList<Integer> values)`
* `public void setMinAndMaxValue(int minValue, int maxValue)`
* `public int getMinValue()`
* `public int getMaxValue()`

# License

MIT
