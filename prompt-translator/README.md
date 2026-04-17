# 🌐 Prompt Translator (Tercüman)

Bu yetenek, Türkçe olarak tasarladığınız prompt fikirlerini, yapay zekanın (LLM) en yüksek performansla anlayabileceği **"AI-Friendly English"** (Yapay Zeka Dostu İngilizce) formatına dönüştürür.

## ✨ Neden Bu Skill'i Kullanmalısınız?

Yapay zeka modelleri (özellikle Claude 3.5/3.7 ve GPT-4/5 serisi) İngilizce talimatlarda çok daha hassas sonuçlar verir. Ancak sadece çeviri yapmak yetmez; promptun içindeki **niyeti, kısıtlamaları ve formatı** korumak gerekir. 

**Tercüman şunları yapar:**
- Türkçe metindeki anlatım bozukluklarını giderir.
- Belirsiz komutları, niyetinizi bozmadan netleştirir.
- Kelimesi kelimesine değil, "talimat odaklı" çeviri yapar.
- Çıktıyı doğrudan kopyalanabilir kod bloğu içinde sunar.

---

## 🚀 Kurulum ve Kullanım

### 1. Dosyaları Alın
Klasör içindeki `skill.md` dosyasının içeriğini kopyalayın.

### 2. Yapay Zekaya Tanımlayın
Kopyaladığınız metni; **Roo Code**, **Cline**, **Cursor** kurallarına veya kullandığınız yapay zekanın **Sistem Mesajı (System Instruction)** kısmına yapıştırın.

### 3. Kullanmaya Başlayın
Artık tek yapmanız gereken Türkçe taslağınızı göndermek. 

**Örnek Giriş:**
> "Bana bir e-ticaret sitesi için veri tabanı şeması çıkar ama sadece kullanıcı ve sipariş tabloları olsun, sql formatında ver."

**Örnek Çıktı:**
> 🇬🇧 `Generate a database schema for an e-commerce site in SQL format. Include only the users and orders tables. Ensure the relationship between them is clearly defined.`
> 
> 🇹🇷 Bir e-ticaret sitesi için SQL formatında bir veritabanı şeması oluştur. Sadece kullanıcılar ve siparişler tablolarını dahil et. Aralarındaki ilişkinin açıkça tanımlandığından emin ol.
> 
> 🔧 Değişiklikler: SQL formatı vurgulandı ve tablolar arası ilişki gerekliliği AI için netleştirildi.

---

## ⚠️ Dikkat Edilmesi Gerekenler
- Bu araç, sizin niyetinizin ötesine geçip "daha iyi bir prompt yazmaya" çalışmaz; sadece niyetinizi AI'nın en iyi anlayacağı dile tercüme eder.
- Eğer talimatlarınızda çelişki varsa, çeviri yapmak yerine size netleştirme soruları sorar.

---
*Hazırlayan: [Hüseyin Arslandoğan](https://github.com/hsyncomtr)*
