
* goods数据结构设计: (流行/新款/精选)

```
goods: {
  'pop': {page: 5, list: [150]},
  'news': {page: 2, list: [60]},
  'sell': {page: 1, list: [30]}
}
```

* ref如果是绑定在组件中的, 那么通过**this.$refs.refname**获取到的是一个组件对象.

* ref如果是绑定在普通的元素中, 那么通过**this.$refs.refname**获取到的是一个元素对象.

* vh -> viewport height

* 在我们需要监听一个组件的原生事件时, 必须给对应的事件加上.native修饰符, 才能进行监听.

