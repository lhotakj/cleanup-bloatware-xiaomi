# Cleanup Bloatware XIAOMI

# Preparation
1. Get the <a href='https://developer.android.com/studio/command-line/adb?gclid=CjwKCAjw64eJBhAGEiwABr9o2A7h6fI7oELgiabyTToR0a_qcV1MkDk1ZqTXzT-YFuIFxUUr2SYjbBoCQskQAvD_BwE&gclsrc=aw.ds'>ADB</a>
2. Activate developers more
3. Turn on debug mode

# Cleanup
1. Connect your device to USB
2. Run `adb shell`
3. Run the following commands

```
pm uninstall --user 0 com.google.android.feedback
pm uninstall --user 0 com.google.android.apps.wellbeing
pm uninstall --user 0 pl.zdunex25.updater 
pm uninstall --user 0 com.caf.fmradio
pm uninstall --user 0 com.miui.fmservice
pm uninstall --user 0 com.miui.fm
pm uninstall --user 0 com.miui.mishare.connectivity
pm uninstall --user 0 com.tencent.soter.soterserver
pm uninstall --user 0 com.xiaomi.joyose 
pm uninstall --user 0 com.xiaomi.location.fused
pm uninstall --user 0 com.xiaomi.payment
pm uninstall --user 0 com.miui.yellowpage 
```

Refer to the complete list of bloatware here: https://rootmygalaxy.net/xiaomi-bloatware-list-remove-safely-from-miui/
this list is very limited to keep working the MIUI cloud and many Xiaomi apps I like

## Alternative sources
Note that is list is proved on Xiaomi Note 7 :)

[1] https://gist.github.com/Biswa96/81fe477079fa5279f7cfd7b98d5519c7
