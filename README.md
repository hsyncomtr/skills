# Agentic AI Skills Library

Bu depo, **Roo Code**, **Cline**, **Roo-Cline** ve **Antigravity** gibi agentic IDE'ler ile gelişmiş LLM'ler (Claude 4.7 Sonnet, GPT-5.4-xhight vb.) için özel olarak tasarlanmış **System Instructions** ve **Custom Skills** koleksiyonudur.

Bu yetenekler, yapay zekanın standart bir sohbet botu yerine; belirli bir uzmanlık alanında (çevirmen, sistem mimarı, hata ayıklayıcı) profesyonel bir **"Otonom Ajan"** gibi davranmasını sağlar.

---

## 🛠 Desteklenen Araçlar

* **Roo Code / Cline:** `.clinerules` dosyasına ekleyerek veya "Custom Instructions" alanına yapıştırarak kullanılabilir.
* **VS Code AI Extensions:** IDE genelindeki sistem mesajlarına entegre edilebilir.
* **Cursor / Windsurf:** "Rules for AI" bölümlerinde mükemmel sonuç verir.

---

## 📂 Yetenek Kataloğu

| Yetenek Adı | Açıklama | Dosya Yolu |
| :--- | :--- | :--- |
| **🌐 Prompt Translator** | Türkçe niyetleri korur, AI için en optimize İngilizce çeviriyi yapar. | [`/prompt-translator`](./prompt-translator/) |
| **🚀 Code Architect** | *Geliştiriliyor* - Modüler ve ölçeklenebilir mimari tasarımı. | - |
| **🐛 Debug Master** | *Geliştiriliyor* - Derinlemesine log analizi ve hata tespiti. | - |

---

## 📥 Kurulum ve Kullanım

### 1. Proje Bazlı (Roo Code / Cline)
Kullanmak istediğiniz yeteneğin klasöründeki `skill.md` içeriğini kopyalayın:
1. Projenizin ana dizininde bir `.clinerules` dosyası oluşturun.
2. Kopyaladığınız metni bu dosyaya yapıştırın.
3. AI, bu projede artık o yeteneğe sahip bir uzman gibi davranacaktır.

### 2. Global Kullanım
Eğer bu yeteneğin her zaman aktif olmasını istiyorsanız:
* IDE ayarlarından **"Custom Instructions"** veya **"Rules for AI"** kısmına metni ekleyin.

---

## 🤝 Katkıda Bulunma

Yeni bir yetenek eklemek, mevcutları iyileştirmek veya bir hata bildirmek için:
1. Depoyu fork'layın.
2. Yeni bir branş oluşturun (`git checkout -b feature/yeniYetenek`).
3. Değişikliklerinizi commit edin ve Pull Request (PR) açın.

---

### 💡 Mimari Felsefesi
Her "skill", **"Minimal müdahale, maksimum netlik"** prensibiyle yazılmıştır. AI'nın orijinal niyetinizi bozmasını engellerken, çıktı kalitesini en üst seviyeye çıkarmayı hedefler.

---
*Hazırlayan: [Hüseyin Arslandoğan](https://github.com/hsyncomtr)*
