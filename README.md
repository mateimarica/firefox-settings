My custom firefox settings. Built off the user.js of [Betterfox](https://github.com/yokoffing/Betterfox).

To install these settings, find your Firefox profile directory. It's usually in

```
C:\Users\<User>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXX.default-release
```

Open up a command prompt in that directory and do:
```console
git init
git remote add origin git@github.com:mateimarica/firefox-settings.git
git pull origin master
```
