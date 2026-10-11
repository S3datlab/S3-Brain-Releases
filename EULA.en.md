# S3 Brain End User License Agreement

**Version:** 1.1 · **Effective date:** 11 October 2026

[Türkçe (bağlayıcı metin)](EULA.md) · [Privacy notice](PRIVACY.md#english) · [Third-party notices](THIRD_PARTY_NOTICES.md)

> **Convenience translation.** This English text is provided for convenience only. The Turkish version ([EULA.md](EULA.md)) is the governing version; if the two differ, the Turkish version prevails.

Please read this agreement carefully. By downloading, installing or using S3 Brain, you accept its terms. If you do not accept them, do not install or use the Software.

## 1. Parties and scope

1.1. This End User License Agreement (the "Agreement") is made between **Sedat Üstünova**, the rights holder of the S3 Brain software (the "Rights Holder"), and the natural person who installs or uses the Software (the "User" or "you"). This Agreement licenses only natural persons, and only for personal, non-commercial use; you may not accept, install or use the Software on behalf of, or for the work of, a company, organization or employer (Section 2).

1.2. "Software" means the S3 Brain macOS application, the memory engine, the installation and removal tools, their updates and documentation, and the images supplied with the Software. Open-source components included in the Software are addressed separately in Section 6.

1.3. S3DAT is the brand under which the Rights Holder offers his products. The official website is https://s3dat.com.

## 2. Grant of license

2.1. Subject to your compliance with this Agreement, the Rights Holder grants you a **free, non-exclusive, non-transferable, non-sublicensable and revocable** license to install the Software on Mac computers that you own or control and to use it **solely for personal, non-commercial purposes**.

2.2. **Personal, non-commercial use** means using the Software as an individual for your own personal needs (for example hobby and personal projects, learning and self-study). **Commercial use** means using the Software in any activity that directly or indirectly generates revenue or commercial benefit; in particular, using it in the work of a company, employer, client or other organization, in freelance or paid services, in revenue-generating projects, or in developing a commercial product or service is commercial use. Companies, partnerships, associations, foundations, schools, public bodies and other organizations are not covered by this license.

2.3. The license applies only to copies obtained from **official sources**, meaning https://s3dat.com, the https://github.com/S3datlab/S3-Brain-Releases repository, or channels expressly designated by the Rights Holder. Copies obtained in any other way are not licensed and may be modified or unsafe.

2.4. This Agreement is a license, not a sale. All rights not expressly granted here are reserved by the Rights Holder.

2.5. **Permission for commercial use.** Persons or organizations that wish to use the Software commercially must obtain written permission or a separate commercial license from the Rights Holder at `sedat@s3dat.com` before using it. Commercial use without written permission breaches this Agreement and the license terminates automatically.

## 3. Restrictions

Except where mandatory law expressly permits it, you may not:

a) copy and distribute, publish or share the Software or its installer with others. You may freely share the official download link.

b) modify, translate or adapt the Software or create derivative works from it.

c) reverse engineer, decompile or disassemble the Software. Rights that Turkish Law No. 5846 on Intellectual and Artistic Works and other mandatory provisions grant to a lawful user of a computer program (for example, acts needed for interoperability) are unaffected.

d) rent, lend, sell or sublicense the Software, offer it as a hosted service, or distribute it together with another product or bundle.

e) remove, obscure or alter any copyright, trademark, license or other notice on the Software.

f) circumvent or disable signature checks, update verification or similar technical protection measures in the Software.

g) use the Software or its outputs to develop a product or service that copies the Software's functionality or competes with it. This restriction does not prevent you from using your own notes and content in other tools.

h) use the Software for unlawful purposes, in a way that infringes the rights of third parties, or in breach of the terms of the AI providers you use.

## 4. Intellectual property and trademarks

4.1. All intellectual property rights in the Software's source code, object code, architecture, design, interface, icons and documentation, including economic and moral rights under Law No. 5846, belong to Sedat Üstünova. Apart from the license in Section 2, this Agreement grants you no right or ownership in these rights.

4.2. The names "S3DAT" and "S3 Brain" and their logos and images are distinctive signs of the Rights Holder. Except to refer accurately to the product, you may not use them without the Rights Holder's written permission.

4.3. The Rights Holder acquires no rights in the notes, memory records and other content you create using the Software ("Your Content").

4.4. The Rights Holder may use suggestions and feedback you send to improve the Software without incurring any obligation to you.

## 5. User data and privacy

5.1. **Local operation.** The Software runs on your Mac. Your notes, conversation records, memory vault, indexes and backups are stored on your Mac. If you keep your memory vault in a folder of a sync service such as iCloud Drive, syncing is governed by that service's terms. The Rights Holder does not receive this data. The Software does not send telemetry, usage statistics or analytics.

5.2. **Update check.** The Software connects to GitHub (the S3datlab/S3-Brain-Releases repository, github.com) to check for new versions. This connection only retrieves update information (such as the version, download address and verification data) and does not contain your notes or conversations. As with any internet connection, technical information such as your IP address and the application version may reach the server.

5.3. **Transfers to the AI provider you choose.** To summarize your conversations, the Software sends selected conversation excerpts and limited prior context to the provider **you choose**. That provider may be the Claude Code CLI or Codex CLI signed in with your own account, a service you use with an API key you enter (for example Anthropic, OpenAI, MiniMax, OpenRouter, DeepSeek or Google Gemini), or a local model (for example Ollama or LM Studio). These transfers go directly from your Mac to the provider; the Rights Holder is not a party to them. Processing of the transferred data, charges and quota use are governed by that provider's terms and privacy policy.

5.4. **Your responsibilities.** You are responsible for having the right to use the provider account or API key you use, for complying with that provider's terms and for any charges incurred. You are also responsible for having the right to process the content you feed into the Software, especially third parties' personal data or confidential information.

5.5. **Credentials.** API keys you enter are stored in the macOS Keychain. The Software does not ask for or store the passwords of your Claude or ChatGPT accounts; CLI sign-ins use the providers' official sign-in flows.

5.6. **Backups.** The Software can create local encrypted backups, but these remain on the same Mac. Keeping your backups and recovery key in a separate place to protect against device loss or failure is your responsibility.

5.7. Details are in the [privacy notice](PRIVACY.md#english).

## 6. Third-party software and services

6.1. The Software includes open-source components that are subject to their own licenses. These components and their licenses are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and in the application bundle. For those components the relevant open-source license applies; this Agreement does not restrict the rights those licenses grant you.

6.2. Third-party AI services such as Claude Code, Codex, API providers and local model servers are not provided by the Rights Holder. Their availability, pricing, model behavior and terms may be changed by the providers.

6.3. Claude, Anthropic, OpenAI, ChatGPT, Codex, Cursor, Visual Studio Code and other third-party names and logos are trademarks of their respective owners and are mentioned only to indicate compatibility. S3 Brain is not affiliated with, sponsored by or endorsed by these companies.

## 7. Settings of other AI tools

7.1. For the Software to work, it may need to add session hooks, MCP server definitions and limited instruction blocks to the configuration files of other tools you use (for example Claude Code, Codex, Cursor or Visual Studio Code), and to make limited system settings such as the command-line path and background services.

7.2. These changes are made only with your consent. The Software backs up a configuration file before changing it and tries to preserve unrelated settings.

7.3. You can revert the changes with the Software's removal function or by restoring the backups. Updates to other tools may change their configuration formats, so check your settings after changes.

## 8. Updates and changes

8.1. The Rights Holder may update the Software, add, change or remove features, or discontinue the Software. Unless they come with separate terms, updates are also subject to this Agreement.

8.2. The Rights Holder may amend this Agreement. A new version will be published with its effective date on s3dat.com or within the Software; material changes will be announced reasonably in advance. Continuing to use the Software after the effective date means you accept the new version. If you do not accept it, you may stop using and uninstall the Software.

8.3. The Rights Holder is not obliged to provide support, maintenance or updates.

## 9. Free offering

9.1. The Software is currently free. No fee is charged for the license under this Agreement.

9.2. The Rights Holder may offer paid features, plans or services in the future. Paid offerings will be subject to separate terms shown to you before purchase; you will not be charged without your explicit consent.

9.3. If the terms of features currently offered free of charge are to change, this will be announced reasonably in advance on s3dat.com or within the Software.

## 10. Disclaimer of warranties

10.1. The Software is provided free of charge, **"as is" and "as available"**. To the fullest extent permitted by applicable law, the Rights Holder gives no express or implied warranty, including that the Software will operate without interruption or error, be fit for a particular purpose or be compatible with every system.

10.2. Summaries and memory records produced with AI models may be incomplete, incorrect or outdated. Source checks do not guarantee semantic accuracy. Verify important information against its source, the files and test results.

10.3. There is no guarantee that third-party services will be available or that they will continue to work with the Software after provider updates.

## 11. Limitation of liability

11.1. To the fullest extent permitted by applicable law, the Rights Holder is not liable for indirect damages, loss of profit or business, loss or corruption of data, charges, quota use or account restrictions imposed by AI providers, decisions made on the basis of memory content, changes made to other tools' settings, or damages arising from the use of unofficial copies.

11.2. The Rights Holder is not liable for damages arising from his slight negligence, to the extent permitted by mandatory law.

11.3. This section does not cover liability for intent or gross negligence, damages to life or bodily integrity, or any liability that cannot be excluded or limited in advance under Article 115 of Turkish Code of Obligations No. 6098 or other mandatory provisions.

11.4. If you use the Software as a consumer, your mandatory rights under Turkish Consumer Protection Law No. 6502 and related legislation remain unaffected.

## 12. Termination

12.1. This Agreement remains in force until terminated.

12.2. If you breach this Agreement, the license terminates automatically without further notice. The Rights Holder may terminate the license with reasonable notice if he discontinues the Software or has just cause.

12.3. You may stop using and uninstall the Software at any time.

12.4. When the license ends, you must stop using and uninstall the Software and delete any copies you hold. Termination does not delete Your Content; you can keep using your Markdown notes with other tools.

12.5. Sections 4, 10, 11 and 13 survive the termination of this Agreement.

## 13. Governing law and jurisdiction

13.1. This Agreement is governed by the laws of the Republic of Türkiye, excluding its conflict-of-laws rules. Mandatory consumer protection provisions of your country of residence remain unaffected.

13.2. Where Turkish Code of Civil Procedure No. 6100 permits a jurisdiction agreement, the Istanbul (Central) Courts and Enforcement Offices have jurisdiction over disputes.

13.3. Consumers retain their right under Law No. 6502 to apply to the competent consumer arbitration committee or consumer court.

## 14. Contact

For questions about this Agreement:

- Email: `sedat@s3dat.com`
- Website: https://s3dat.com

## 15. Effective date

15.1. Version 1.0 of this Agreement takes effect on **6 October 2026**.

15.2. The binding text of this Agreement is Turkish. This English translation is provided for convenience only; if the two texts differ, the Turkish text prevails.

15.3. If any provision of this Agreement is held invalid, the remaining provisions stay in force. This Agreement constitutes the entire agreement between the parties regarding use of the Software; separate terms accepted for paid offerings remain reserved.

Copyright (c) 2026 Sedat Üstünova. All rights reserved.
