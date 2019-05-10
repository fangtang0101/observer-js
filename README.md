# observer-js
observer in js  use decorator

监听 浏览器 的 存储，一定存储右变化，便 发出通知，

使用 js 装饰器 知识点

用法：

```
import Observer from './observer'

    Observer.addObservers('webappConfig',(res) => {
      self.getYearsTest();
      self.getPowerBy();
    })
 ```


