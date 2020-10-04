---
layout: post
title: "Kullanıcının İhtiyaçlarını Anlamak"
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

### ⭐ Başlamadan Önce

Bu makale `3 Ekim 2020` tarihinde paylaştığım [Etkili bir UI/UX nasıl olmalı?](https://kaanf.com/blog/Etkili-UIUX-nasil-olmali) yazısının devamıdır. Yazının büyük bir bölümü **Smashing Magazine** & **Behance** sitelerinden referans içermektedir. En sonda yer alan referanslar bölümünden inceleyebilirsiniz.

### 📍 Tahmin Edilebilir Etkileşimli Ögelerin Tasarlanması

Tahmin edilebilirlik, kullanıcı deneyiminin temel ilkelerinden bir tanesidir. İşler kullanıcının tahmin ettiği şekilde yürüdüğünde, uygulama üzerinde daha güçlü bir kontrol duygusu hissederler. Örneğin, çoğu zaman masaüstünde bir ögenin etkileşimi olup olmadığını imleci ögenin üzerine getirdiğinizde anlayabilirsiniz. Muhtemelen ögeye uygulanan bir hover efekti vardır. Ancak mobil uygulamalar da, masaüstünün aksine kullanıcılar etkileşimi yalnızca dokunarak kontrol edebilir. Bu nedenle, düğmeler ve diğer etkileşimli ögelerin buna uygun tasarlanması gerekmektedir. Kullanıcı bir ögeyi düğme olarak nasıl algılar? Nesnenin görünüşü, kullanıcılara onu nasıl kullanacaklarını anlatır. Butonlara benzeyen ancak etkileşimi olmayan görseller, çoğu zaman kullanıcının kafasını karıştırır.

### ◀️ Geri Butonu

Uygulamalardaki belki de en önemli butonlardan birisi olan geri butonu, yanlış çalıştığı takdirde kullanıcılar için birçok soruna neden olabilir. Çok adımlı bir süreçte geri butonunun yanlış çalışması, kullanıcıyı önceki ekran yerine ana ekrana geri götürür. İyi bir tasarım, kullanıcıların geri dönüp düzeltmeler yapmasını kolaylaştırır.

### ⚠️ Hata Mesajları

Hata yapmak insani bir durum. Çoğu zaman, kullanıcılar uygulamalarla etkileşim içerisinde olduklarında hatalar meydana gelebilir. Bu hatalar bazen kullanıcı kaynaklı, bazen de uygulama kaynaklı olabilir. Kaynağı ne olursa olsun, bu hataların kullanıcıya doğru ve anlamlı bir şekilde iletilmesi gerekir. Anlamsız hata mesajları kullanıcıları hayal kırıklığına uğratabilir ve uygulamanızı terk etmesine sebep olabilir.

Örnek vermek gerekirse, Spotify hata mesajlarında başarısız bir örnek. Kullanıcılara anlamlı hata mesajları sunmaz ve _Bu konuda ne yapabilirim?_ sorusunun cevabını bulmalarına yardımcı olmaz.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/92a405e7-77ae-4111-b235-1d6a9330cb0d/mobile-app-design-image199-opt.png " ")

> 📷 [Spotify](https://apps.apple.com/us/app/spotify-music/id324684580)'ın hata ekranında sadece "Bir hata oluştu." yazar ve sorunun nasıl çözüleceğine dair yapıcı bir tavsiyede bulunmaz.

Çoğu tasarımcının genel hatası, her kullanıcının teknoloji konusunda çok bilgili olduğunu düşünmesidir. Kullanıcılara her zaman yanlışlığın nerede olduğunu söyleyin. Anlamlı hata mesajlarının şu maddeleri içermesi gerekir:

- Ne yanlış gitti ve neden?

- Kullanıcı bu hatayı nasıl düzeltebilir?

### ⚫ Erişilebilir Arayüz Tasarımı

Erişilebilir tasarım görme kaybı, işitme kaybı ve diğer engelleri olan kullanıcıların deneyimini iyileştirmek için gerekli bir adımdır.

### 💥 Renk Körlüğünün Farkında Olmak

Küresel nüfusun **%4,5**'i renk körü, **%4**'ü az görmekten muzdarip ve **%0,6**'sı kördür. Çoğu tasarımcı bu tür sorunlarla karşılaşmadığı için üretilen tasarımların bu kullanıcı grubunu da içerisine aldığını unuturlar.

Örneğin, kayıt formlarındaki başarı ve hata mesajları genellikle sırasıyla yeşil ve kırmızı renktedir. Ancak yeşil ve kırmızı, görme eksikliği olan kullanıcıların en çok etkilendikleri renklerdendir. Bir form'u doldururken hata mesajınız **Kırmızı ile işaretlenmiş alanların doldurulması zorunludur.** ise, bu durum renk körlüğü yaşayan kullanıcılar için oldukça sinir bozucu bir deneyim olabilir.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/c4996a88-58c4-4eaf-96e4-7ea6a3e54698/mobile-app-design-image94-opt.png " ")

> 📷 Renk körlüğü yaşayan kullanıcılar kırmızı ile vurgulanan yerleri ayırt edemez.

[W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html)'nin yönergelerinde de belirtildiği gibi, bir eylemi belirtmenin, bir yanıtı harekete geçirmenin veya görsel bir ögeyi ayırt etmenin tek yolu olarak renkler kullanılmamalıdır. Kullanıcıların arayüz ile iletişimini iyileştirmek için diğer görsel göstergeleri de kullanmak önemlidir. 

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/d8316f62-cea1-4508-88ff-e66afb56dd50/mobile-app-design-image104-opt.png " ")

> 📷 Başarı ve hata mesajlarında simgelerin ve ikonların kullanılması, renk körlüğü yaşayan kullanıcıya daha iyi bir deneyim sağlar.

### 🎈 İsteğe Bağlı Animasyonlar

Her ne kadar küçük bir şey gibi gözükse de, animasyonları tercih etmeyen kullanıcılar genelde işletim sistemi ayarlarında efektleri kapatırlar. Erişilebilirlik tercihlerinde **Animasyonları Kapat** seçeneğinin olması ve işaretli olduğu takdirde uygulamanızın animasyonları kapatması gerekmektedir.

### 📱 Navigasyon Menüsünü Basitleştirmek

Kullanıcıların sayfalar arasında rahatça gezinmesine yardımcı olmak her uygulamanın dikkat etmesi gereken bir faktördür. Kullanıcılar navigasyon menüsünü kullanamazsa, uygulamanın sahip olduğu harika özelliklerin ve ilgi çekici içeriklerin hiçbir anlamı olmayacaktır. Ayrıca kullanıcılar, sayfaların arasında nasıl gezineceğine çok fazla zaman ve çaba harcıyorsa, büyük olasılıkla kullanıcılar uygulamayı terkedecektir. Kullanıcı uygulamayı sezgisel olarak keşfedebilmeli ve navigasyon menüsünü kullanabilmelidir.

### 📱 Standart Navigasyon Ögelerinin Kullanılması

Android için **Navigation Drawer** ve IOS için **Tab Bar** gibi standart navigasyon ögelerini kullanmak her zaman daha iyidir. Kullanıcıların çoğu her iki navigasyon menüsüne de aşinadır ve uygulamanızda nasıl gezineceğini önceki deneyimlerinden bilir.

![alt text](https://res.cloudinary.com/indysigner/image/fetch/f_auto,q_auto/w_2000/https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/4ead9319-1144-4e00-975c-64799016c692/mobile-app-design-image100-opt.png " ")

> 📷 Side Drawer in Android. **Referans:** Material Design.

![alt text](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/8a4f456f-1ea2-4c22-9713-e2f70c5d0b09/mobile-app-design-image63.gif " ")

> 📷 Tab Bar in IOS. **Referans:** [Ramotion](https://www.ramotion.com/)

### 📱 Navigasyon Ögesini Tutarlı Kullanmak

Uygulamanız için kullanacağınız navigasyon menüsünü seçtiğinizde, bunu uygulama içerisinde tutarlı bir şekilde kullanın. Uygulamanızın bir bölümünde **Tab Bar**, başka bir bölümünde **Side Drawer** olmamalıdır.

_Üçüncü bölümü yakın zamanda paylaşacağım._

> **Referanslar:**\
[ekşisözlük](https://www.eksisozluk.com)\
[Smashing Magazine](https://www.smashingmagazine.com/2018/02/comprehensive-guide-to-mobile-app-design/)\
[Behance](https://www.behance.net)\
[Hotjar](https://www.hotjar.com)

