# Kolo的UDF功能 <!-- {docsify-ignore-all} -->
- Kolo内置常用UDF
- Kolo支持使用其他语言动态扩展UDF
  - 支持语言：Scala/Python/Java 的自定义UDF，
  - 动态扩展：无需打包重启应用，只需要在上下文中使用 Kolo 语法注册 UDF，即可使用

当然，我们也支持在启动时注册自定义 UDF 到 Kolo 中
