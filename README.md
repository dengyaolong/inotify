# inotify
exec command when file is changed

# Install
```
curl  https://raw.githubusercontent.com/dengyaolong/inotify/master/inotify > ~/bin/inotify
```

# Usage
```
inotify watch_root your_cmd
```

# Example
In your Application dir root, run npm test if any file modified.
```
inotify . npm test
```
