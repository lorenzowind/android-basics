# Building Layouts II

## [Vocabulary](https://developers.google.com/android/for-all/vocab-words/?utm_source=udacity&utm_medium=course&utm_campaign=android_basics)

- ViewGroups
- Root View
- Father, Child and Sibling
- LinearLayout (vertical column or horizontal row)
- RelativeLayout (relative to parent or other children)
- match_parent (expand horizontally to occupy the full width of its parent)
- Layout parameter of the ViewGroup
- layout_weight (set an equal value in each child view to get a same distance)
- Portrait and landscape
- id (identify the components to use as a reference in relative layout)
- padding (content spacing inside the view)
- margin (need a ViewGroup)

## [LinearLayout layout_weight](https://developer.android.com/guide/topics/ui/layout/linear.html?utm_source=udacity&utm_medium=course&utm_campaign=android_basics)

## [RelativeLayout parameters](https://developer.android.com/reference/android/widget/RelativeLayout.LayoutParams.html?utm_source=udacity&utm_medium=course&utm_campaign=android_basics)

## Adding XML namespace in the Root View
```
xmlns:android="http://schemas.android.com/apk/res/android"
```

## Child view in center of the parent
```
android:layout_centerInParent="true"
//android:layout_centerHorizontal="true"
```

## Child view relative to parent
```
android:layout_alignParentTop="true"
```

## Assigning view ID names
```
android:id="@+id/..."
```

## Positioning children relative to other views
```
android:layout_toLeftOf="@id/..."
```

## Adding margin or padding in a view
```
android:layout_marginBottom="8dp"
android:padding="16dp"
//android:paddingTop="8dp"
```