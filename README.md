# GHX VOICE STUDIO

**Advanced AI Voice Studio** by **GHX Studio** — Voice Cloning & Text-to-Speech in 600+ languages.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GHX-STUDIO-786/GHX-Voice-Studio-/blob/main/GHX_VOICE_STUDIO.ipynb)

## Access control

GHX VOICE STUDIO now uses the **GHX Cloudflare license server**. Google Sheets and the old Apps Script are no longer used by the active notebook.

- Owner dashboard: https://ghx-voice-studio-server.autoflow-ghx.workers.dev/admin
- License endpoint: https://ghx-voice-studio-server.autoflow-ghx.workers.dev/api/access
- Client access is matched by the Google account email.
- The Owner adds, edits, suspends, renews, or deletes subscriptions from the dashboard.
- Global Access can disable or re-enable service access.
- An empty expiry means no expiry date; expired or inactive clients are denied.

## Quick Start (Users)

1. Open the notebook using the Colab link above.
2. Select **Runtime → Change runtime type → T4 GPU** and save.
3. In **Step 1 — Verify Your Access**, enter the Gmail registered by GHX Studio and run the cell.
4. Sign in to Colab with that same Google account and approve account verification.
5. When **ACCESS GRANTED** appears, run **Step 2 — Launch GHX VOICE STUDIO**.
6. Wait for the public Gradio link and open the studio.

## Owner workflow

1. Open the [GHX VOICE STUDIO Admin Dashboard](https://ghx-voice-studio-server.autoflow-ghx.workers.dev/admin).
2. Sign in with the Owner account.
3. Add a client using their Google email, plan, optional expiry date, and notes.
4. Use Edit to change the plan/expiry or deactivate the client. Use Delete only to permanently remove the client.
5. Keep Global Access ON for normal service operation.

## Features

| Feature | Detail |
|---|---|
| Text to Speech | 600+ languages, voice design presets |
| Voice Cloning | 3–10 sec reference audio, zero-shot |
| Save Voice | Save cloned voices and reuse them |
| Subtitles | Optional SRT generation |
| Output | 320 kbps MP3 download |
| Access control | Cloudflare Worker + D1 admin dashboard |

## Requirements

- A Google account approved by GHX Studio.
- Google Colab with an NVIDIA GPU runtime (T4 recommended).

## Support

WhatsApp: [0341-4657696](https://wa.me/923414657696)

## Repository files

- `GHX_VOICE_STUDIO.ipynb` — main Colab notebook.
- `README.md` — current setup and owner instructions.
- `GHX_Access_Control_AppsScript.gs` and `GHX_Sheet_Template_README.txt` — legacy Google Sheets reference files only; they are not used by the active notebook.

---

**Developed by GHX Studio**. Only clone voices you have permission to use.
