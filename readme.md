**"Sealed Classes" yani "Mühürlü Sınıflar"**

* Java 16 ile birlikte gelen bu özellik, bir sınıfın hangi diğer sınıflar tarafından genişletilebileceğini veya hangi alt sınıfların oluşturulabileceğini sınırlamak için kullanılır.

Example:

    public sealed class Shape permits Circle, Square {...}
