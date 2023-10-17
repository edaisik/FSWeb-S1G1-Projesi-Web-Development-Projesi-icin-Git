# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   - Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
   - Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir platformdur.

3. Neden bir branch oluşturuyoruz?
   - Branch oluşturmak çalıştığımız projenin farklı versiyonlarına erişmemizi sağlar. Projemize bir yenilik eklemek istediğimizde projenin çalışır halini kaydedip, yeni branch üzerinde çalışabiliriz. Böylece projenin eski halini korumuş oluruz. Her yeni versiyon için farklı branchler açabiliriz. Versiyonları, yaptığımız geliştirmeleri ana koda müdahale etmeden daha kolay takip etmiş oluruz. 

4. Pull Request'in amacı nedir?
   - Yeni bir branch'te yaptığımız işi ana branch'e erişimi olan, merge yapabilme yetkisi olan kişiye pull requeste yollarız. Proje üzerinde değişiklik yaptığımızı göstermiş oluruz. Proje sahibi bu değişiklikleri görebilir. Değişiklikler, eklemeler ve çıkarmalar yeşil ve kırmızı olarak gösterilir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   - git checkout 'branch name'

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   - git fetch : remote-repo‘daki tüm commit ve dosyaları çeker.
   - git merge : başka bir branch'deki değişiklikleri üzerinde çalıştığımız kendi branch'imize entegre eder.
   - git pull : local bir branchi remote versiyona güncellemek için kullanılır. Aynı zamanda diğer remote brachleri de update etmek için de kullanılır. Fetch ve merge komutlarının birleşimidir.

7. Merge conflict nedir?
   - İki kişi aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olur.

8. Merge conflict'i nasıl çözeriz?
   - Bir developer bu oluşan conflict'in her ikisine de bakar hangisini isterse onu yayına alabilir, ikisini de almayabilir veya her iki tarafın da düzeltmelerini isteyebilir. Kodun işleyişi hakkında bir kanıya varılıp buna göre kodu düzenlemek gerekir.
