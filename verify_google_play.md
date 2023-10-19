Get the android_id:

```shell
adb root
adb shell 'sqlite3 /data/*/*/*/gservices.db \
    "select * from main where name = \"android_id\";"'
# output like this:
android_id|456xxxxxxxxxx827
```

Submit the number 456xxxxxxxxxx827 on this page:

[https://www.google.com/android/uncertified/](https://www.google.com/android/uncertified/)
