由于是双向绑定，所以

```
<my-directive user-info="userInfo"></my-directive>
```

中的`user-info="userInfo"`，不能写成一个表达式`user-info="{{ userInfo }}"`，只能是某一个变量名。


