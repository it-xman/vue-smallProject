# 简单商品管理功能

## 目的：练习Vue 的使用，实现增删査的功能

### 1. 获取数据库的数据，将其渲染到页面显示

- 设置一个获取数据库内容的方法  getBrandsList
- 设置一个计算成员 computed
  - 进行关键字查询的时候，通过查找输入的关键字是否含有传入的filter的参数对象的name属性值，v-for的时候，遍历这个计算成员的成员，就可以实现数据双向绑定，查询的时候输入的关键字，会影响filter筛选，filter筛选会将筛选完毕的结果返回，在容器里再遍历筛选出来的结果进行渲染，就达成了筛选的功能

### 2. 可以搜索关键字查找到相应的数据

### 3. 使用axios拦截器，在发送数据请求的时候页面给出提示，增加友好度

### 4. 可以增加数据，删除数据，通过axios发送数据

### 5. 使用axios的其他功能，axios返回的是Promise对象

### 6. 练习Promise对象的使用方法

### 7. 在拦截器里改变axios请求的基地址(baseURL)

### 8. 使用过滤器，更改将数据进行制定修改后展示