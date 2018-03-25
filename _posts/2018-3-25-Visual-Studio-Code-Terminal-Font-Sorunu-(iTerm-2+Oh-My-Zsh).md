---
layout: post
title: Visual Studio Code Terminal Font Sorunu (iTerm 2 + Oh My Zsh)
---


Atom'dan VS Code'a geçtiğiö bu günlerde bazı sıkıntılar yaşıyorum. Aslında VS Code'a geçiş yapmamın ana sebeplerinden biri de içinden terminal'e erişebiliyor olmak. Terminalde iTerm 2 + Oh My Zsh kullanıyorum. Kullandığım temada da Meslo isimli font VS Code'un terminal kısmında sıkıntı çıkartıyordu.

![Düzenlenmiş Hali](http://img508.yukle.tc/images/4735Screenshot_2018-03-25_230836.jpg)

![Sorunlu Fontlu Ekran Görüntüsü](http://img508.yukle.tc/images/7809Screenshot_2018-03-25_230230.jpg)

Bu sorunu çözmek için ise VS Code ayarlar dosyasınıza terminalde hangi fontu söylemeniz gerekiyor. Ben Meslo isimli fontu kullandığım için Font Book'da olan adını ayarlar dosyasına kaydettim.

    "terminal.integrated.fontFamily": "Meslo LG M for Powerline"

Eğer farklı bir kullanıyorsanız kesinlikle Font Book'daki adını girmelisiniz. Eğer sıkıntı yaşıyorsanız kullanıdınız temanın GitHub sayfasında VS Code config başlığı altında yer vermiş olabilirler.

İyi kodlamalar!