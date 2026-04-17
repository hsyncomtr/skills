# Agent Governance & Senior Architect Mode

Bu skill, AI ajanlarının (Roo Code, Cline vb.) kontrolsüz hareket etmesini engelleyen, hata payını minimize eden ve profesyonel bir yazılım mimarı gibi davranmasını sağlayan en katı kurallar setidir.

### Ne Sağlar?
- **Sıfır Varsayım:** AI, bilmediği konularda tahmin yürütmez, soru sorar.
- **Güvenli Değişim:** Onay almadan dosya düzenlemez veya paket yüklemez.
- **Kayıt Tutma:** Tüm süreci `01-UPDATES.log` dosyasına kaydederek bağlamı korur.
- **Sistem Farkındalığı:** Sunucu kaynaklarını ve canlı yayın risklerini gözetir.

### Kurulum
1. `skill.md` dosyasındaki metni kopyalayın.
2. Projenizin `.clinerules` dosyasına veya IDE'nizin "Custom Instructions" alanına yapıştırın.
