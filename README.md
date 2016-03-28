# lazyload
lazyload延迟加载

## 引入lazyload.min.js插件

```js
 $(function(){
        $("img.lazy").show().lazyload();
        $("img.lazy").lazyload({
            effect: "fadeIn",
            threshold :400
            // skip_invisible : true
            // skip_invisible : false
            // failure_limit : 10
          });
    });
```
