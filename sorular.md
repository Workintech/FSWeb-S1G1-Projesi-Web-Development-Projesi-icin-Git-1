# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

    Dağıtılmış bir açık kaynak sürüm kontrol sistemidir.Kaynak kodun takibini yapmak ve değişiklilikleri yönetmek , işbirliği yapmak için kulalnılır.

2. Git ile GitHub arasında ne fark var?

    Github , bulut tabanlı bir git barındırma hizmeti sunan kar amaçlı bir şirkettir.
    Git ile github bulut tabanlı barındırma hizmetine kendi kaynak kodlarımızı yükleyip gerektiği zaman lokale çekip gerektiği zaman ise işbirliği için kullanırız.

3. Neden bir branch oluşturuyoruz?

    Branch çalışan bir kaynak kodun tamamını kopyalayarak  üzerinde update'ler yapmak için başka bir yere taşımasıdır.Branch ile ayrıca geliştirilen kodun testi de yapılabilir.
    Hata düzeltmeleri yapılabilir.

4. Pull Request'in amacı nedir?

    Bir kod değişikliliğinin ana kod tabanına dahil olmadan önce diğer geliştiricilere tarafından incelenip onaylanmasını sağlamamız gerekir. Bunun için Pull request kullanırız.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

    Bir branchdan diğer brancha geçmek için kullandıgımız komut git checkout -b "Yazılacak isimdir."

    Git checkout main yazarak ana brancha geçebiliriz. Tabi eğer isim-soyisim brachi ile ana branchi birleştireceksek önce commit yapıp push yapıp sonra merge komuta ile berabermain ile birleştiriyoruz.



6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

    Git fetch , remote repo'dan güncellemeleri alarak yerel depoya getirir ama yerel brachlar üzerinde bir değişiliklilik yapmaz.

    git merge , Ana kaynak kodu ile yeni üzerinde çalıştığımız brach'in birleştirilmesini sağlar.

    git pull , repomuzda olan projemizi lokale çekmemize sağlar.

7. Merge conflict nedir?

    Git' de birleştirme yani merge esnasında ortaya çıkan patlamalardır çakışmalardır , iki ve daha fazla yapılan değişikliliklerin çelişkili olduğu durumlarda meydana gelir.


8. Merge conflict'i nasıl çözeriz?

    Conflictleri belirleyip , onları düzenlememiz gerekir.

    Düzenlemelerden sonra ise yapılan değişiklilikleri commit ederek merge işlemini tamamlamamız gerekir. Tabi bu çözülen değişiklilikleri hedef branch ile birleştirdiğimizden emin olmamız gerekir.