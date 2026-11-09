<div align="center">

# Nuvexel AI Pro 1.0

**Offline AI cut-out, HD upscaling and clean vector for Windows 10 / 11**

Clean cut-outs, crisp Bézier vectors and laser-ready files, made on your own PC.
No uploads, no subscription, no credits.

[Website](https://nuvexelai.com) · [Download](#2-download-and-install) · [Pricing](https://nuvexelai.com/#pricing) · [Support](mailto:support@nuvexelai.com) · [Feedback and ideas](#7-roadmap-ideas-and-feedback)

</div>

---

## Contents

1. [What Nuvexel AI Pro is](#1-what-nuvexel-ai-pro-is)
2. [Download and install](#2-download-and-install)
3. [Free trial and license keys](#3-free-trial-and-license-keys)
4. [The five steps, tool by tool](#4-the-five-steps-tool-by-tool)
   - [① HD: sharpen and enlarge](#-hd-sharpen-and-enlarge)
   - [② Crop: frame, rotate, shape](#-crop-frame-rotate-shape)
   - [③ Background: AI cut-out and holes](#-background-ai-cut-out-and-holes)
   - [④ Vector: hybrid, SVG or layers](#-vector-hybrid-svg-or-layers)
   - [⑤ Save: every format](#-save-every-format)
   - [Canvas, views and shortcuts](#canvas-views-and-shortcuts)
5. [Recipes: which settings for which job](#5-recipes-which-settings-for-which-job)
6. [FAQ and troubleshooting](#6-faq-and-troubleshooting)
7. [Roadmap, ideas and feedback](#7-roadmap-ideas-and-feedback)
8. [Privacy, licenses and credits](#8-privacy-licenses-and-credits)

---

## 1. What Nuvexel AI Pro is

Nuvexel AI Pro is a desktop studio for Windows that turns a photo, a sketch or a piece of game art into a clean,
usable file. Five guided steps sharpen the picture, crop it, remove the background and the holes inside the object,
turn it into a vector and save it as a transparent PNG, a clean SVG, a print PDF or a laser-ready DXF.

| | |
|---|---|
| **100% offline** | Background removal, HD upscaling and vectorization run on your own processor. Your pictures never leave your PC. |
| **No subscription** | Every plan is one payment. Nothing renews and nothing is charged again. |
| **No graphics card needed** | The AI models run on any 64-bit CPU, in the background, so other programs stay responsive. |
| **For real work** | Logos, mascots, stickers, tattoo stencils, jewellery, item sheets, game sprites, laser and CNC jobs. |

**Best results:** 2D illustrations, game sprites and item sheets, logos, emblems, line art, stickers and objects on a
clean or contrasting background. 3D renders, busy photos and crowded scenes may need a few clicks with the manual
tools, and for photographic shading the **Clean object (HD hybrid)** mode keeps the real pixels inside a vector outline.

---

## 2. Download and install

Both files are in the [latest release](../../releases/latest). They contain the same program.

| File | For whom | Size |
|---|---|---|
| `Nuvexel_AI_Pro_v1.0_Setup.exe` | **Recommended.** Installs for your Windows user, adds a Start menu shortcut and an uninstaller. No administrator rights needed. | ≈ 205 MB |
| `Nuvexel_AI_Pro_v1.0_Portable.zip` | Unzip anywhere (also a USB stick) and run `NuvexelAI.exe`. Nothing is installed. | ≈ 205 MB |

**System requirements:** Windows 10 or 11, 64-bit · 4 GB RAM (8 GB recommended) · 1 GB free disk space · any 64-bit
processor · no graphics card needed.

### Check the file (optional)

Compare the SHA-256 of the file you downloaded with these values (PowerShell: `Get-FileHash <file>`):

| File | SHA-256 |
|---|---|
| `Nuvexel_AI_Pro_v1.0_Setup.exe` | `db42c4a5f04ed6bb35c76d5b0661c4228ceb4f0ed4b512892f7f5c684ca63b20` |
| `Nuvexel_AI_Pro_v1.0_Portable.zip` | `41d15037b46844dd59731390a337184727221b47baed11830ed77eb9015919ab` |

### The blue "Windows protected your PC" window

The program is new and not yet signed with a paid code-signing certificate, so on the first start Windows SmartScreen
may show a blue window. This is normal for new independent software.

1. Click **More info**.
2. Click **Run anyway**.
3. Follow the installer (about one minute), or start `NuvexelAI.exe` from the unzipped folder.

Windows asks only once per file.

---

## 3. Free trial and license keys

### Free trial

- **3 complete pictures without a watermark.** Each counted picture can be saved clean as often as you like, in any
  format.
- Every tool and all five steps are unlocked.
- Trial export goes up to 2× / 2048 px. 4× and 4K output, batch "Save all", Watch Folder and the tray clean-up are Pro.
- After the 3 pictures, raster exports carry a DEMO watermark, and SVG, PDF, EPS, laser / CNC, normal maps and GIF
  need a key.
- No card, no account, no time limit.

### Plans

| Plan | Price | Runs for |
|---|---|---|
| 30-Day Pass | $7.99 | 30 days **from activation** |
| 1-Year Pass | $39 | 365 days **from activation**, all updates during the year |
| Lifetime Pro | $59 | No end date, all 1.x updates |

All paid plans unlock exactly the same full program. They differ only in how long the key works. Every plan is a
one-time payment with no auto-renewal. Commercial use of your results is allowed on every plan. A personal license
covers up to 3 of your own PCs. Buy on the [website](https://nuvexelai.com/#pricing) (checkout by Payhip, PayPal).
Payhip may add the VAT or sales tax of your country at checkout where the law requires it.

### Activate your key

1. After payment Payhip shows your key on the order page and sends it by e-mail. It starts with `NV3`.
2. In the program click **Trial** at the top of the window (or the gear menu → **PRO license**).
3. Paste the key and press **Activate**.

There is nothing to reinstall: the trial and Pro are the same program. Activation works offline. A 30-day or 1-year
pass starts when you activate the key, not when you pay. When it ends, the program goes back to the trial until you
enter a new key.

---

## 4. The five steps, tool by tool

The program opens on a start screen: drop pictures into the window, paste one from the clipboard (Ctrl+V), or press
**Add** (Ctrl+O). Open: PNG, JPG, WEBP, BMP, TIFF, GIF, ICO, AVIF, PSD, TGA, HEIC (with the free Windows HEIF codec)
and PDF with embedded pictures.

The numbered buttons at the top (**1 · HD**, **2 · Crop**, **3 · Background**, **4 · Vector**, **5 · Save**) move between
the steps; **Back** and **Next** do the same. Every change is a history step: Ctrl+Z undoes (25 steps), Ctrl+Y redoes.
**Guide** (top bar) lists every button of the current screen with its explanation.

### ① HD: sharpen and enlarge

| Control | What it does |
|---|---|
| **Make it HD (AI)** | The Real-ESRGAN network enlarges the picture and sharpens edges and fine details. Runs on your computer, offline. |
| **Turn HD off** | Back to the original size (a history step). |
| **Photo / Artwork** | Model choice. Photo: natural texture for photos, metal, jewellery and tattoos. Artwork: clean lines and fills for illustrations, logos and art. |
| **1× / ×2 / ×4** | 1×: neural sharpening without upscaling (for large pictures). ×2 and ×4 enlarge; ×4 is for small pictures. |
| **AI strength** | 100%: fully the network. Lower: softer and closer to the original. |
| **Sharpness** | Sharpens facets and engraving, on edges only (no noise on flat areas). |
| **Denoise** | Removes grain and JPEG blocks; edges stay. |
| **Hold to compare** | Shows the original while you hold the button. |

**Colour & filters:** Original, B&W ink (crisp black and white: logos vectorize cleaner), Cyber neon, Vintage, Pop
contrast, Poster (flat colours, cleaner vector layers), plus Contrast, Saturation and Hue sliders and **Reset filters**.

### ② Crop: frame, rotate, shape

| Control | What it does |
|---|---|
| **Fit to object (AI)** | One click puts the frame exactly around the main object with a 4% margin (tattoo, pendant, logo on a photo). |
| **Whole picture / Free / 1:1 / 4:3 / 16:9** | Frame presets: icons and avatars (1:1), covers and video (16:9). |
| **90° / Mirror horizontally / Mirror vertically** | Rotate and flip (history steps). |
| **Straighten** | Fine rotation −15°…+15° for a tilted horizon. Double-click the label to reset. |
| **Cut-out shape** | Rectangle, Rounded corners, Circle / oval (stickers, coins, avatars), Hexagon (game tiles), Diamond, Shield / emblem; **Corner radius**. |
| **Crop to frame** | Applies the frame (Enter). Ctrl+Z to undo. |
| **Exact size, px** | Resize with Lanczos interpolation; **Keep proportions**; presets for a long side of 512, 1024 and 2048 px. |
| **Margins / Add margins** | A transparent border so the object does not touch the edges. |
| **HD for the cropped frame** | Runs Real-ESRGAN on the cropped frame only: faster, and the object itself gets sharper. |

### ③ Background: AI cut-out and holes

| Control | What it does |
|---|---|
| **Remove background (AI)** | Removes the outer background, shadows and closed holes inside the object (star triangles, chain links, letter holes). A tattoo on skin keeps only the ink. |
| **Auto-remove background on entry** | On: the background is removed as soon as you open step ③. Off: the picture opens as it is. |
| **Restore background** | Undoes the removal and all background edits of this screen (one history step). |
| **Find more holes** | Searches again for closed background windows inside the object. |
| **Polish & clean up** | After manual cleaning: removes crumbs and semi-transparent dirt, closes pinholes and makes one even, thin edge. |
| **Edge trim** | Moves the edge of the whole cut-out: right pulls it inward (the light or grey fringe disappears, the edge colour comes from the object), left lets it grow. Live. |
| **Edge smoothing** | Evens out jaggies of the automatic cut. Live. |
| **Click the main object** | For a full-frame scene: click the main object to keep only it (MobileSAM). |
| **Select all objects** | MobileSAM + ISNet find the characters and objects; click one on the canvas to remove or add it, then **Keep selected**. |
| **Cut the collage into frames** | When straight seams between photos are found, each frame opens as its own picture. |
| **Keep background, go to vector** | Skips background removal; the vector is built from the whole picture. |

**Manual tools** (keyboard letter in brackets):

| Tool | What it does |
|---|---|
| **Hole (W)** | Hover to see in coral what will go, click to cut. Stops at the object edge. **Sensitivity**, **Protect object edge**, **Hole edge** and **Cut all similar holes** (finds every identical hole with the same threshold). |
| **Eraser (E)** | Erase by hand. Shift+click: straight line. Alt: restore brush. `[` `]`: size. |
| **Restore (B)** | Brings back the original. Shift+click: straight line. Alt: eraser. |
| **Object (O)** | Click an item of a scene to keep only it. |
| **Selection** | Select, + Add (Shift+click), − Subtract (Ctrl+click), **Selection brush** with **Snap to edges**, **Border** (−15…+15 px), **Keep selected / Remove selected / Deselect**; scope **Detail / Object / Whole figure**. |
| **Brush size, Edge hardness** | For the eraser and the restore brush. |

### ④ Vector: hybrid, SVG or layers

Choose the result type:

| Result | Best for |
|---|---|
| **Clean object (HD hybrid)** | 100% of the original's detail (native pixels) inside a vector silhouette with detail outlines. Best for textured art, ships, photos and metal. Nothing is lost. |
| **SVG vector (smooth Bézier curves)** | Scalable Bézier curves: colour zones plus a crisp ink and detail layer. A defect checker compares the lines with the original, so no detail is lost. |
| **Split into layers** | A scene becomes 5–12 meaningful layers (characters, houses, trees) plus the background; an item sheet becomes separate files; one object gets every letter or detail as its own path. |

The program analyses the picture (illustration, logo, photo, ink outline, number of colours) and picks the settings
automatically; the analysis button explains what it found and restores the automatic choice with one click.

| Control | What it does |
|---|---|
| **Light / Medium / Max** | Detail level: Light gives the fewest nodes (Figma, Illustrator, the web); Max is the default. |
| **Softer / Auto / Sharper** | Corner style: softer roundings for organic and hand-drawn shapes; sharper corners for logos, type and engraving; Auto decides from the picture. |
| **Silhouette / Major parts / All** | How much is outlined: only the silhouette and see-through holes (cutting, engraving), the major parts (letters, pieces), or every small detail. |
| **Simplify nodes** | Fewer nodes, same shape: smooth runs merge into one Bézier curve (35% ≈ 1 px is the default). |
| **Rebuild vector** | Rebuilds from the current image with all edits. |
| **Text on the object** | Places a chosen inscription onto the details of the current image. |
| **Edit tools** | **Bézier nodes (A):** drag nodes and handles, Alt+click switches corner / smooth, Del deletes. **Detail (V):** select and move a part. **Fill (G)** with a colour or transparency, **Eyedropper (I)**, **Cut part** with a line, **Brush (B)** and **Eraser (E)** for pixels, **Add by click** for a missed letter or detail. |
| **Sticker border (Die-Cut)** | An even border around the silhouette for printed die-cut stickers, Telegram stickers and UI icons; in SVG it is a separate path under the artwork. |
| **Details: ZIP / Download all layers** | An SVG with every part on its own layer, plus a ZIP with a separate SVG and PNG of each part (and a sprite atlas for a sheet). |

### ⑤ Save: every format

| Control | What it does |
|---|---|
| **Compare / Side by side** | Before / after curtain, or the original and the result side by side. |
| **What to download: Picture / Details / All** | The whole picture; only the parts and layers (each as PNG + SVG in a ZIP); or both. |
| **Main download button** | Follows the result type: Hybrid → PNG, Vector → SVG, Layers → ZIP. The standard Windows "Save As" window opens with the file name filled in. |
| **Copy** | Copies a PNG to the clipboard (Figma, Photoshop, messengers). |
| **Other formats** | WEBP, PDF (vector document for print), EPS (print vector), JPG (solid background), ICO (Windows icon 16–256 px), ZIP (a bundle you choose: PNG, SVG, parts folder, PDF, EPS, WEBP, JPG, ICO, DXF, game sprite, normal map). |
| **Laser / CNC (.dxf)** | DXF R12 + laser SVG: closed contours, red cut and blue engrave layers, size in millimetres, optional holding bridges that join loose parts (the dot of an "i", separate letters) to the body, and halftone. |
| **Unity / Godot (.png)** | Sprite PNG + 2D collider (low-vertex polygon with holes) + Unity `.meta` and Godot `.tscn`, pivot and pixels-per-unit. |
| **Normal map** | Normal map, 16-bit height map and a lit preview for 2D lighting. |
| **GIF animation** | A before / after curtain GIF (24 frames, 680 px) for portfolios and posts. |
| **Size, background and folder…** | The export window (Ctrl+S): exact size (0.5× … 4×, or W × H), background (transparent, white, custom colour) and destination folder. |
| **Compare 4 variants** | Crisp hybrid · Clean vector (SVG) · Light SVG · Stamp / Laser side by side with synced zoom; click the best one to use it. |

### Canvas, views and shortcuts

| Control | What it does |
|---|---|
| **Before / After** (Alt+1) | Drag the line: original on the left, result on the right. |
| **Result** (Alt+2) | The clean finished result, exactly as in the file. |
| **Outlines** (Alt+3) | The real vector curves and anchor points over the result: square = sharp corner, circle = smooth node, triangle = a line flowing into a curve. |
| **X-ray** | Alpha X-ray: transparent is black, the object dark green, semi-transparent pixels and leftover specks bright pink. |
| **Backdrops** | Transparency checkerboard, Black velvet (silver and gold), White paper, Neon (leftover background shows at once). |
| **Canvas lock (L)** | The mouse wheel does not zoom and a stroke next to the picture does not move the canvas. Zoom: Ctrl + wheel. Pan: Space + drag or the middle mouse button. |
| **Reset to original** (Ctrl+R) | The picture as it was opened; also a history step. |
| **Clear canvas** (Ctrl+W) | Closes all pictures and returns to the start screen. |
| **Settings** (Ctrl+,) | Theme, interface language (16 languages), folders, tray, optional online AI. |

---

## 5. Recipes: which settings for which job

| Job | Suggested path |
|---|---|
| **Logo or emblem for a website** | ② Fit to object → ③ Remove background → ④ SVG vector, Sharper, Major parts → ⑤ SVG. |
| **Mascot or illustration** | ① HD (Artwork) if the picture is small → ③ Remove background → ④ SVG vector, Auto, Max → ⑤ SVG or PDF. |
| **Photo of jewellery or metal** | ① HD (Photo) → ② Fit to object → ③ Remove background, Black velvet backdrop to check → ④ Clean object (HD hybrid) → ⑤ PNG. |
| **Laser engraving or CNC** | ③ Remove background → ④ SVG vector, Silhouette or Major parts → ⑤ Laser / CNC, size in millimetres, bridges for loose parts. |
| **Sticker** | ② Circle or Rounded corners shape → ③ Remove background → ④ Sticker border (Die-Cut) → ⑤ PNG and SVG. |
| **Game item sheet** | ③ Remove background → ④ Split into layers (every item becomes its own file) → ⑤ Unity / Godot, or ZIP with the parts folder. |
| **Tattoo stencil** | ① B&W ink filter → ③ Remove background (skin goes, ink stays) → ④ SVG vector, Major parts → ⑤ SVG or PDF. |

---

## 6. FAQ and troubleshooting

**Does it upload my images anywhere?**
No. Background removal, HD and vectorization all run on your PC. The optional online AI is off by default and works
only with your own API key (stored encrypted by Windows on your PC); when you turn it on, a copy of the picture no
larger than 768 px is sent to the provider you chose.

**Do I need a powerful PC or a graphics card?**
No graphics card is needed. 8 GB of RAM is recommended for big pictures and scenes; 4 GB works for normal pictures.

**The program is slow on a big picture.**
Long jobs run in the background with a progress indicator. For pictures above 4000 px, crop first (step ②) or use HD
1× instead of ×4.

**Windows Defender or SmartScreen warns me.**
See [the blue window](#the-blue-windows-protected-your-pc-window). The files are not signed with a paid certificate
yet. You can compare the SHA-256 with the values above.

**I activated a 30-day key and it shows Trial again.**
The pass has ended (30 days from activation). Enter a new key, or contact support if the dates look wrong.

**On how many computers can I use one key?**
Up to 3 of your own PCs.

**Will photos of shiny metal look the same in pure SVG?**
In pure SVG, reflections become a gradient and 2–3 tones, because that is how vector graphics work. To keep every
photo detail choose **Clean object (HD hybrid)**.

**How do I contact support?**
E-mail [support@nuvexelai.com](mailto:support@nuvexelai.com), or in the program: gear menu → **Contact support**. It
opens an e-mail with your system details, never your license key or your pictures. Please never post your key in
public (issues, forums, screenshots).

**Refunds**
14-day refund policy: a full refund if the key was never activated, or if a technical problem cannot be fixed within
7 days of your first message. Details: [nuvexelai.com/refund.html](https://nuvexelai.com/refund.html).

---

## 7. Roadmap, ideas and feedback

Planned for the 1.x line (one-time-payment customers get all 1.x updates):

- Online activation server: key revocation after a refund and the 3-PC limit enforced.
- Code-signed installer, so the SmartScreen window disappears.
- Finer pure-SVG vectors for very detailed scenes within the node budget.
- Smoother metal shading in pure SVG (more than 2–3 tones).
- An updated embedded Python runtime.

**Tell us what you need.** Which format, tool or kind of picture should come next? Write to
[support@nuvexelai.com](mailto:support@nuvexelai.com) with the subject "Idea", or start a topic in
[Discussions](../../discussions) if it is open. Sample pictures that came out badly are the most useful feedback,
but send only pictures you have the right to share.

---

## 8. Privacy, licenses and credits

- [Privacy policy](https://nuvexelai.com/privacy.html) · [Terms and EULA](https://nuvexelai.com/terms.html) ·
  [Refund policy](https://nuvexelai.com/refund.html)
- The program has no telemetry and no analytics. The website uses no cookies and no trackers.
- Third-party components (Qt for Python under LGPL-3.0, ONNX Runtime, OpenCV, NumPy, Pillow, ReportLab, svglib and
  others) and the AI models (ISNet / DIS and MobileSAM under Apache-2.0, Real-ESRGAN under BSD-3-Clause) are listed
  with their licenses in `THIRD_PARTY_NOTICES.txt` inside the program folder.

© 2026 Nuvexel AI Pro · Operated by NIKOSART (Exempt Dealer No. 209531680, Israel).
This repository hosts the release files and the user guide; the program itself is closed source.
