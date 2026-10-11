# S3 Brain Gizlilik Bildirimi / Privacy Notice

**Sürüm / Version:** 1.0 · **Yürürlük / Effective:** 6 Ekim 2026 / 6 October 2026

[Türkçe](#türkçe) · [English](#english)

## Türkçe

Bu bildirim, S3 Brain'in verilerinizi nerede tuttuğunu ve hangi verilerin nereye gittiğini açıklar. Yazılım'ın hak sahibi Sedat Üstünova'dır ("Hak Sahibi"). Kullanım koşulları [EULA.md](EULA.md) içindedir.

### Kısaca

- Notlarınız, konuşma kayıtlarınız ve hafıza kasanız Mac'inizde kalır. Hak Sahibi bunları almaz.
- Telemetri, kullanım istatistiği veya analitik veri gönderilmez.
- Özetleme için seçili konuşma parçaları, **sizin seçtiğiniz** yapay zekâ sağlayıcısına gönderilir.
- Güncelleme denetimi için yalnızca GitHub'a (S3datlab/S3-Brain-Releases) güncelleme bilgisi isteği yapılır.

### Mac'inizde kalan veriler

- Claude Code ve Codex gibi araçların Mac'inizde tuttuğu yerel konuşma kayıtları S3 Brain tarafından okunur. Yalnızca erişilebilir yerel kayıtlar işlenir; yalnızca bulutta duran sohbetler kapsam dışındadır.
- Bu kayıtlardan üretilen Markdown notları, hafıza kasası, kayıt defteri, iş kuyruğu, arama ve vektör indeksleri, ayarlar ve şifreli yedekler Mac'inizde saklanır.
- Yerel arama ve anlamsal arama modeli Mac'inizde çalışır; arama için buluta veri gönderilmez.
- Hafıza kasanız iCloud Drive veya başka bir eşitleme hizmetinin eşitlediği bir klasörde bulunuyorsa, notlarınız o hizmete o hizmetin koşullarıyla aktarılır. macOS'ta "Masaüstü ve Belgeler" klasörlerini iCloud Drive ile eşitliyorsanız, varsayılan `~/Documents` konumu da buna dâhildir. Bu, sizin eşitleme ayarlarınıza bağlıdır.

### Seçtiğiniz yapay zekâ sağlayıcısına giden veriler

Konuşmalarınızı özetlemek için S3 Brain, seçili konuşma parçalarını ve sınırlı önceki bağlamı seçtiğiniz sağlayıcıya gönderir:

- kendi hesabınızla giriş yaptığınız Claude Code CLI veya Codex CLI,
- girdiğiniz API anahtarıyla kullandığınız bir hizmet (ör. Anthropic, OpenAI, MiniMax, OpenRouter, DeepSeek, Google Gemini),
- ya da yerel bir model (ör. Ollama, LM Studio). Yerel model kullandığınızda veriler sizin kontrolünüzdeki cihazda veya ağda kalır.

Bu aktarım Mac'inizden doğrudan sağlayıcıya yapılır; Hak Sahibi bu verileri görmez. Verilerin sağlayıcı tarafında işlenmesi, saklanması ve ücretlendirme ilgili sağlayıcının koşullarına ve gizlilik politikasına tabidir. Gönderilmeden önce bilinen sır biçimleri (ör. anahtar ve token kalıpları) temizlenmeye çalışılır; ancak bu filtre her gizli bilgiyi tanıyamaz. Belirli bir oturumun kaydedilmemesini S3 Brain'e bildirebilirsiniz.

### Hak Sahibi'ne giden veriler

- **İçerik:** Yok. Notlarınız, konuşmalarınız ve hafıza kayıtlarınız Hak Sahibi'ne gönderilmez.
- **Telemetri:** Yok. S3 Brain kullanım, analitik veya hata raporu göndermez.
- **Güncelleme denetimi:** S3 Brain yeni sürümleri denetlemek için GitHub'a (S3datlab/S3-Brain-Releases deposu) bağlanır ve yalnızca güncelleme bilgisini alır. Her internet bağlantısında olduğu gibi IP adresiniz ve uygulama sürümü gibi teknik bilgiler GitHub sunucularına ulaşabilir; bunlar GitHub'ın kendi gizlilik politikasına tabidir.
- **İletişim:** Hak Sahibi'ne e-posta gönderirseniz, yalnızca sizin paylaştığınız bilgiler yanıt vermek için kullanılır.

### Kimlik bilgileri

Girdiğiniz API anahtarları macOS Anahtar Zinciri'nde (Keychain) saklanır. S3 Brain, Claude veya ChatGPT hesaplarınızın parolasını istemez ve saklamaz; CLI girişleri sağlayıcıların resmî giriş akışlarıyla yapılır.

### Diğer araçların ayarları

S3 Brain, Claude Code veya Codex gibi araçların ayar dosyalarını yalnızca onayınızla ve önce yedek alarak değiştirir. Ayrıntılar EULA'nın 7. maddesindedir.

### Verilerinizi silme

1. S3 Brain'i kaldırma işleviyle kaldırın. Bu işlem diğer araçlara eklenen bağlantıları, arka plan servislerini ve motoru kaldırır; **hafıza kasanızı silmez**.
2. Hafıza kasası klasörünü silin. Mevcut kurulumda varsayılan konum `~/Documents/S3 Brain` klasörüdür; kurulumda farklı bir klasör seçtiyseniz o klasörü silin.
3. Motorun durum, önbellek ve ayar klasörlerini silin. Mevcut sürümde bunlar `~/.local/state/unified-second-brain`, `~/.local/share/unified-second-brain`, `~/.cache/unified-second-brain` ve `~/.config/unified-second-brain` klasörleridir. Şifreli yedekler ve yedek anahtarı da durum klasöründe tutulur.
4. Girdiğiniz API anahtarlarını Anahtar Zinciri Erişimi uygulamasından silin.
5. Sağlayıcılara daha önce gönderilmiş veriler için ilgili sağlayıcının silme ve saklama seçeneklerini kullanın.

Başka bir yere kopyaladığınız yedekleri veya eşitleme hizmetlerindeki kopyaları ayrıca silmeniz gerekir.

### Sorumluluğunuz

S3 Brain'e başkalarına ait kişisel veriler veya gizli bilgiler içeren konuşmalar aktarıyorsanız, bu verileri işleme ve seçtiğiniz sağlayıcıya gönderme hakkına sahip olduğunuzdan siz sorumlusunuz.

### Değişiklikler ve iletişim

Bu bildirim güncellenebilir; yeni sürüm yürürlük tarihiyle birlikte s3dat.com'da veya Yazılım içinde yayımlanır. Sorularınız için: `sedat@s3dat.com` · https://s3dat.com

---

## English

This notice explains where S3 Brain keeps your data and which data goes where. The rights holder of the Software is Sedat Üstünova (the "Rights Holder"). The terms of use are in [EULA.en.md](EULA.en.md); the Turkish version above prevails.

### In short

- Your notes, conversation records and memory vault stay on your Mac. The Rights Holder does not receive them.
- No telemetry, usage statistics or analytics are sent.
- For summarization, selected conversation excerpts are sent to the AI provider **you choose**.
- For update checks, only a request for update information is made to GitHub (S3datlab/S3-Brain-Releases).

### Data that stays on your Mac

- S3 Brain reads the local conversation records that tools such as Claude Code and Codex keep on your Mac. Only accessible local records are processed; conversations that exist only in the cloud are out of scope.
- The Markdown notes, memory vault, record ledger, job queue, search and vector indexes, settings and encrypted backups derived from these records are stored on your Mac.
- Local search and the semantic search model run on your Mac; no data is sent to the cloud for search.
- If your memory vault is in a folder synced by iCloud Drive or another sync service, your notes are transferred to that service under its terms. If you sync your Desktop and Documents folders with iCloud Drive on macOS, this includes the default `~/Documents` location. This depends on your sync settings.

### Data sent to the AI provider you choose

To summarize your conversations, S3 Brain sends selected conversation excerpts and limited prior context to the provider you choose:

- the Claude Code CLI or Codex CLI signed in with your own account,
- a service you use with an API key you enter (for example Anthropic, OpenAI, MiniMax, OpenRouter, DeepSeek or Google Gemini),
- or a local model (for example Ollama or LM Studio). With a local model, the data stays on a device or network you control.

This transfer goes directly from your Mac to the provider; the Rights Holder does not see this data. Processing, retention and charges on the provider's side are governed by that provider's terms and privacy policy. Known secret formats (such as key and token patterns) are filtered out before sending where possible, but the filter cannot recognize every secret. You can tell S3 Brain not to record a particular session.

### Data sent to the Rights Holder

- **Content:** None. Your notes, conversations and memory records are not sent to the Rights Holder.
- **Telemetry:** None. S3 Brain does not send usage data, analytics or crash reports.
- **Update check:** S3 Brain connects to GitHub (the S3datlab/S3-Brain-Releases repository) to check for new versions and only retrieves update information. As with any internet connection, technical information such as your IP address and the application version may reach GitHub's servers, where GitHub's own privacy policy applies.
- **Contact:** If you email the Rights Holder, only the information you share is used to reply.

### Credentials

API keys you enter are stored in the macOS Keychain. S3 Brain does not ask for or store the passwords of your Claude or ChatGPT accounts; CLI sign-ins use the providers' official sign-in flows.

### Settings of other tools

S3 Brain changes the configuration files of tools such as Claude Code or Codex only with your consent and after making a backup. Details are in Section 7 of the EULA.

### Deleting your data

1. Uninstall S3 Brain with its removal function. This removes the connections added to other tools, the background services and the engine; it **does not delete your memory vault**.
2. Delete the memory vault folder. In the current installation the default location is `~/Documents/S3 Brain`; if you chose a different folder during setup, delete that folder.
3. Delete the engine's state, cache and settings folders. In the current version these are `~/.local/state/unified-second-brain`, `~/.local/share/unified-second-brain`, `~/.cache/unified-second-brain` and `~/.config/unified-second-brain`. Encrypted backups and the backup key are also kept in the state folder.
4. Delete any API keys you entered using the Keychain Access app.
5. For data already sent to providers, use that provider's deletion and retention options.

Backups you copied elsewhere and copies in sync services must be deleted separately.

### Your responsibility

If you feed S3 Brain conversations that contain other people's personal data or confidential information, you are responsible for having the right to process that data and to send it to the provider you choose.

### Changes and contact

This notice may be updated; a new version will be published with its effective date on s3dat.com or within the Software. Questions: `sedat@s3dat.com` · https://s3dat.com
