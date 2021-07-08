# flutter 各种疑难杂症
**Flutter 升级2.x SDK 再降级导致iOS平台 找不到Flutter.h解决方案**

```
essages.m:4:9: fatal error: ‘Flutter/Flutter.h’ file not found
    #import <Flutter/Flutter.h>
            ^~~~~~~~~~~~~~~~~~~
    1 error generated.
    In file included from
```

1. Remove iOS_Flutter_Flutter.podspec: rm iOS_Flutter_Flutter.podspec
2. flutter clean
3. Run your app again.
