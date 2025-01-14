Öğrenci ve Ders Yönetim Sistemi

Bu proje, Öğrenci ve Ders Yönetim Sistemi uygulamasını simüle eden bir Console Uygulamasıdır. Kullanıcılar, sistemdeki öğrencileri, öğretim görevlilerini ve dersleri yönetebilirler. Veriler, JSON formatında yerel dosyalarda saklanır.

Proje Gereksinimleri

Öğrenci ve Öğretim Görevlisi nesneleri JSON dosyaları üzerinden yönetilmektedir.
Dersler her öğrenci için ayrı ayrı eklenip çıkarılabilir ve derslerin bilgileri öğretim görevlileriyle ilişkilendirilir.
IPerson arayüzü, Login ve BilgiGoster metotları ile giriş yapılmasını ve bilgilerin gösterilmesini sağlar.
Kayıtlar JSON dosyalarında saklanır ve her ekran girdisi bu dosyalara kaydedilir.
Özellikler

Öğrenci ekleme, öğretim görevlisi ekleme, ders ekleme işlemleri yapılabilir.
Derslere öğrenci kaydı yapılabilir.
Kayıtlı öğrenciler ve dersler görüntülenebilir.
Veriler JSON formatında yerel dosyalara kaydedilir.
Kullanım

1. Proje Başlatma
Projeyi Visual Studio veya Rider gibi bir IDE ile açın.
Projeyi çalıştırarak aşağıdaki adımları takip edebilirsiniz.
2. Ekran Girdileri
1 - Öğrenci Kayıt Etme: Öğrenci adı, soyadı ve öğrenci numarası girilerek yeni bir öğrenci kaydedilir.
2 - Öğretim Görevlisi Kayıt Etme: Öğretim görevlisinin adı, soyadı ve sicil numarası girilerek yeni bir öğretim görevlisi kaydedilir.
3 - Ders Kayıt Etme: Dersin adı ve kredi değeri girilir ve belirtilen öğretim görevlisiyle ilişkilendirilir.
4 - Kayıtlı Öğrencileri Göster: Kayıtlı tüm öğrenciler ekranda görüntülenir.
5 - Kayıtlı Dersleri Göster: Kayıtlı tüm dersler ve derslerdeki öğrenciler ekranda görüntülenir.
6 - Çıkış: Programdan çıkılır.
3. Verilerin Saklanması
Veriler, JSON dosyalarında saklanır. Projede şu dosyalar bulunmaktadır:

ogrenciler.json: Öğrenci verilerini içerir.
ogretimGorevlisi.json: Öğretim görevlisi verilerini içerir.
dersler.json: Ders verilerini içerir.
