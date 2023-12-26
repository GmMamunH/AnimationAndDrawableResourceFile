# Custom Drawable Resource File <a href="https://github.com/GmMamunH/AnimationAndDrawableResourceFile"> GitHub </a>
## 1: bottom_curved.xml
```js
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android" >


    <item>
        <shape android:shape="rectangle" >
            <solid android:color="@android:color/transparent" />
            <corners android:radius="0dp" />
        </shape>
    </item>
    
    
    <item
        android:bottom="5dp"
        android:left="1dp"
        android:right="1dp"
        android:top="0dp">
        
        
        <shape android:shape="rectangle" >
            <solid
                android:color="#FFC107"
                />
            <corners
                android:bottomLeftRadius="20dip"
                android:bottomRightRadius="20dip"
                android:topRightRadius="0dip"
                />


        </shape>
        
        <shape android:shape="rectangle"  >
             <corners android:radius="0dip" />
             <stroke android:width="0dip" 
                 android:color="#10000000" />
         </shape>
                 
                     
    </item>

</layer-list>
```

## 2: bottom_shade.xml
```js
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android" >
    

    <item>
        <shape android:shape="rectangle" >
            <solid android:color="#61000000" />
            <corners android:radius="0dp" />
        </shape>
    </item>
    
    
    <item
        android:bottom="10dp"
        android:left="2dp"
        android:right="2dp"
        android:top="1dp">
        
        
        <shape android:shape="rectangle" >
            <solid android:color="#FFFFFF" />
            <corners android:radius="0dp" />
        </shape>
        
        <shape android:shape="rectangle"  >
             <corners android:radius="0dip" />
             <stroke android:width="0dip" 
                 android:color="#10000000" />
                 
                    
         </shape>
                 
                     
    </item>

</layer-list>
```

## 3: circle_colored.xml
```js
<?xml version="1.0" encoding="utf-8"?>
<shape
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="oval">

    <solid
        android:color="#FF9800"/>

    <size
        android:width="120dp"
        android:height="120dp"/>
</shape>
```

## 4: circle_transparent.xml
```js
<?xml version="1.0" encoding="utf-8"?>
<shape
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="oval">

    <solid
        android:color="@android:color/transparent"
        />

    <stroke
        android:color="#FFC107"
        android:width="5dp"
        />

    <size
        android:width="120dp"
        android:height="120dp"
        />
</shape>
```

## 5: circle_two_colored.xml
```js
<?xml version="1.0" encoding="utf-8"?>
<shape
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="oval">


    <gradient
        android:startColor="#FFC107"
        android:endColor="#FF5722"
        android:angle="135"
        />

    <size
        android:width="120dp"
        android:height="120dp"/>
</shape>
```

