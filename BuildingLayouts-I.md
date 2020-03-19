# Building Layouts I

## [Vocabulary](https://developers.google.com/android/for-all/vocab-words/?utm_source=udacity&utm_medium=course&utm_campaign=android_basics)

- Layout
- UI (User Interface)
- TextView
- ImageView
- Button
- Camel Case
- IDE (Integrated Development Environment)
- Code
- XML
- XML Element
- Tag
- Closing tags
- Attributes
- Syntax
- Android Studio
- Device
- Density Independent Pixels (dp)
- Hard coding (avoid it)
- wrap_content (shrink-wrap the View around its content)
- Scale Independent Pixels (sp)
- Hex color
- Documentation

## [Take a screenshot](https://developer.android.com/studio/debug/am-screenshot.html)

## [Material Design - Typography](https://material.io/design/typography/#type-scale)

## [Material Design - Color](https://material.io/design/color/#color-usage-palettes)

## [Common Android Views](https://drive.google.com/file/d/0B5XIkMkayHgRMVljUVIyZzNmQUU/view)

- TextView - displays text
- ImageView - displays image
- Button - button with text label
- View - plain rectangule
- EditText - text field that you can type into
- Spinner - click on it to show a list of dropdown options
- CheckBox - checkbox with text label
- RadioButton - radio button (where you can select one out of a group of radio buttons)
- RatingBar - star rating
- Switch - on/off switch that you can drag right or left (or just tap to toggle the state)
- SeekBar - Displays progress and allows you to drag the handle anywhere in the bar (i.e. for music or video player)
- SearchView - A search field that you can type a query into
- ProgressBar - loading spinner
- ProgressBar - Horizontal loading indicator

## Text appearance tip
```
android:textAppearance="?android:textAppearanceLarge"
android:textAppearance="?android:textAppearanceMedium"
android:textAppearance="?android:textAppearanceSmall"
```

## HexColor
```
android:background="#000000"
android:textColor="#FFFFFF"
```

## ImageView - scaleType
```
android:src="@drawable/imageExample"
android:layout_width="wrap_content"
//android:layout_width="100dp"
android:layout_height="wrap_content"
android:scaleType="center"
//android:scaleType="centerCrop"
```
