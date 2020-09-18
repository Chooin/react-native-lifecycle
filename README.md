# React Native Lifecycle

> 类似微信小程序的生命周期

### API

- useLoad
- useShow
- useHide
- useUnload
- useResize

``` js
import {
  useLoad,
  useShow,
  useHide,
  useUnload,
  useResize,
} from 'react-native-composition';

// ? 页面创建时执行
useLoad(() => {})

// ? 页面出现在前台时执行
useShow(() => {})

// ? 页面从前台变为后台时执行
useHide(() => {})

// ? 页面销毁时执行
useHide(() => {})

// ? 页面尺寸变化时执行
useResize(() => {})
```

