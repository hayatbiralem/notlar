# Hızlı Web Siteleri Kodlamak

Optimizasyon çok önemli bir husus. Optimizasyon eksikliği, küçük web siteleri üstünde çalışıldığında pek fark edilemeyebilir ama büyük bir web sitesi üzerinde çalışıyorsanız, bolca img, css ve js kullanıyorsanız, kısa sürede optimizasyonun ne kadar hayati olduğunu fark edersiniz.

Aklıma gelenleri not etmeye, not ettiklerim üzerinde çalışmaya, tecrübelerimi de anlamlandırmaya çalışacağım.

---

## 2015-06-03

### Önce CSS ve HTML

Bir projenin front-end kodlamasını yaparken, _JavaScript kullanmadan_ tüm tasarımı sadece CSS ve HTML kullanarak kodlamak, sitenin performansını önemli ölçüde arttırmamıza olanak sağlayacaktır.

Şöyle ki;

Sitenizin (JavaScript, vb. kullanarak) fonksiyonellik kazanmadan da olması gerektiği gibi görünmesini sağlarsanız, diğer tüm CSS ve JS dosyalarınızın, (require.js, yepnope.js, vb. kullanarak) sayfa yüklendikten sonra çağırılmasını sağlayabilirsiniz. Bu sadede web sitenizin hem masaüstü hem de mobil cihazlarda mümkün olduğunca hızlı bir şekilde açılmasına yardımcı olursunuz.

### CSS Framework kullanmamak daha doğru olabilir

Front-End kodlamaya ilk başladığınızda bu frameworkler sizin işin mantığını anlamanızda müthiş yardımcı olurlar. Özel tasarım yapılmayan, işleve öncelik verilmiş projelerde, bu tarz araçlar size hızlı ve tutarlı kodlama yapma olnağı da sağlar. Ancak özel tasarımlı ve büyük bir proje geliştirirken, bu tarz bir framework kullanmak yerine basit bir `reset.css` kullanarak işe başlamak daha doğru bir karar olabilir. Yadığınız toplam CSS ne kadar küçük olursa, o kadar iyi.

CSS Frameworklerini her zamanb yakında takip edin hatta mümkünse katkıda bulunun. Sadece ne zaman kullanıp, ne zaman kullanmayacağınızı bilecek kadar konuya hakim olun.

