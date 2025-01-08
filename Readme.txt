# 🥒 Cucumber HH Project
<br><br>
Cucumber HH Project, web tabanlı uygulamaların test otomasyonu için geliştirilmiş bir framework'tür.  
Framework, aşağıdaki özellikleri içerir:<br><br>

- Gherkin dili ile yazılmış senaryolar.  
- Selenium WebDriver ile UI otomasyonu.  
- Cucumber ile BDD tabanlı test senaryoları.  
- ExtentReports ile detaylı test raporlaması.  

Bu proje, test süreçlerini kolaylaştırmak ve yüksek doğruluk sağlamak için optimize edilmiştir.  
<br><br>

## ✨ Ana Özellikler
<br><br>
- **UI Test Otomasyonu**: Kullanıcı arayüzü bileşenlerinin uçtan uca test edilmesi.  
- **Cucumber BDD**: İş birliğini artırmak için kolay anlaşılabilir Gherkin formatı.  
- **Selenium Entegrasyonu**: Web tabanlı uygulamaların otomatik testleri için güçlü bir araç.  
- **Raporlama**: ExtentReports ile detaylı test sonuçlarının görselleştirilmesi.  
<br><br>

## 📐 Kullanılan Teknolojiler ve Bağımlılıklar
Bu projede aşağıdaki teknolojiler kullanılmıştır:<br><br>

- **Cucumber**: BDD framework.  
- **Selenium WebDriver**: UI otomasyon kütüphanesi.  
- **JUnit**: Test çalıştırma framework'ü.  
- **ExtentReports**: Raporlama kütüphanesi.  
- **Maven**: Proje yönetimi ve bağımlılık yönetimi.  
<br><br>

## 🔧 Kurulum ve Çalıştırma
<br><br>
Projeyi yerel bilgisayarınıza klonlayın:  
`git clone https://github.com/seflekL/Cucumber_HH_Project.git`  
<br><br>
Proje dizinine gidin:  
`cd Cucumber_HH_Project`  
<br><br>
Maven bağımlılıklarını yükleyin:  
`mvn clean install`  
<br><br>
Testleri çalıştırın:  
`mvn test`  
<br><br>

## 📊 Test Özellikleri
<br><br>
### Test Kapsamı
- **Giriş Senaryoları**: Kullanıcı giriş işlemlerinin doğrulanması.  
- **Form Doğrulama**: Formların doğru bir şekilde çalışıp çalışmadığının testi.  
- **Sayfa Yönlendirme**: Doğru sayfalara yönlendirme ve bağlantı kontrolleri.  
- **UI Bileşenleri**: Düğmeler, metin kutuları ve dropdown listelerinin testi.  
<br><br>

### Örnek Senaryo
Feature: Kullanıcı Giriş Kontrolü  
<br><br>
Scenario: Geçerli bilgilerle giriş yapılması  
<br><br>
- Given Kullanıcı giriş sayfasını açar  
- When Kullanıcı geçerli kullanıcı adı ve şifreyi girer  
- And Giriş butonuna tıklar  
- Then Kullanıcı, başarılı bir şekilde ana sayfaya yönlendirilmelidir  
<br><br>

## 📫 İletişim
<br><br>
Projeyi geliştiren kişiye ulaşmak için:  
**GitHub**: [seflekL](https://github.com/seflekL)
