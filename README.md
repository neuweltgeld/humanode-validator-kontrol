Humanode kurulum sonrası validatör kontrolü [^1]

Humanode Launcher kullanarak tamamladınız, bioauth 168 saatlik süreç başladı (auth süresi 7 gün, sonrasında tekrar auth yapacaksınız). Validatörüm çalışıyor mu acaba diye merak ediyorsanız bu yolları deneyebilirsiniz.


Aşağıdaki linke tıklayın ve validatör isminizin listede olup olmadığını kontrol edin.

https://telemetry.humanode.io/#list/0x54f8483c71e0bd9fa1b1f654bcdd91b35df07a08ecc4e859b465926ceef91a49

Daha sonra aşağıdaki linke girin ve **"selected state query"** sekmesinden **bioauth** seçip **activeAuthentications (): Vec <PalletBioauthAuthentication>** seçin ve sağdaki **+** butonuna basın. Böylece aktif listeyi göreceksiniz. Cüzdan adresinizi sayfada aratıp bulabilirsiniz.
  
https://polkadot.js.org/apps/?rpc=wss://explorer-rpc-ws.testnet3.stages.humanode.io#/chainstate
  
Aynı sayfada **bioauth** seçtiğimiz yerden tekrar **session** seçip **validators ()** seçiyoruz ve **+** tuşuna basıyoruz. Buradan aktif validatör listesini görüyoruz. Yine adresinizi aratıp bulabilirsiniz.

Eğer adresinizi listede göremezseniz ortalama **10-20 dk** sonra tekrar kontrol edin.

- [x] Bu 3 şekilde de kendi adresinizi görüyorsanız tebrikler. Her şey yolunda demektir.
Tam tersi, validatör isminizi ya da cüzdanınızı göremiyorsanız kurulum aşamasını kontrol edin.

> Node kurulum ve Türkçe destek grupları için @github/ruesandora teşekkürler.


[^1]: *Orjinali Humanode Discord kanalında @Dmitriy Wayne nickli kullanıcıya aittir.*
