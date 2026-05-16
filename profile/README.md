<div align="center">

<img src="https://raw.githubusercontent.com/ainjiner/ainjiner.github.io/main/public/favicon.svg" width="80" height="80" alt="Ainjiner Logo" />

# Ainjiner

**AI Engineering Organization — Built in Indonesia 🇮🇩**

*Building open-source AI tools for developers, educators, and students.*

[![Website](https://img.shields.io/badge/website-ainjiner.github.io-8b5cf6?style=flat-square&logo=astro)](https://ainjiner.github.io)
[![Email](https://img.shields.io/badge/email-hello@ainjiner.ai-8b5cf6?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@ainjiner.ai)
[![GitHub Sponsors](https://img.shields.io/badge/sponsor-GitHub-ea4aaa?style=flat-square&logo=github-sponsors)](https://github.com/sponsors/ainjiner)
[![Open Collective](https://img.shields.io/badge/donate-Open%20Collective-3b82f6?style=flat-square&logo=opencollective)](https://opencollective.com/ainjiner)
[![Ko-fi](https://img.shields.io/badge/ko--fi-ainjiner-f97316?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/ainjiner)
[![Trakteer](https://img.shields.io/badge/trakteer-ainjiner-ef4444?style=flat-square)](https://trakteer.id/ainjiner)

</div>

---

## Who We Are

Ainjiner adalah organisasi open-source dari Indonesia yang membangun tools AI/ML untuk developer, pendidik, dan siswa. Semua proyek kami **MIT licensed**, **self-hosted**, dan **community-driven** — tanpa lock-in, tanpa paywall, tanpa agenda tersembunyi.

Kami percaya bahwa AI seharusnya **memperkuat kemampuan berpikir manusia**, bukan menggantikannya — dan bahwa tools engineering AI berkualitas seharusnya bisa diakses oleh semua developer, bukan hanya mereka yang bekerja di perusahaan besar.

---

## Our Projects

<table>
<tr>
<td width="33%" valign="top">

### 🔬 [AI Lab](https://github.com/ainjiner/ai-lab)

**ML/LLM Engineering Platform**

Unified, self-hosted platform untuk developer AI. Satu tempat untuk semua provider, model, eksperimen, dan cost — tanpa context-switch.

**Highlights:**
- 10 built-in providers (OpenAI, Anthropic, Gemini, Groq, Baseten, OpenRouter, Together, Fireworks, DeepSeek, Ollama)
- Provider registry dengan multi-instance per provider
- Model catalog: search, compare, recommend, aliases
- Experiment tracker dengan cost & latency analytics
- Config sync ke OpenCode, Cursor, Continue, Aider
- REST API (65+ endpoints) + CLI (30+ commands) + Web UI
- SQLite persistence — self-hosted, no proxy required
- OpenCode-native sebagai key differentiator

[![MIT](https://img.shields.io/badge/license-MIT-8b5cf6?style=flat-square)](https://github.com/ainjiner/ai-lab/blob/main/LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/ainjiner/ai-lab)
[![Bun](https://img.shields.io/badge/Bun-f9f9f9?style=flat-square&logo=bun&logoColor=black)](https://bun.sh)

</td>
<td width="33%" valign="top">

### 🧠 [2USE](https://github.com/ainjiner/2USE)

**Socratic AI Middleware** *(double-u-es)*

AI middleware yang **menolak memberikan jawaban instan**. Mengajarkan berpikir kritis melalui metode Socrates. Anti-dependency by design — *the doubled understanding*.

**Highlights:**
- Intercepts LLM queries → responds with Socratic questions first
- Progressive hints: Level 0 → 1 → 2 → 3 → 4
- Thinking time enforcement (min 30s sebelum AI menjawab)
- Homework & lazy-prompt detection
- Dependency monitoring & independence scoring
- Pattern caching (70% cost reduction)
- Multi-LLM: Gemini, OpenAI, Claude, Ollama
- Privacy-first, local-first option

**Philosophy:** `2USE = See process + See result = 2× understanding`

[![MIT](https://img.shields.io/badge/license-MIT-f59e0b?style=flat-square)](https://github.com/ainjiner/2USE/blob/main/LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/ainjiner/2USE)
[![EdTech](https://img.shields.io/badge/EdTech-Socratic%20AI-f59e0b?style=flat-square)](https://github.com/ainjiner/2USE)

</td>
<td width="33%" valign="top">

### 🌟 [We Will Shine](https://github.com/ainjiner/we-will-shine)

**Student Wellbeing Platform** *(W·S)*

Platform open-source untuk career guidance & wellbeing siswa Indonesia, dengan AI mentor. Berawal sebagai hadiah penuh cinta untuk siswa SMP IT Masjid Syuhada — kini berkembang menjadi platform nasional.

**Highlights:**
- AI career guidance dalam Bahasa Indonesia
- 8 eksplorasi karir teknologi masa depan
- Quiz kepribadian (Holland's RIASEC adaptasi)
- Jurnal digital anonim & AI mentor (ruang curhat aman)
- Gamifikasi: points, levels, 8 achievements
- Dream Board — tulis & track impian
- Dashboard Guru BK dengan wellbeing insights
- 100% gratis untuk semua sekolah
- Mobile-optimized, SvelteKit + Tailwind

[![MIT](https://img.shields.io/badge/license-MIT-10b981?style=flat-square)](https://github.com/ainjiner/we-will-shine/blob/main/LICENSE)
[![SvelteKit](https://img.shields.io/badge/SvelteKit-ff3e00?style=flat-square&logo=svelte&logoColor=white)](https://github.com/ainjiner/we-will-shine)
[![Live](https://img.shields.io/badge/demo-live-10b981?style=flat-square)](https://ainjiner.github.io/we-will-shine/)

</td>
</tr>
</table>

---

## Why We Build This

```
45,000,000+ siswa Indonesia tidak punya akses ke AI guidance yang kontekstual
         0  open-source Socratic AI middleware yang ada saat ini
    1 : 500  rasio Guru BK : siswa (standar UNESCO: 1 : 250)
        $0   pendanaan eksternal yang pernah kami terima — semua self-funded
```

Kami membangun karena masalah ini nyata, dan tidak ada yang mengerjakannya dengan pendekatan open-source yang benar untuk konteks Indonesia.

---

## Our Mission

| Nilai | Penjelasan |
|-------|-----------|
| 🌍 **Democratize AI** | Tools ML/LLM berkualitas seharusnya bisa diakses semua developer, bukan hanya perusahaan besar |
| 🔓 **Open Source First** | Semua proyek MIT licensed — tidak ada paywalls, tidak ada lock-in |
| 🧠 **Teach, Don't Replace** | AI seharusnya memperkuat pemikiran manusia, bukan menggantikannya |
| 🇮🇩 **Built in Indonesia** | Untuk konteks Indonesia, oleh developer Indonesia, dengan cinta |
| 📊 **Radical Transparency** | Semua keuangan publik via Open Collective — lihat setiap rupiah masuk dan keluar |

---

## Support Our Work

Semua proyek kami gratis selamanya. Tapi dukungan Anda memungkinkan kami bergerak lebih cepat — dari nights-and-weekends menjadi full-time development.

<div align="center">

| Platform | Link | Keunggulan |
|----------|------|-----------|
| 💗 **GitHub Sponsors** | [github.com/sponsors/ainjiner](https://github.com/sponsors/ainjiner) | Recurring, nama Anda di repo kami |
| 🔵 **Open Collective** | [opencollective.com/ainjiner](https://opencollective.com/ainjiner) | 100% transparan — lihat setiap pengeluaran |
| ☕ **Ko-fi** | [ko-fi.com/ainjiner](https://ko-fi.com/ainjiner) | One-time, mudah dan cepat |
| ❤️ **Trakteer** | [trakteer.id/ainjiner](https://trakteer.id/ainjiner) | Dukungan lokal Indonesia |

</div>

Belum siap donasi? **Star repo kami**, bagikan ke komunitas, atau hubungkan kami dengan peneliti dan pendidik yang peduli AI untuk edukasi.

---

## For Researchers & Institutions

Proyek kami berada di persimpangan **AI Ethics**, **EdTech**, dan **Open Infrastructure** — menjadikannya kandidat kuat untuk penelitian akademik dan hibah institusional.

**Grant yang sedang kami kejar:** Mozilla Technology Fund · NLnet Foundation · Ford Foundation · DIKTI Kedaireka · BRIN RISPRO · Google.org · GitHub Fund

📄 **Dokumen lengkap:**
- [Funding Guide](https://github.com/ainjiner/ainjiner.github.io/blob/main/FUNDING-GUIDE.md) — 13 program funding + cara apply
- [Research Brief](https://github.com/ainjiner/ainjiner.github.io/blob/main/RESEARCH.md) — untuk akademisi & lembaga riset
- [Partnership Opportunities](https://github.com/ainjiner/ainjiner.github.io/blob/main/PARTNERSHIPS.md) — sekolah, NGO, perusahaan, universitas
- [Project Roadmap](https://github.com/ainjiner/ainjiner.github.io/blob/main/docs/ROADMAP.md) — milestone 3 tahun
- [Budget Plan](https://github.com/ainjiner/ainjiner.github.io/blob/main/docs/BUDGET.md) — transparansi anggaran
- [Impact Statement](https://github.com/ainjiner/ainjiner.github.io/blob/main/docs/IMPACT.md) — theory of change & target metrik

---

## Contributing

Kami menyambut kontribusi dari semua kalangan — developer, desainer, peneliti, pendidik, atau siapa saja yang peduli.

**Cara berkontribusi:**
- ⭐ Star repo yang Anda sukai
- 🐛 Report bugs atau request fitur via Issues
- 🔀 Submit pull requests
- 📖 Improve dokumentasi
- 💬 Bergabung di Discussions
- 🏫 Hubungkan kami dengan sekolah atau universitas mitra

---

## Contact

<div align="center">

**hello@ainjiner.ai** · [ainjiner.github.io](https://ainjiner.github.io) · [github.com/ainjiner](https://github.com/ainjiner)

*Building the future of AI development, one tool at a time.*
*Membangun masa depan AI — satu tools pada satu waktu.*

</div>
