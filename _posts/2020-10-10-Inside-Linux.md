---
layout: post
title: "Linux'ta Kernel & Shell'in kısa bir özeti"
categories: Blog
tags:
- linux
status: publish
type: post
published: true
meta: {}
---

### ⚫ Kernel (Çekirdek)

- Linux çekirdeği, -_diğer adıyla **kernel**_- bir Linux sisteminde çalışan en alt seviye yazılımdır. Linux sisteminin özü diyebiliriz. Sistemin başlangıcında **(boot esnasında)** yüklenir. 

- Sistemin kaynaklarını yönetmekle sorumludur ve kullanıcılara uyumlu ve stabil bir sistem sunar. Device management, process scheduling vs. gibi kullanıcı uygulamalarına hizmet sağlar.

- Kernel tarafından gerçekleştirilen görevlerden bazıları;

  - **I/O Management** dediğimiz, giriş-çıkış işlemlerinin yürütülmesi. Örneğin klavye, fare, ekran gibi donanımların ihtiyaçlarını karşılayarak, başarıyla çalışmasını sağlamak,

  - **Process Management** dediğimiz, işletim sisteminde oluşan taleplerin yönetilmesi,

  - Kullanıcının işini verimli bir şekilde gerçekleştirmesi için, CPU tarafından yapılan işin planlanması,

  - Erişim izinlerini zorunlu kılma,

  - **Shell** üzerinden girilen talimatları uygulama.

### 🐚 Shell (Kabuk)

- **Shell** bir komut yorumlayıcısıdır. 

- Yazılan komutları alır ve işlem için **kernel'e** aktarır. Daha sonrasında işlemin sonuçlarını ekranızda görüntüler. 

- Farklı kullanıcılar farklı kabuklar kullanabilir. Başlangıçta sistem, size değiştirilebilen veya geçersiz kılınabilen varsayılan bir kabuk sağlayacaktır. 

- En çok kullanılan kabuklar;

  - Bourne shell (sh),

  - C shell (csh),

  - Korn shell (ksh),

  - TC shell (tcsh),

  - Bourne Again shell (bash).

- Her kabuk kendi programlama diline sahiptir. **Shell Scripts** dediğimiz komut dosyaları, görevleri gerçekleştirmek için kullanılır.
