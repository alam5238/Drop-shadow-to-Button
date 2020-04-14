# Drop-shadow-to-Button
Drop-shadow to Button in Android Studio

Create a drawable 'xml' background file in res > drawable folder. Than add it to Button background properties.

### shadow.xml
```
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item>
        <layer-list>
            <item android:right="5dp" android:top="5dp">
                <shape>
                    <corners android:radius="3dp" />
                    <solid android:color="#989898" />
                </shape>
            </item>
            <item android:bottom="2dp" android:left="2dp">
                <shape>
                    <gradient android:angle="270"
                        android:endColor="#00000000" android:startColor="#00000000" />
                    <stroke android:width="1dp" android:color="#00000000" />
                    <corners android:radius="4dp" />
                    <padding android:bottom="10dp" android:left="10dp"
                        android:right="10dp" android:top="10dp" />
                </shape>
            </item>
        </layer-list>
    </item>

</selector>
```
