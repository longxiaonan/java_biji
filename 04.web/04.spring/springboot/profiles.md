假设你不希望在修改代码时意外地对生产数据库进行任何操作，因此将默认配置文件设为 dev 是很有意义的。然后，在服务器上，你可以通过提供 `-Dspring.profiles.active=prod` 参数给 JVM 来手动覆盖配置文件。