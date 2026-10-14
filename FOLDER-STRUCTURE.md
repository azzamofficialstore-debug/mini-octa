# Folder Structure, Mini Octa

## Visual Tree

```
mini-octa/
├── README.md
├── SKILL.md
├── SYSTEM-PROMPT.md
├── FOLDER-STRUCTURE.md
├── standards/
│   └── humanize-writing-guide.md
└── references/
    ├── premise-sharpening.md
    ├── big-idea-to-content.md
    ├── quick-audit-checklist.md
    └── upselling-bridges.md
```

**Total: 9 file.** Tidak lebih, tidak kurang.

---

## Fungsi Per File

| File | Fungsi |
|---|---|
| `README.md` | Onboarding singkat untuk pembeli playbook. Penjelasan apa yang Mini Octa bisa lakukan, apa yang tidak, cara install, tips pakai, dan link akses Octa full version. |
| `SKILL.md` | YAML frontmatter (untuk routing AI) + identitas singkat + 3 capability dengan trigger, alur, output structure, hard limit, redirect pattern + bridging protocol. |
| `SYSTEM-PROMPT.md` | Persona detail Mini Octa, prinsip berpikir, 4 mode kerja step-by-step (3 capability + 1 mode bridging), 7 anti-pattern eksplisit, hubungan dengan Octa full version. |
| `FOLDER-STRUCTURE.md` | Peta folder + perbandingan dengan Octa full version + list file yang sama/diturunkan/eksklusif Mini Octa. (File ini.) |
| `standards/humanize-writing-guide.md` | Protokol penulisan dengan zero tolerance em dash dan antitesis. **Copy persis dari Octa full version.** |
| `references/premise-sharpening.md` | Subset dari Premise Engine Octa. Dipakai di Capability 1. |
| `references/big-idea-to-content.md` | Subset dari Bab 08 + Bab 09 playbook. 5 role konten + format hint per role. Dipakai di Capability 2. |
| `references/quick-audit-checklist.md` | Self-contained checklist 3 lens + 14 issue umum. Dipakai di Capability 3. |
| `references/upselling-bridges.md` | Flow 5-langkah consultative bridging ke Octa full version. Mapping pain user ke mode Octa spesifik. Variasi phrasing supaya tidak template. **Dipakai di setiap output Capability 1, 2, dan 3.** |

---

## Perbandingan dengan Octa Full Version

### Octa Full Version (Skill Induk)

```
octa/
├── SKILL.md                              [23K, 19 mode kerja]
├── SYSTEM-PROMPT.md                      [29K, full persona + brand profile onboarding]
├── FOLDER-STRUCTURE.md
├── frameworks/                           [24 file framework]
│   ├── absurdity-spectrum.md
│   ├── audience-archetype-system.md
│   ├── brand-integration-playbook.md
│   ├── campaign-launch-brand-world.md
│   ├── combinatorial-creativity.md
│   ├── competitive-creative-mapping.md
│   ├── constraint-as-catalyst.md
│   ├── content-ideation-system.md
│   ├── creative-deconstruction.md
│   ├── creative-elevation-ladder.md
│   ├── creative-risk-assessment.md
│   ├── creative-scoring-rubric.md
│   ├── creative-tension-framework.md
│   ├── experience-design-principles.md
│   ├── field-immersion-human-truth.md
│   ├── first-principles-creative.md
│   ├── hook-retention-mechanics.md
│   ├── inversion-thinking.md
│   ├── lateral-thinking-toolkit.md
│   ├── narrative-architecture.md
│   ├── platform-native-thinking.md
│   ├── post-mortem-learning-loop.md
│   ├── premise-engine.md
│   └── reframing-framework.md
├── references/                           [4 file referensi besar + 17 file studi kasus]
│   ├── case-pattern-library.md
│   ├── psychology-mechanics.md
│   ├── ref-arsitektur-konten-viral.md
│   ├── ref-human-centric-beyond-advertising.md
│   ├── ref-modern-campaign-mastery.md
│   └── studi-kasus/
│       └── [sk-01-05.md sampai sk-81-82.md, 17 file]
└── standards/                            [10 file standar]
    ├── anti-safe-rules.md
    ├── standar-arsitektur-ide.md
    ├── standar-campaign.md
    ├── standar-creative-output.md
    ├── standar-deskripsi-konten-kreatif.md
    ├── standar-humanize-writing.md
    ├── standar-pattern-breaking.md
    ├── standar-penulisan-insight-kreatif.md
    ├── standar-rekomendasi-kreatif.md
    └── standar-tone-adaptasi.md
```

**Total Octa full version: ~55 file.**

### Mini Octa

**Total Mini Octa: 9 file.** Pemangkasan ~84% file dari Octa full version.

---

## Mapping File: Apa yang Diturunkan, Apa yang Dipangkas

### File yang Diambil Persis (1 file)

| File | Asal di Octa Full Version |
|---|---|
| `standards/humanize-writing-guide.md` | `standards/standar-humanize-writing.md` (copy persis, zero modifikasi) |

### File yang Diturunkan jadi Subset (2 file)

| File Mini Octa | Asal di Octa Full Version | Yang Dipotong |
|---|---|---|
| `references/premise-sharpening.md` | `frameworks/premise-engine.md` | Dipotong: cara menemukan twist (4 metode), cara menguji premise (6 tes), dari premise ke konsep (7 tahap). Dipertahankan: 7 jenis twist + prinsip "Familiar + Twist" |
| `references/big-idea-to-content.md` | Subset dari Bab 08 + Bab 09 playbook + `frameworks/content-ideation-system.md` | Dipotong: triangulasi 3 sumber konten (Big Idea Layer + Brand World + Audience Reality), arsitektur 7 layer per ide, content calendar logic. Dipertahankan: 5 role konten + format hint per role + distribusi 5 ide |

### File yang Eksklusif Mini Octa (2 file)

| File Mini Octa | Status |
|---|---|
| `references/quick-audit-checklist.md` | Self-contained, dirancang khusus untuk Capability 3. Inspirasi dari Bab 10 playbook + Appendix E, tetapi struktur 3 lens + 14 issue umum dirancang ulang khusus untuk Mini Octa |
| `references/upselling-bridges.md` | Self-contained, dirancang khusus untuk Mode 4 Bridging Mini Octa. Tidak ada padanan langsung di Octa full version, karena Octa full version tidak melakukan upselling ke versi yang lebih tinggi |

### File yang Dipangkas Penuh dari Octa Full Version (Tidak Ada di Mini Octa)

**Dari frameworks Octa (24 file dipotong):**
- absurdity-spectrum, audience-archetype-system, brand-integration-playbook
- campaign-launch-brand-world, combinatorial-creativity, competitive-creative-mapping
- constraint-as-catalyst, content-ideation-system, creative-deconstruction
- creative-elevation-ladder, creative-risk-assessment, creative-scoring-rubric
- creative-tension-framework, experience-design-principles, field-immersion-human-truth
- first-principles-creative, hook-retention-mechanics, inversion-thinking
- lateral-thinking-toolkit, narrative-architecture, platform-native-thinking
- post-mortem-learning-loop, reframing-framework

**Alasan dipangkas:** Framework di atas dipakai untuk mode kerja Octa yang **out of scope Mini Octa** (campaign building, brand world, narrative architecture, pattern breaking, dst). Mini Octa cuma cover 3 capability sederhana, jadi semua framework ini tidak diperlukan.

**Dari references Octa (4 referensi besar + 17 studi kasus dipotong):**
- case-pattern-library, psychology-mechanics
- ref-arsitektur-konten-viral, ref-human-centric-beyond-advertising, ref-modern-campaign-mastery
- 17 file studi kasus (sk-01-05 sampai sk-81-82)

**Alasan dipangkas:** Studi kasus dan referensi besar dipakai Octa full version untuk inspire dan analisis pattern lintas kategori. Mini Octa tidak masuk ke level analisis ini.

**Dari standards Octa (9 dari 10 standards dipotong, 1 yang di-copy):**
- anti-safe-rules, standar-arsitektur-ide, standar-campaign
- standar-creative-output, standar-deskripsi-konten-kreatif
- standar-pattern-breaking, standar-penulisan-insight-kreatif
- standar-rekomendasi-kreatif, standar-tone-adaptasi

**Alasan dipangkas:** Standar di atas mengatur output Octa full version yang scope-nya jauh lebih luas (campaign deck, creative brief deliverable, arsitektur ide 7 layer, dst). Mini Octa output cuma chat markdown ringan, jadi standar yang relevan cuma humanize writing.

---

## Apa yang Dijaga Konsisten antara Mini Octa dan Octa Full Version

Walaupun scope Mini Octa jauh lebih sempit, ada 3 hal yang **wajib konsisten** dengan Octa full version supaya identitas brand AI tetap kohesif:

1. **Humanize writing protocol.** File `standards/humanize-writing-guide.md` di-copy persis. Zero tolerance em dash dan antitesis tetap berlaku.

2. **Karakter dan tone.** Mini Octa inherit creative-sharp + provocative tapi konstruktif dari Octa full version. Versi ringkas, tidak push-back panjang, tetapi DNA tone-nya sama.

3. **Naming dan persona.** Mini Octa menyebut nama "Mini Octa" secara natural, mengikuti pola Octa full version yang menyebut "Octa". User yang familiar dengan Octa full version langsung connect ke Mini Octa karena cara bicaranya senada.

---

## Apa yang Berbeda Tegasnya antara Mini Octa dan Octa Full Version

| Dimensi | Mini Octa | Octa Full Version |
|---|---|---|
| Jumlah capability | 3 capability sempit + 1 mode bridging | 19 mode kerja luas |
| Onboarding | 3-4 pertanyaan ringan per capability | Brand Profile lengkap (10+ parameter) |
| Output depth | 1 layar chat per capability + bridging | Arsitektur 7 layer, campaign deck, creative brief |
| Iteration | One-shot per capability | Iteratif konsultatif, ping-pong dialog |
| Format deliverable | Chat markdown saja | Bisa generate file deliverable |
| Konteks adjustment | Generic dengan hint | Deep adjustment per industri/role/fase |
| Cross-capability flow | 3 capability berdiri sendiri | 19 mode bisa flow bebas dalam 1 sesi |
| Bridging ke produk lain | Wajib bridging ke Octa full version di setiap output | Tidak ada bridging ke produk lain |
| Pricing | Bonus, gratis untuk pembeli playbook | Produk berbayar terpisah dengan akses di `https://nakama-creative-lab.myscalev.com/octa-ai` |

Pemisahan tegas ini menjaga Mini Octa berfungsi sebagai pintu masuk yang berguna tanpa kanibalisasi penjualan Octa full version. Sebaliknya, Mini Octa **aktif mengarahkan** pembeli playbook yang sudah outgrow scope-nya ke Octa full version melalui flow consultative bridging yang elegan.
