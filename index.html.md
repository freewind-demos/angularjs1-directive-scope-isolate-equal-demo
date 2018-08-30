由于是双向绑定，所以

```
<my-directive user-name="userName"></my-directive>
```

中的`user-name="userName"`，不能写成一个表达式`user-name="{{ userName }}"`，只能是某一个变量名。


