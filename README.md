
## Build
#### Install android-js
```bash
npm i -g androidjs-builder
```
### For Windows  
#### Open file
```bash
C:\Users\:UserName:\.androidjs\cache\androidjs-sdk\res\values\styles.xml
```
#### Find
```xml
<style name="AppTheme" parent="@style/Theme.AppCompat.Light.NoActionBar"></style>
```
#### Add child
```xml
<item name="android:windowFullscreen">true</item>
```

---

> Dev build

```bash
androidjs build
```

> Release build

```bash
androidjs build --release
```
