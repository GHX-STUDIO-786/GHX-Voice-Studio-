# GHX VOICE STUDIO

**AI Voice Generation & Voice Cloning** — Text-to-Speech, voice cloning, saved voice profiles, and subtitle export in 600+ languages.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GHX-STUDIO-786/GHX VOICE STUDIO/blob/main/GHX_VOICE_STUDIO.ipynb)
[![License](https://img.shields.io/badge/license-Private-red.svg)]()
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![Gradio](https://img.shields.io/badge/UI-Gradio-orange.svg)]()

---

## Features

| Feature | Detail |
|---------|--------|
| **Text to Speech** | 600+ languages and voice design presets |
| **Voice Cloning** | 3–10 second reference audio, zero-shot |
| **Saved Voices** | Save cloned voices and reuse them in Text to Speech |
| **Subtitles** | Optional SRT generation |
| **Audio Export** | MP3 download at up to 320 kbps |
| **Access Control** | Subscription access managed through Google Sheets |

## Quick Start

1. Open the [GHX VOICE STUDIO Colab notebook](https://colab.research.google.com/github/GHX-STUDIO-786/GHX VOICE STUDIO/blob/main/GHX_VOICE_STUDIO.ipynb).
2. Select **Runtime → Change runtime type → GPU (T4)** and save.
3. In **Step 1**, enter your registered Gmail and run the cell.
4. Wait for **Access Granted**.
5. Run **Step 2**. The first launch may take around 2–3 minutes.
6. Open the generated public `.gradio.live` link.

### Requirements

- A Gmail address approved by the owner in the access list.
- Google Colab with a GPU runtime.

## Support

- **WhatsApp:** [0341-4657696](https://wa.me/923414657696)
- **WhatsApp Channel:** [Follow GHX VOICE STUDIO](https://whatsapp.com/channel/0029VbA5Z6UCsU9KEtgmrN2m)

## Repository Files

```
GHX VOICE STUDIO/
├── GHX_VOICE_STUDIO.ipynb
├── GHX_Access_Control_AppsScript.gs
├── GHX_Sheet_Template_README.txt
└── README.md
```

## Access Management

1. Open the Google Sheet connected to the Apps Script access endpoint.
2. Add or update a customer row using these columns:

| Email | Plan | Expires | Active |
|-------|------|---------|--------|
| client@gmail.com | monthly | 2026-12-31 | YES |

3. The customer opens this repository's Colab notebook and signs in with the same approved Gmail address.

To disable a customer, set **Active** to `NO` or set **Expires** to a past date. The optional master switch in cell **F1** can be set to `OFF` to disable access for everyone.

### Apps Script Setup

- Deploy the Apps Script as a Web App.
- Set **Execute as: Me** and **Who has access: Anyone**.
- Keep the endpoint URL and access key configured consistently in the Apps Script and notebook.

## Responsible Use

Only clone voices you have permission to use. Unauthorized redistribution is not allowed.

---

**GHX VOICE STUDIO** · [WhatsApp Support](https://wa.me/923414657696)
