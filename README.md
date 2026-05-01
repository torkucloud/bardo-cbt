# BARDO Lens

> Bilişsel Davranışçı Terapi (BDT) odaklı, yapay zekâ destekli dijital düşünce kaydı asistanı.

**BARDO Lens**, BARDO Psikoloji bünyesinde geliştirilen ve psikologların görüşme sürecinde danışanlarına rehberlik etmesini sağlayan tek dosyalık bir HTML uygulamasıdır. Sokratik sorgulama yöntemiyle çalışan bu araç, bilişsel çarpıtmaları tespit etmek ve yeniden çerçeveleme sürecini yapılandırmak amacıyla tasarlanmıştır.

---

## 🎯 Amacımız

BARDO Lens, psikolojik danışmanlık ortamında BDT temelli düşünce kayıt sürecini dijitalleştirerek:

- Psikologların görüşme sürecinde danışanlarına yapılandırılmış bir rehberlik sunmasını sağlamak,
- Danışanların kendi düşünce kalıplarını keşfetmelerine ve anlamlandırmalarına yardımcı olmak,
- Bilişsel yeniden çerçeveleme (D-Şeması) sürecini interaktif bir deneyime dönüştürmek,
- Türkçe ve İngilizce dil desteğiyle farklı kullanıcı gruplarına erişilebilir olmak.

**Önemli Not:** BARDO Lens bir tedavi aracı veya terapi yerine geçmez. Psikolojik danışmanlık sürecini destekleyici bir dijital araçtır.

---

## 🛠️ Nasıl Kullanılır

### Psikologlar İçin

1. `bardo-cbt-v6.html` dosyasını herhangi bir web tarayıcısında açın (sunucu gerekmez).
2. Görüşme başında uygulama dilini (Türkçe/İngilizce) seçerek başlayın.
3. **Bilgilendirme** ekranını okuyup onay verdikten sonra psikoeğitim kartları ile süreci tanıtın.
4. **BDT Üçgeni** ekranında olay, düşünce, duygu ve beden tepkilerini danışanla birlikte doldurun.
5. **Topraklama** egzersiziyle duruma odaklanmayı sağlayın.
6. **Diyalog** aşamasında Sokratik sorgulama yöntemini kullanarak danışanın düşünce yapısını keşfedin (en fazla 8 tur).
7. Onay özetleri ve D-E geçişiyle **Çürütme (D-Şeması)** aşamasına geçin.
8. **Dengeli Düşünce (E-Şeması)** ile alternatif bakış açılarını ve dengeli düşünceyi formüle edin.
9. Seans sonunda otomatik oluşturulan **Özet Raporu** ile süreci değerlendirin.

### Danışanlar İçin

1. Psikoloğunuzun yönlendirmesiyle uygulamayı açın.
2. Adım adım ilerleyerek kendi düşünce, duygu ve davranışlarınızı kaydedin.
3. Yapay zekâ asistanının size yönelttiği sorulara açık ve dürüst şekilde yanıt verin.
4. Çürütme aşamasında düşüncenizi destekleyen ve desteklemeyen kanıtları düşünün.
5. Dengeli düşünce formülasyonuyla süreci tamamlayın.

---

## 📋 Pratik Değer ve Önemi

### Psikologlar İçin Faydalar
- **Yapılandırılmış Süreç:** BDT düşünce kaydı sürecini adım adım takip etmenizi sağlar, hiçbir aşamayı atlamadan ilerlemenizi garantiler.
- **Zaman Tasarrufu:** Görüşme sürecinde manuel not alma yerine dijital kayıt tutarak seans verimliliğini artırır.
- **Sokratik Sorgulama Rehberi:** Hazır soru rotasyon sistemi ile farklı soru tiplerini (bilgi, çeviri, yorum, geçmiş, analiz, sentez) otomatik olarak kullanmanızı sağlar.
- **Raporlama:** Seans sonunda kısa/terapist/tamamış olmak üzere üç farklı formatta otomatik rapor oluşturur.
- **BYOP Desteği:** Pollinations.ai "Bring Your Own Pollen" (BYOP) sistemi ile kendi API anahtarınızı kullanarak sınırsız kullanım imkânı sunar.

### Danışanlar İçin Faydalar
- **Kendi İçgörüsünü Geliştirme:** Düşünce kayıt süreci boyunca kendi bilişsel kalıplarını keşfetme fırsatı bulur.
- **Yapılandırılmış Keşif:** Serbest sohbet yerine yönlendirilmiş sorular sayesinde daha derin bir içgörü elde eder.
- **Görselleştirme:** BDT üçgeni, inanç derecesi kaydırıcıları ve önce/sonra karşılaştırması ile süreç görsel olarak takip edilir.
- **Dil Seçeneği:** Türkçe ve İngilizce dil desteği ile kendi dilinde rahatça iletişim kurar.

---

## 👤 Kimler İçin Uygun?

### Uygun Olanlar
- BDT yaklaşımını kullanan psikologlar ve psikolojik danışanlar
- Bilişsel yeniden çerçeveleme sürecini yapılandırılmış bir araçla desteklemek isteyen profesyoneller
- Kendi düşünce kalıplarını keşfetmek isteyen ve bu süreci bir uzmanla yürüten bireyler

### Uygun Olmayanlar
- Akut kriz durumu olan kişiler (bu araç acil müdahale sağlamaz)
- Profesyonel gözetim olmadan kendi başına kullanmak isteyenler
- BDT yaklaşımıyla çalışmayan terapi ekollerini benimseyen profesyoneller

---

## 🔧 Teknik Detaylar

| Özellik | Açıklama |
|---------|----------|
| **Format** | Tek dosya HTML (sunucu gerektirmez) |
| **Boyut** | ~244 KB |
| **Dil Desteği** | Türkçe / İngilizce |
| **AI Backend** | Pollinations.ai API (BYOP desteğiyle) |
| **Kimlik Doğrulama** | OAuth 2.0 (enter.pollinations.ai/authorize) |
| **Model Seçimi** | openai-large (varsayılan) / openai-reasoning / openai |
| **Streaming** | SSE tabanlı gerçek zamanlı yanıt (isteğe bağlı) |
| **Veri Saklama** | localStorage (cihaz üzerinde) |
| **Güvenlik** | sk_ geliştirici anahtarı dosyada saklanmaz |

### BYOP (Bring Your Own Pollen) Entegrasyonu

BARDO Lens, Pollinations.ai'nin BYOP sistemi ile entegre çalışır. Bu sayede:

1. `enter.pollinations.ai/authorize` üzerinden OAuth ile giriş yapın.
2. Kendi `pk_` uygulama anahtarınızı ayarlar menüsünden girebilirsiniz.
3. Pollen bakiyenizi ayarlar panelinden takip edebilirsiniz.
4. BYOP olmadan ücretsiz katman sınırlarıyla da kullanılabilir.

---

## 🌐 Geliştirici

**BARDO Psikoloji** — Psikolojik Danışmanlık

---

---

# BARDO Lens

> A cognitive behavioral therapy (CBT) focused, AI-powered digital thought record assistant.

**BARDO Lens** is a single-file HTML application developed under BARDO Psikoloji, designed to help psychologists guide their clients through structured CBT thought record sessions. Using Socratic questioning methodology, this tool helps identify cognitive distortions and structure the cognitive restructuring process.

---

## 🎯 Purpose

BARDO Lens digitizes the CBT-based thought record process in psychological counseling settings to:

- Provide psychologists with a structured framework to guide clients during sessions,
- Help clients discover and make sense of their own thought patterns,
- Transform the cognitive restructuring (D-Worksheet) process into an interactive experience,
- Offer accessibility across different user groups with Turkish and English language support.

**Important Note:** BARDO Lens is not a treatment tool or a substitute for therapy. It is a digital support tool for psychological counseling processes.

---

## 🛠️ How to Use

### For Psychologists

1. Open `bardo-cbt-v6.html` in any web browser (no server required).
2. Select the application language (Turkish/English) to begin the session.
3. Read through the **Information** screen and provide consent before introducing the process with psychoeducation cards.
4. Use the **CBT Triangle** screen to fill in the event, thought, emotion, and body response together with the client.
5. Perform a **Grounding** exercise to focus on the present situation.
6. In the **Dialogue** phase, use Socratic questioning to explore the client's thought structure (up to 8 turns).
7. After confirmation summaries and the D-E transition, proceed to the **Disputation (D-Worksheet)** phase.
8. With the **Balanced Thought (E-Worksheet)**, formulate alternative perspectives and a balanced thought.
9. At the end of the session, evaluate the process using the automatically generated **Summary Report**.

### For Clients

1. Open the application as directed by your psychologist.
2. Progress step-by-step to record your own thoughts, emotions, and behaviors.
3. Answer the AI assistant's questions openly and honestly.
4. In the disputation phase, consider evidence that supports and contradicts your thought.
5. Complete the process with the balanced thought formulation.

---

## 📋 Practical Value and Significance

### Benefits for Psychologists
- **Structured Process:** Guides you step-by-step through the CBT thought record process, ensuring no stage is skipped.
- **Time Efficiency:** Digital recording during sessions increases session efficiency compared to manual note-taking.
- **Socratic Questioning Guide:** The built-in question rotation system automatically uses different question types (information, translation, interpretation, past, analysis, synthesis).
- **Reporting:** Automatically generates session reports in three formats: short, therapist, and comprehensive.
- **BYOP Support:** Unlimited usage with your own API key through Pollinations.ai's "Bring Your Own Pollen" (BYOP) system.

### Benefits for Clients
- **Developing Self-Insight:** Opportunity to discover own cognitive patterns throughout the thought record process.
- **Structured Exploration:** Guided questions enable deeper insight compared to free conversation.
- **Visualization:** CBT triangle, belief degree sliders, and before/after comparisons allow visual tracking of the process.
- **Language Options:** Communicate comfortably in your preferred language with Turkish and English support.

---

## 👤 Who Is It For?

### Suitable For
- Psychologists and psychological counselors who use the CBT approach
- Professionals who want to support the cognitive restructuring process with a structured tool
- Individuals who want to explore their thought patterns while working with a professional

### Not Suitable For
- Individuals in acute crisis situations (this tool does not provide emergency intervention)
- Those who want to use it on their own without professional supervision
- Professionals who follow therapy modalities that do not align with the CBT approach

---

## 🔧 Technical Details

| Feature | Description |
|---------|-------------|
| **Format** | Single-file HTML (no server required) |
| **Size** | ~244 KB |
| **Language Support** | Turkish / English |
| **AI Backend** | Pollinations.ai API (with BYOP support) |
| **Authentication** | OAuth 2.0 (enter.pollinations.ai/authorize) |
| **Model Selection** | openai-large (default) / openai-reasoning / openai |
| **Streaming** | SSE-based real-time responses (optional) |
| **Data Storage** | localStorage (on-device) |
| **Security** | Developer sk_ key is never stored in the file |

### BYOP (Bring Your Own Pollen) Integration

BARDO Lens integrates with Pollinations.ai's BYOP system. This allows:

1. Sign in via OAuth at `enter.pollinations.ai/authorize`.
2. Enter your own `pk_` application key from the settings menu.
3. Track your Pollen balance from the settings panel.
4. Can also be used without BYOP within free tier limits.

---

## 🌐 Developer

**BARDO Psikoloji** — Psychological Counseling
