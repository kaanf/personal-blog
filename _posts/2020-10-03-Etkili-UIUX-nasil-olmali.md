---
layout: post
title: "Etkili bir UI/UX nasıl olmalı?"
categories: Blog
tags:
- user interface
- user experience
- design
status: publish
type: post
published: true
meta: {}
---

### 🦄 Mobil Uygulama Tasarımına Giriş

Blogtaki yazıları kendimi geliştirmek açısından da ingilizce yazmayı düşünüyordum ancak bu konuda çok fazla türkçe kaynak olmadığı için türkçe devam edeceğim. Yazının büyük bir bölümü **Smashing Magazine** & **Behance** sitelerinden referans içermektedir. En sonda yer alan referanslar bölümünden inceleyebilirsiniz.

İyi bir uygulama ile kötü bir uygulama arasındaki fark genellikle kullanıcı deneyiminin (UX) kalitesidir. İyi bir kullanıcı deneyimi, başarılı uygulamaları başarısız olanlardan ayıran şeydir. Günümüzde mobil uygulama kullanıcıları bir uygulamadan çok şey bekliyor: 

- Hızlı yükleme süresi, 

- Kullanım kolaylığı,

- Etkileşim sırasında keyif. 

Uzun bir süre boyunca gözlemlediğim kadarıyla, UX'i tasarımın sadece küçük bir yönü değil, aynı zamanda ürün stratejisinin önemli bir bileşeni olarak düşünmelisiniz.

### 🧠 Bilişsel Yük

Bilişsel psikolojide çokça kullanılan bir kavram. İnsan beyninin belli bir anda zihnine yüklenmekte olan algı miktarını ifade ediyor. İnsan beyninin aynı anda sınırlı miktarda
işlem gücü vardır ve bir uygulama, kullanıcıyla çok fazla etkileşime girdiği veya bilgi sağladığı takdirde kullanıcının uygulamayı terk etmesine neden olabilir.

### 😵 Düzensizlik

Bana göre, UX ve UI tasarımında yapılması gereken en önemli şeylerden birisi düzensizliği ve dağınıklığı kaldırmak. Dağınıklık, iyi bir tasarımın en kötü düşmanlarındandır. Yukarıda da
bahsettiğim gibi, sınırlı bir algı gücüne karşı çok fazla etkileşime geçmek, kullanıcıları kısıtlı zamanda aşırı bilgi ile yüklemek demektir. Eklenen her düğme, simge ve görüntü ekranı daha karmaşık hale getirir.

Masaüstü uygulamalarda etkisi hissedilse de mobil uygulamalarda bu durum çok daha fazla göze batıyor. Çünkü mobil cihazlarda masaüstü ve dizüstü bilgisayarlarımızda olduğu gibi geniş bir alanımız yok. Kısıtlı bir alanı verimli kullanmak zorundayız. Mobil uygulama tasarlarken, ekrandaki gereksiz olan her şeyden kurtulmak çok önemli çünkü dağınıklığı azaltmak, kavrayışı iyileştirecektir. Bu durumda **Functional Minimalism** tekniğini uygulamak, karmaşık bir kullanıcı arayüzü sorununu çözmenizde yardımcı olabilir:

- İçeriği minimumda tutmak (Kullanıcıya sadece bilmesi gereken şeyleri sunmak),

- Arayüz ögelerini minimumda tutmak.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/366208b7-5820-4dc1-b7c4-9ec12122666c/mobile-app-design-image67-opt.png "Functional Minimalism")

> 📷 **Referans:** Apple

- Kullanıcıya aynı ekranda daha fazla detay göstermek istiyorsanız, **Progressive Disclosure** tekniğini kullanabilirsiniz.

![alt text](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/4149f7df-312e-4a3b-b2ee-ace7510bfb32/mobile-app-design-image107.gif "Progressive Disclosure")

> 📷 **Referans:** [Ramotion](https://www.ramotion.com/) 

### 🔌 Arkaplan Görevleri

Tasarımınızda kullanıcının etkileşime girdiği alanları düşünün ve alternatif çözümleri araştırın. Bazı durumlarda kullanıcının daha fazla yazmasını istemek yerine önceden girilmiş veriler yeniden kullanılabilir. Android geliştirme üzerinden örnek vermek gerekirse, bir otel rezervasyon uygulamamız olsun. Kayıt esnasında kullanıcının kişisel bilgilerini alarak veritabanımızda tutalım. Kullanıcı, bir otelden rezervasyon yaptırmak istediğinde bu bilgileri tekrardan girmek yerine, veritabanımızda hali hazırda mevcut bilgiler gerekli alanları doldurmak için kullanılabilir.

### 📜 Görevleri Küçük Parçalara Bölmek

Bir görev, kullanıcı açısından tamamlanması gerekli birçok adım ve eylem içeriyorsa, bu tür görevleri birkaç alt göreve bölmek daha iyidir. Görevleri küçük parçalara bölmek mobil tasarımda oldukça önemli bir durum çünkü yukarıda da yazdığım gibi, kısıtlı bir alanımız olduğu için kullanıcıya bir seferde büyük bir karmaşa ve dağınıklık yaratmak istemeyiz. Örneğin, kayıt ya da bir ödeme sayfasında kullanıcıdan fazla bilgi istemek zorunda kaldığımız durumlarda **Progress Bar** kullanmak ekrandaki düzensizliği azaltmamıza yardımcı olur.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/e5725ec4-09a9-4757-af00-f5393dbcce3f/mobile-app-design-image54-opt.png "Progress Bar")

> 📷 Doğru kullanılan bir **Progress Bar**, özellikle kullanıcıdan çok fazla bilgi talep ettiğimizde ekrandaki düzensizliği azaltmamıza yardımcı olur. **Referans:** [Murat Mutlu](https://dribbble.com/mutlu82) 

### 📱 Tanıdık Ekranların Kullanımı

Tanıdık ekranlar, kullanıcıların gördüğü **Uygulamaya Başlarken** ve **Arama Sonuçları** gibi ekranlar, bir çok uygulamada standart haline gelen ekranlardır. Kullanıcılar bu ekranlara aşina olduğu için ek açıklama gerektirmezler. Tanıdık ekranları kullanmak, kullanıcının herhangi bir öğrenme eğrisi kullanmadan uygulamayla etkileşimde bulunmak için önceki deneyimlerini kullanmasına olanak sağlar.

Bu konu ile ilgili de yakında bir yazı paylaşacağım.

### 💹 Kullanıcıdan Alınan Bilgiyi İyileştirmek

Küçük ve mobil bir ekranda yazı yazmak her zaman en rahat deneyim değildir. Kullanıcıdan bilgi aldığımız ekranlardan en yaygını kayıt sayfasıdır ve çoğu zaman hataya meyillidir.. Bu durumu iyileştirebilecek bir kaç çözüm var:

- **Gereksiz alanları kaldırarak formları kısa tutmak.** (Uygulama, kullanıcıdan yalnızca minimum bilgi istemelidir.)

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/4d4a8a86-1d74-4fee-bdb9-fc5f1ba88c66/mobile-app-design-image57-opt.png "Formları Kısa Tutmak")

> 📷 Form tasarımında temel kurallardan bir tanesi, doldurulması gerekilen bir çok alanı olabildiğince minimize etmektir. **Referans:** Luke W.

- **Giriş alanlarını maskelemek.** Alanları maskelemek, kullanıcıların girilen metni biçimlendirmesine yardımcı olan bir tekniktir. Kullanıcı bir giriş alanına odaklandığında yarattığımız maske, girilen metni otomatik biçimlendirerek kullanıcının gerekli verilere odaklanmasına ve hataları daha kolay farketmesine olanak sağlar.

![alt text](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/fa12c37f-8350-4a8f-a1d2-d05530d7415c/mobile-app-design-image105.gif "Mask of User Input")

> 📷 **Referans:** [Josh Morony](https://www.joshmorony.com/wp-content/uploads/2017/01/input-mask.gif)

- **Otomatik doldurma gibi akıllı özellikleri kullanmak.** Örneğin, bir adres alanını doldurmak genellikle herhangi bir formun en sorunlu kısmıdır. PAAF (Place Autocomplete Address Form) gibi araçların kullanılması(kullanıcının tam konumuna doğru öneriler sağlamak için coğrafi konumu kullanır.), kullanıcıların adreslerini normal bir giriş alanında olması gerekenden daha az hatayla girmelerini sağlar.

- **Giriş alanlarını doğrulamak.** Çoğu durumda verileri gönderdikten sonra geri dönüp hataları düzeltmek bir zaman kaybıdır. Mümkün mertebe kullanıcıların hatalarını düzeltebilmesi için giriş alanlarını gerçek zamanlı olarak kontrol edin. Örneğin, Android'de EditText'e girilen bir yazıyı **TextWatcher** kullanarak takip edebilirsiniz.

![alt text](https://cdn.baymard.com/data-broker/graphic-548-df365441c389949fc9dbf39ed204de5f.jpg "Input Validation")

> 📷 Örnek bir giriş alanı doğrulaması. **Referans:** [Baymard](https://cdn.baymard.com/data-broker/graphic-548-df365441c389949fc9dbf39ed204de5f.jpg)

- **Farklı giriş alanları için klavyeyi özelleştirmek.** Bu durumu bir çok uygulama göz ardı ediyor ancak en önemli maddelerden bir tanesi. Kullanıcıdan telefon numarası isterken sayısal bir klavyenin görüntülenmesi veya e-posta adresi isterken klavyede @ işaretinin bulunması, kullanıcı açısından oldukça rahatlatıcı ve hızlı bir deneyim sağlar.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/11aa6d9d-8151-41c5-afb6-e51a2fd7bc66/mobile-app-design-image95-opt.png "Keyboard Specialization")

> 📷 Farklı giriş alanları için klavyeyi özelleştirmek. **Referans:** [ThinkWithGoogle](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/11aa6d9d-8151-41c5-afb6-e51a2fd7bc66/mobile-app-design-image95-opt.png)

### ❗ Önemli Unsuru Vurgulamak

Ekrandaki en önemli unsur görsel açıdan en büyük ağırlığa sahip olmalıdır. Bu ne demek? Büyük parçalar küçük parçalara oranla daha fazla dikkat çeker ve kullanıcı için daha önemli görünür. Ekranda odaklamak istediğimiz önemli bir unsur varsa, bu unsurun yazı tipi kalınlığı, boyutu, rengi ve görseliyle en büyük ağırlığa sahip olmasını sağlamalıyız.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/881fb3c5-784e-412b-bf1d-aece0403ca69/mobile-app-design-image81-opt.jpg " ")

> 📷 **Request Lyft** butonu diğer parçalara oranla kullanıcının dikkatini daha fazla çekecektir. **Referans:** [Smashing Magazine](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/881fb3c5-784e-412b-bf1d-aece0403ca69/mobile-app-design-image81-opt.jpg)


### ⚙️ Tasarımı Tutarlı Hale Getirmek

Tutarlılık, tasarımın en temel ilkelerinden bir tanesidir. Web ve mobil platformlarında, uygulama genelinde tutarlı bir görünüm sağlamak kafa karışıklığının ortadan kalkmasına ve kullanıcının daha sağlıklı bir etkileşim halinde olmasına olanak sağlar. Mobil uygulama ile ilgili tutarlılıktan bahsedecek olursak:

- **Visual Consistency:** Yazı biçimleri, butonlar ve alanların uygulama genelinde tutarlı olması.

- **Functional Consistency:** Etkileşimli ögelerin uygulamanın genelinde tutarlı bir şekilde çalışması.

- **External Consistency:** Tasarımın birden çok üründe tutarlı olması.

Tutarlılık konusunda problemler yaşıyorsanız, bu problemleri çözmek için bazı çözümler var:

- **Platform kurallarına uymak:** Her mobil işletim sisteminin arayüz tasarımı için standart yönergeleri vardır. IOS için `Apple’s Human Interface Guidelines` ve Android için `Google’s Material Design Guidelines`. Platformlar için tasarım yaparken, kaliteyi yükseltmek için bu yönergeleri izlemenizde fayda var. Bu yönergelere uymanın en büyük avantajı, kullanıcılar kullandıkları işletim sisteminin tasarım kalıplarına aşina oldukları için uygulamanıza adapte olmakta zorlanmayacak olmaları.

- **Platformlar arasında kullanıcı arayüzü ögelerini taklit etmemek:** Android platformu üzerinden geliştirme yapıyorsanız Google materyallerini, IOS için yapıyorsanız Apple materyallerini kullanın. Simgeler, işlevsel ögeler(giriş alanları, onay kutuları, vb.) ve yazı biçimleri kullandığınız platformu yansıtmalıdır. İnsanların uygulamanıza güvenmesi ve bağ kurabilmesi için mümkün olduğunca bu maddeye dikkat edin.

_İkinci bölümü yakın zamanda paylaşacağım._

> **Referanslar:**\
[ekşisözlük](https://www.eksisozluk.com)\
[Smashing Magazine](https://www.smashingmagazine.com/2018/02/comprehensive-guide-to-mobile-app-design/)\
[Behance](https://www.behance.net)\
[Hotjar](https://www.hotjar.com)