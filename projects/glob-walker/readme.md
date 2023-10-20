Title
=====


```glob
~/home
./here
../relatively
path/

```

### Search Regex

```glob
(?i)ygg.{json, json5, toml}
(?i)Yggdrasil.{json, json5, toml}
[yY][cC]{2}
```

### Search Group(Relative paths)

```glob
~/home

./here
../relatively


*.json
**.json


path/
path/**
**path/**
this-path/a.text

/path/
**/path/**

```

### Search Coverage

```glob
a/
!a/b
a/b/c
```
