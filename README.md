Ödev: Okul Yönetimi Projesi
Açıklama: C# dilinde OOP prensiplerine uygun olarak bir okul yönetimi uygulaması geliştireceksiniz. Uygulama, öğrencileri ve öğretmenleri yönetmeyi ve her ay "Ayın Öğrencisi" belirlemeyi içerecektir.

Görevler:
Model Oluşturma:

Student (Öğrenci) adında bir sınıf oluşturun.

Özellikler:
Id (int)
Name (string)
Grade (int)
GPA (decimal)
Metotlar:
ToString(): Öğrenci bilgilerini döndüren bir metot.
Teacher (Öğretmen) adında bir sınıf oluşturun.

Özellikler:
Id (int)
Name (string)
Subject (string)
Metotlar:
ToString(): Öğretmen bilgilerini döndüren bir metot.
Repository Oluşturma:

StudentRepository adında bir sınıf oluşturun.
Metotlar:
Add(Student student): Yeni bir öğrenci ekler.
Update(Student student): Var olan bir öğrenciyi günceller.
Delete(int id): Bir öğrenciyi siler.
GetAll(): Tüm öğrencileri listeleyen bir metot.
GetById(int id): ID ile belirli bir öğrenciyi bulan bir metot.
Service Oluşturma:

StudentService adında bir servis sınıfı oluşturun.
Bu sınıf, StudentRepository'yi kullanarak öğrenci işlemlerini yöneten metotları içermelidir.
Ayın Öğrencisini Belirleme:

GetStudentOfTheMonth() adında bir metot oluşturun. Bu metot, en yüksek GPA'ya sahip öğrenciyi döndürmelidir.
Ana Program (Program.cs):

Uygulamanızın ana giriş noktasını oluşturun.
Kullanıcıdan bilgi alarak öğrencileri ekleyin, güncelleyin, silin ve ayın öğrencisini belirleyin.
Ekstra Özellikler (İsteğe Bağlı):
Öğrencilerin ve öğretmenlerin listelerini filtreleme veya arama işlevleri ekleyin.
Hataları yakalamak için exception handling ekleyin.
Kullanıcıdan komut almak için basit bir konsol arayüzü oluşturun. 


yeni fikri olan buraya ekler baba
