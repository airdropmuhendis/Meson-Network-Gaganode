<h1 align="center"> Meson Network Gaganode Kurulumu

## Meson Network, geleneksel emek tabanlı satış modellerini değiştirmek için kendi oluşturduğu  bir blockchain protokol modeli kullanarak, uzun kuyruklu kullanıcıların boşta kalan bant genişliğini düşük bir maliyetle birleştirip paraya dönüştürerek, Web3'te verimli bir bant genişliği pazarı oluşturmaya khedefliyor.

## GaGaNode, kullanıcıların boştaki bant genişliği kaynaklarını bağımsız olarak yönetmelerine yardımcı olmak için geliştirilmiştir. Kullanıcılar, genel ağ IP'si olmadan evde Idle Electronics aracılığıyla Web3 ağına katılabilir. GaGaNode, yeni madencilik ekipmanlarına yapılan yatırımı azaltmaya yönelik herhangi bir cihazdaki banttan yararlanarak geliştirilen bir çalışmadır.

 ## Video [Linki](https://youtu.be/Gh8dX0xfA0g)
![image](https://docs.gaganode.com/assets/gaga-system.89f4f46b.png)

## Kayıt [Linki](https://dashboard.gaganode.com/register?referral_code=liewshrrtr)

## Sunucuyu nerden nasıl alacağınızı bilmiyorsanız node eğitim serimizi izleyebilirsiniz. [Node Eğitim Serisi](https://www.youtube.com/playlist?list=PLKxGUfdcj7MVXls2OvTpwx6CnpVJN685w)

sistem gereksinimleri çok önemli değil çok düşük sistemlerede kurabilirsiniz.

Hazırlık
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt-get install curl tar ca-certificates -y 
```
İndirme
```
curl -o app-linux-amd64.tar.gz https://assets.coreservice.io/public/package/22/app/1.0.3/app-1_0_3.tar.gz && tar -zxf app-linux-amd64.tar.gz && rm -f app-linux-amd64.tar.gz && cd ./app-linux-amd64 && sudo ./app service install
```
```
sudo ./app service start
```
Kontrol : eğer status Downloaded veya Running ise devam edebilirsin. eğer To Download ise biraz bekle bu komutu tekrar gir hala devam ediyorsa stop komutunu kullanıp tekrar start komutunu çalıştır. Ek 1 de anlattım.
```
./app status
```
Token set Çalıştırma: Token adresini yaz denen kısmı gaganodeden aldığınız token adresiyle değiştirin.
```
sudo ./apps/gaganode/gaganode config set --token= token adresini yaz
```
```
./app restart
```
## Ek 1: eğer kontrol adımında status durumu To Download olarak gözüküyor ve değişmiyorsa 
1-Önce servisi durdur.
``` 
sudo ./app service stop
```
2-Daha sonra tekrar çalıştırıp kontrol et eğer düzeldiyse aynı işlemlere devam et.
```
sudo ./app service stop
```
