# Casper'ın Sanal Bakımı 👶💻

## 🎮 Giriş

**Casper'ın Sanal Bakımı**'na hoş geldiniz!  
Bu, **C diliyle yazılmış** eğlenceli ve etkileşimli bir **sanal bebek simülasyon oyunudur**.  
Oyunda, *Casper* adında bir sanal bebeğe bakarak onun büyümesini ve gelişmesini sağlarsınız.  
Açlık, uyku, sevgi gibi çeşitli parametreleri yöneterek sanal bir bebeği büyütmenin keyfini ve zorluklarını yaşayacaksınız.

Oyun, oyunculara **sorumluluk ve zaman yönetimi** öğretirken, **etkileşimli görevlerle eğlendirici** bir deneyim sunar.

---

## 🧩 Özellikler

- **🎯 Etkileşimli Oynanış**  
  Casper'a yemek yedirme, oynatma ve eğitme gibi çeşitli aktivitelerden seçim yapın.

- **📊 Çoklu Parametreler**  
  Aşağıdaki 13 farklı ihtiyacı yönetirsiniz:
  - Açlık
  - Uyku
  - Sevgi
  - Sosyalleşme
  - Sağlık
  - Eğitim
  - Hijyen
  - Tuvalet
  - Spor
  - Eğlence
  - Zeka
  - Kişisel Gelişim
  - Psikoloji

- **🔄 Dinamik Sistem**  
  Her eylem birden fazla parametreyi etkiler. Bu nedenle **stratejik kararlar** vermeniz gerekir.

- **💬 Kullanıcı Dostu Arayüz**  
  Konsol tabanlı, İngilizce karakter uyumlu, basit ve anlaşılır menü sistemi.

- **💀 Oyun Bitiş Koşulları**  
  Eğer **Açlık, Uyku** veya **Sağlık** sıfıra düşerse oyun sona erer.

---

## 🕹️ Nasıl Oynanır?

1. **Oyunu Başlatın:**  
   Program çalıştığında Casper’ın tanıtımı görüntülenir.

2. **Eylem Seçin:**  
   14 seçenekli menüden seçim yapın (1–13: aktiviteler, 14: çıkış).

3. **İhtiyaçları İzleyin:**  
   Her eylem sonrası Casper’ın durumunu görün (0–10 arası seviyeler).

4. **Dengeli Planlama Yapın:**  
   Bazı aktiviteler birkaç ihtiyacı artırırken bazılarını azaltır.

5. **Oyun Sonunu Önleyin:**  
   Açlık, Uyku veya Sağlık parametrelerinden biri sıfıra düşerse oyun biter.

---

## ⚙️ Kurulum

### 🧾 Gereksinimler:
- C Derleyicisi (örneğin: `GCC`, `MinGW`, `Code::Blocks`, `Dev-C++`)

### 💾 Kodu İndirin:
- `caspers_virtual_care.c` dosyasını indirin veya kopyalayın.

### 🧪 Derleyin ve Çalıştırın:

**IDE ile:**
- `Code::Blocks` veya `Dev-C++` gibi IDE’lerde dosyayı açın ve derleyin.

**Komut Satırı ile:**
```bash
gcc caspers_virtual_care.c -o casper
./casper
## 🎛️ Oyun İçi Seçenekler

Aşağıdaki 14 seçeneği kullanarak Casper'ın ihtiyaçlarını yönetin:

| No | işlem                       |
|----|-------------------------------|
| 1  | Yemek yedirme                 |
| 2  | Uyutma                        |
| 3  | Sevgi seviyesini artırma      |
| 4  | Sosyalleştirme                |
| 5  | Sağlığı iyileştirme           |
| 6  | Eğitim seviyesini artırma     |
| 7  | Hijyen ayarı                  |
| 8  | Tuvalet düzenleme             |
| 9  | Spor aktivitesi               |
| 10 | Eğlence ayarı                 |
| 11 | Zeka seviyesini yükseltme     |
| 12 | Kişisel gelişime katkı        |
| 13 | Psikolojiyi düzeltme          |
| 14 | Oyunu sonlandırma             |

> 🔁 **Not:** Her seçenek, bazı ihtiyaçları artırırken bazılarını azaltabilir.  
> Örneğin: **Yemek yedirmek**, açlığı azaltır ama hijyen ve spor değerini düşürebilir.

---

## 📝 Notlar

- ⚠️ **Kritik Düşüş Uyarısı:**  
  Açlık, Uyku veya Sağlık sıfıra düşerse **Casper "ölür"** ve oyun sona erer.

- 🔐 **Sınırlar:**  
  İhtiyaç seviyeleri **maksimum 10** olur. 10'u aşan değerler otomatik olarak sabitlenir.

- ❗ **Geçersiz Giriş Kontrolü:**  
  Kullanıcı hatalı giriş yaptığında tekrar giriş yapması istenir.
