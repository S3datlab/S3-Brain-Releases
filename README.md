# S3 Brain

## Türkçe

S3 Brain, yapay zekâ araçların için ortak, kaynağı gösteren yerel hafıza sağlayan bir Mac uygulamasıdır. Claude Code ve Codex konuşmalarından kararları ve sonuçları yakalar; Claude Desktop, Cursor, VS Code / GitHub Copilot, Windsurf, Gemini CLI, Zed, Cline ve diğer araçlara hafıza araçlarını (MCP) bağlar. Hafızan senin Mac'inde, okunabilir bir Markdown klasöründe durur. Menü çubuğunda çalışır, 11 dil destekler, yeni sürümleri imzalı uygulama içi güncellemeyle getirir.

**Lisans:** Bireyler için **kişisel, ticari olmayan kullanımda ücretsizdir.** Şirketler, işverenler, müşteri işleri, serbest çalışma ve diğer ticari kullanım için yazılı izin gerekir: sedat@s3dat.com. Açık kaynak değildir; tüm hakları saklıdır. Ayrıntı: [Kullanım Koşulları](EULA.md).

**Gereksinimler:** Apple silicon Mac (M serisi), macOS 14 veya üzeri. Python vb. kurmanız gerekmez.

1. [Releases](https://github.com/S3datlab/S3-Brain-Releases/releases/latest) sayfasından `S3-Brain-…-macOS-arm64.dmg` dosyasını indirin.
2. DMG'yi açın ve **S3 Brain**'i **Applications / Uygulamalar** klasörüne sürükleyin.
3. Uygulamalar'dan açın. Uygulama Developer ID ile imzalıdır ve Apple tarafından notarize edilmiştir; macOS ilk açılışta internetten indirilen bir uygulamayı açmak isteyip istemediğinizi sorar, **Aç**'ı seçin. İmza veya zararlı yazılım uyarısı görürseniz durun ve bildirin; güvenlik ayarlarını kapatmayın.
4. Kurulum sihirbazı ilk açılışta başlar: dil, kayıt yöntemi ve bağlanacak yapay zekâ araçlarını seçersiniz. Her değişiklik önizlenir ve geri alınabilir.

Hafıza kaydı varsayılan olarak kendi yapay zekâ aracınız aracılığıyla yapılır. İsterseniz kendi API anahtarınızla veya yerel bir modelle (Ollama, LM Studio) arka plan özetlemesini açabilirsiniz; metin parçaları yalnızca seçtiğiniz sağlayıcıya gider. Güncelleme denetimi bu depoya (GitHub) yapılır. Ayrıntı: [Gizlilik Bildirimi](PRIVACY.md).

Hataları [Issues](https://github.com/S3datlab/S3-Brain-Releases/issues) üzerinden bildirin: uygulama sürümü, macOS sürümü ve tekrarlama adımlarını ekleyin. **Parola, API anahtarı, token veya kişisel/gizli veri paylaşmayın.** Güvenlik sorunları ve özel destek: sedat@s3dat.com. Üçüncü taraf bileşenlerin kendi lisansları vardır; uygulamadaki lisans bildirimlerinde listelenir. Hukuki metinlerin Türkçesi bağlayıcıdır.

## English

S3 Brain is a Mac app that gives your AI tools a shared, source-linked local memory. It captures decisions and outcomes from Claude Code and Codex conversations and connects memory tools (MCP) to Claude Desktop, Cursor, VS Code / GitHub Copilot, Windsurf, Gemini CLI, Zed, Cline and more. Your memory lives on your Mac as a readable Markdown folder. It runs from the menu bar, supports 11 languages and delivers new versions as signed in-app updates.

**License:** **Free for personal, non-commercial use by individuals.** Use by or for companies, employers, clients, freelance work or any other commercial purpose requires written permission: sedat@s3dat.com. Not open source; all rights reserved. See the [Terms of Use](EULA.en.md) (the [Turkish text](EULA.md) prevails).

**Requirements:** Apple silicon Mac (M series), macOS 14 or later. No Python or other installs needed.

1. Download the `S3-Brain-…-macOS-arm64.dmg` file from the [latest release](https://github.com/S3datlab/S3-Brain-Releases/releases/latest).
2. Open the DMG and drag **S3 Brain** into **Applications**.
3. Open it from Applications. The app is Developer ID signed and notarized by Apple; on first launch macOS asks whether to open an app downloaded from the internet — choose **Open**. If you see a signature or malware warning, stop and report it; do not disable security settings.
4. The setup wizard starts on first launch: you choose language, capture method and which AI tools to connect. Every change is previewed and reversible.

By default, memories are written through your own AI tool. You can optionally turn on background summaries with your own API key or a local model (Ollama, LM Studio); excerpts go only to the provider you choose. Update checks go to this repository (GitHub). See the [Privacy Notice](PRIVACY.md#english).

Report bugs in [Issues](https://github.com/S3datlab/S3-Brain-Releases/issues) with the app version, macOS version and reproduction steps. **Do not post secrets:** passwords, API keys, tokens or personal/confidential data. Security issues and private support: sedat@s3dat.com. Third-party components keep their own licenses, listed in the app's license notices.
