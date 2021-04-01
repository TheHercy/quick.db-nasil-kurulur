# Windows'a/VDS'e quick.db modülü nasıl kurulur ?

## Önemli
* [Node.JS'in](https://nodejs.org/en/) makinenizde yüklü olduğundan emin olun.

## Kurulum aşamalar 

1) Makinenize öncelikler [Microsoft .NET Framework 4.5.1](https://www.microsoft.com/en-us/download/details.aspx?id=40773) yüklemelisiniz.
2) Eğer ki bu program zaten yüklü yazıyorsa kurulumu kapatabilirsiniz.
3) PowerShell'i yönetici olarak çalıştırın ve şu kodu yazıp enterlayın `npm install --global windows-build-tools --vs2015` Bu işlem uzun sürebilir. Bittiğinde alt satıra geçer zaten.
4) Sorunsuz bir şekilde indiyse sırada CMD'yi yönetici olarak çalıştırıp şu kodu yazıyoruz. `npm init -y` işlem bittiğinde ise `npm i quick.db` bu kodu yazıyoruz.

  🎉 Artık bilgisayarımıza quick.db inmiş oldu 🎉
