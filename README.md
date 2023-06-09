# Proje Takip Sistemi

Bu repo, .NET 5,Entity Framework, C# ve MSSQL kullanılarak geliştirilen bir Proje Takip Sistemi'ni içermektedir. Bu sistem, kullanıcıların projeleri eklemesini, düzenlemesini, diğer kullanıcılara atamasını sağlamakla birlikte personel ekleme ve çıkarma işlemlerini de desteklemektedir.

## Özellikler

- Kullanıcılar proje ekleyebilir, düzenleyebilir ve silebilir.
- Kullanıcılar diğer kullanıcılara projeler atayabilir.
- Personel ekleme ve çıkarma işlemleri.
- Proje detaylarını görüntüleme ve güncelleme imkanı.


## Kurulum

1. Bu repo'yu klonlayın.
2. MSSQL veri tabanında bir veritabanı oluşturun.
3. webconfig dosyasında veritabanı bağlantı ayarlarınızı yapın.
4. Proje Takip Sistemi uygulamasını derleyin ve çalıştırın.

## Kullanım

1. Uygulamayı çalıştırdıktan sonra tarayıcınızda `http://localhost:5000` adresine gidin.
2. Kullanıcı girişi yapmadan projeyi kullanabilirsiniz.
3. Personel eklemek veya çıkarmak için yönetici hesabıyla giriş yapın.
4. Personel eklemek için ilgili sayfayı kullanın ve gerekli bilgileri girin.
5. Personel çıkarmak için personel listesinden ilgili personelin üzerine gelin ve çıkarma işlemini gerçekleştirin.

> Not: Bu örnek projede kullanıcı girişi ve yetkilendirme sistemi uygulanmamıştır. İhtiyaçlarınıza göre kullanıcı girişi ve yetkilendirme sistemi ekleyebilirsiniz.
![Proje Takip](https://github.com/Snmzgrkn/TakipProje/blob/master/Ekran%20Al%C4%B1nt%C4%B1s%C4%B1.PNG)
![Proje Takip](https://github.com/Snmzgrkn/TakipProje/blob/master/Ekran%20Al%C4%B1nt%C4%B1s%C4%B12.PNG)
![Proje Takip](https://github.com/Snmzgrkn/TakipProje/blob/master/Ekran%20Al%C4%B1nt%C4%B1s%C4%B13.PNG)

## Katkı

Katkıda bulunmak isterseniz, lütfen `CONTRIBUTING.md` dosyasını okuyun ve pull talepleri gönderin.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasını inceleyin.
