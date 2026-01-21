# ⚡ Lithium – Custom Windows ISOs

---
<p align="center">
  <a href="https://mega.nz/folder/BnpnWZiT#zasSycb6_RRpt_mxxRqEag">
    <img src="https://img.shields.io/badge/Download-ISO-blue?style=for-the-badge" />
  </a>
</p>
---

## 🇹🇷 Türkçe Açıklama

Bu proje, **MSMG Toolkit** kullanılarak özelleştirilmiş Windows ISO’ların hazırlanmasını içerir.  
Amaç: Daha sade, optimize edilmiş ve güvenli Windows ortamları oluşturmak. Hem Windows 10 hem de Windows 11 sürümleri için ISO’lar hazırlanır.

### Özellikler
- **MSMG Toolkit** ile bileşen temizleme ve özelleştirme
- **Sysprep + CopyProfile** ile kullanıcı profili aktarımı
- **Explorer Patcher** entegrasyonu (klasik Başlat menüsü ve görev çubuğu düzenlemeleri)
- **Registry tweak’leri** ile performans ve gizlilik ayarları
- Güncellemelerle uyumlu, test edilmiş minimal sistem
- Hem Windows 10 hem de Windows 11 sürümleri için optimize edildi

### Kurulum
1. ISO dosyasını indirin (Releases bölümünde veya README’de verilen linklerden).
2. ISO’yu USB’ye yazdırın (Rufus veya benzeri araçlarla).
3. Kurulum sırasında standart Windows adımları izlenir.
4. İlk oturum açmada Explorer Patcher ve registry tweak’leri otomatik uygulanır.

### Kullanılan Araçlar
- **MSMG Toolkit**: Windows bileşenlerini kaldırma ve özelleştirme
- **Sysprep**: Sistem genelleştirme ve profil aktarımı
- **Explorer Patcher**: Arayüz düzenlemeleri
- **Registry tweaks**: Performans, gizlilik ve minimalizm için ayarlar

### Notlar
- ISO dosyaları büyük olduğundan GitHub’a yüklenmez. Bunun yerine **Releases** bölümünde veya harici linklerle paylaşılır.
- `.gitignore` dosyası ile ISO/WIM gibi büyük dosyalar depoya dahil edilmez.
- Güvenlik için sysprep sonrası SID ve aktivasyon test edilmelidir.
- Tüm değişiklikler önce sanal makinede test edilmiştir.

---

## 🇬🇧 English Description

This project provides **custom Windows ISOs** created with **MSMG Toolkit**.  
Goal: Build streamlined, optimized, and secure Windows environments. ISOs are prepared for both Windows 10 and Windows 11.

### Features
- **MSMG Toolkit** for component removal and customization
- **Sysprep + CopyProfile** for profile transfer
- **Explorer Patcher** integration (classic Start menu and taskbar tweaks)
- **Registry tweaks** for performance and privacy
- Tested minimal system, compatible with updates
- Optimized for both Windows 10 and Windows 11

### Installation
1. Download the ISO (from Releases or provided links).
2. Write ISO to USB (using Rufus or similar tools).
3. Follow standard Windows installation steps.
4. On first login, Explorer Patcher and registry tweaks are applied automatically.

### Tools Used
- **MSMG Toolkit**: Component removal and customization
- **Sysprep**: System generalization and profile transfer
- **Explorer Patcher**: Interface tweaks
- **Registry tweaks**: Performance, privacy, minimalism

### Notes
- ISO files are large and not uploaded directly to GitHub. They are shared via **Releases** or external links.
- `.gitignore` excludes ISO/WIM and other large binaries.
- Sysprep ensures SID and activation consistency.
- All changes are tested in virtual machines before deployment.

