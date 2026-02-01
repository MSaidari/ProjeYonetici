# 📱 ProjeYonetici - Kurumsal Mobil Asistan

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20|%20iOS-orange?style=for-the-badge)

**ProjeYonetici**, şirket içi bilgi akışını düzenlemek, görev takibini kolaylaştırmak ve kritik kurumsal verileri (alan adları, sistem şifreleri vb.) güvenli bir şekilde yönetmek için tasarlanmış **React Native** tabanlı bir mobil uygulamadır.

Modern arayüzü ve güçlü veri yönetim özellikleri ile hem bireysel kullanıcıların notlarını tutabileceği hem de yöneticilerin ekiplerini koordine edebileceği hibrit bir yapı sunar.

---

## 📸 Ekran Görüntüleri

| Giriş Ekranı | Dashboard | Görev Takvimi |
|:---:|:---:|:---:|
| ![Login Screen](https://via.placeholder.com/200x400?text=Login+Screen) | ![Dashboard](https://via.placeholder.com/200x400?text=Dashboard) | ![Calendar](https://via.placeholder.com/200x400?text=Calendar) |
*(Not: Projenin ekran görüntüleri buraya eklenecektir.)*

---

## 🌟 Temel Özellikler

### 🔐 Kimlik Doğrulama ve Güvenlik
* **Giriş & Kayıt Sistemi:** Güvenli kullanıcı kabul süreci.
* **Rol Bazlı Yetkilendirme (RBAC):** Admin kullanıcılar, diğer personele belirli yetkiler tanımlayabilir. Yetkilendirilmiş kullanıcılar, kendilerine atanan alanlardaki verilere erişebilir.

### 🗂️ Veri Yönetimi (CRUD)
Aşağıdaki modüllerde Ekleme, Silme, Okuma ve Güncelleme işlemleri yapılabilmektedir:
* **Alan Adı (Domain) Takibi:** Şirket bünyesindeki alan adlarının listelenmesi.
* **Sistem Şifreleri & Destek:** Kurumsal hesap bilgilerinin güvenli depolanması.
* **Kişisel Notlar:** Kullanıcıya özel, şifreli not defteri alanı.
* **Görev Tanımlamaları:** Detaylı görev açıklamaları ve atamalar.

### 📅 Planlama ve Bildirimler
* **Takvim Entegrasyonu:** Görevlerin takvim üzerinde görselleştirilmesi sayesinde düzenli iş takibi.
* **Akıllı E-Posta Bildirimleri:** Süresi yaklaşan alan adları (domainler) için otomatik e-posta uyarı sistemi.

### 📊 Dashboard
* Tüm verilerin özetlendiği, kullanıcı dostu ana kontrol paneli.

---

## 🛠️ Teknolojiler

Bu proje aşağıdaki teknolojiler kullanılarak geliştirilmiştir:

* **Frontend Framework:** React Native (CLI / Expo)
* **Dil:** TypeScript (Tip güvenliği ve kod kalitesi için)
* **Navigasyon:** React Navigation
* **Durum Yönetimi (State Management):** (Kullandıysan buraya Redux, Context API veya Zustand yazabilirsin)
* **UI Bileşenleri:** Custom Components

---

## 🚀 Kurulum ve Çalıştırma

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1.  **Repo'yu Klonlayın:**
    ```bash
    git clone [https://github.com/MSaidari/ProjeYonetici.git](https://github.com/MSaidari/ProjeYonetici.git)
    cd ProjeYonetici
    ```

2.  **Bağımlılıkları Yükleyin:**
    ```bash
    npm install
    # veya
    yarn install
    ```

3.  **Uygulamayı Başlatın:**
    *Android için:*
    ```bash
    npx react-native run-android
    ```
    *iOS için:*
    ```bash
    npx react-native run-ios
    ```

---

## 🔮 Gelecek Planları (Roadmap)

Şu anda projenin **Frontend** mimarisi tamamlanmıştır. İlerleyen süreçte yapılması planlananlar:

* [ ] Node.js veya Firebase kullanılarak Backend servislerinin bağlanması.
* [ ] Gerçek zamanlı bildirimler (Push Notifications).
* [ ] Dark Mode (Karanlık Mod) desteği.
* [ ] Çoklu dil desteği (i18n).

---

## 👨‍💻 Geliştirici

**Muhammed Said Arı**
*Bilgisayar Mühendisliği Öğrencisi & Full Stack Geliştirici Adayı*

Proje hakkında sorularınız veya önerileriniz için benimle iletişime geçebilirsiniz.
