# Yapay Zeka Destekli Akademik Ders Programı Planlayıcısı

Bu proje, akademik bölümlerin ders programı hazırlama süreçlerini optimize etmek amacıyla **Kısıt Programlama (Constraint Programming)** algoritması temel alınarak geliştirilmiş açık kaynaklı bir masaüstü otomasyonudur. 

Altyapısında Google'ın optimizasyon çözücüsü **OR-Tools** ve arayüz için **Tkinter** kullanılmıştır.

## 🚀 Temel Özellikler
* **Çakışma Kontrolü:** Öğretim elemanı, sınıf, laboratuvar ve öğrenci gruplarının saat çakışmalarını %100 oranında engeller.
* **Mekan Kategorizasyonu:** Dersleri gereksinimlerine göre (Genel Derslik, Anfi, Laboratuvar Tipleri) ilgili mekanlara akıllıca atar.
* **Zaman Kilidi (Sabitleme):** Kurum dışı etkenlere bağlı dersleri belirli bir gün ve saate "çivileme" imkanı sunar.
* **Esnek Blok Süreleri:** 8 saatlik tam gün uygulamaları veya standart blok dersleri başarıyla yönetir.
* **Excel'e Aktarım:** Üretilen çakışmasız ders programını saniyeler içinde kurumsal Excel formatına dönüştürür.
* **Bağımsız Bölüm Yönetimi:** Tüm verileri JSON formatında tutarak farklı bölümler (Sosyal Hizmet, Fizyoterapi, Çocuk Gelişimi vb.) için ayrı ayrı yapılandırılabilir.

## 🛠️ Kullanılan Teknolojiler
* **Python 3.x**
* **Google OR-Tools** (Yapay Zeka ve Kısıt Çözücü Algoritma)
* **Tkinter & ttk** (Grafik Kullanıcı Arayüzü)
* **OpenPyXL / Pandas** (Excel Veri İşlemleri)

## 📥 Kurulum ve Çalıştırma
Projeyi bilgisayarınıza klonladıktan sonra gerekli kütüphaneleri yükleyin:
```bash
pip install ortools pandas openpyxl