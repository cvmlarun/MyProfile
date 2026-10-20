# YuktYantra & Arun Patil Labs Website Bundle

A clean, self-contained multi-page web publication for **YuktYantra** (a unit of **Arun Patil Labs**).

## File Directory & Purpose

| File | Purpose | Description |
| :--- | :--- | :--- |
| `index.html` | Flagship Homepage | Main landing page for YuktYantra: Applied AI systems overview, core programmes, and technology architecture. |
| `internships.html` | Academic Fellowships | Research internship and capstone portal for B.Tech & B.Sc Horticulture students (3 tracks, applicant matrix, IP & safety terms). |
| `agrotech.html` | Farm AI & Viticulture | Precision agriculture field study in Sindagi taluk: 51-row block explorer, 4-phase protocol, and camera cart specifications. |
| `voice-ai.html` | Duplex Voice Lab | High-throughput speech-to-speech inference research, 80ms live frame animation, and GPU concurrency calculator. |
| `physical-ai.html` | Physical AI & Manipulation | Procedural grapevine pruning decision model, 10 domestic mobile manipulation challenges, and DPDP consent architecture. |
| `arunpatillabs-index.html` | Consulting Profile | Preserved standalone personal consulting website for Arun Patil Labs (LLM inference, speculative decoding, computer vision). |
| `CHANGELOG.md` | Revision Log | Complete audit of all pre-publishing content corrections and mobile responsiveness code fixes. |

## Key Features & Design System
- **Self-Contained**: Zero external image or JavaScript framework dependencies; all graphics use embedded inline SVG and vanilla HTML5/Canvas/CSS3.
- **Typography**: Uses modern web typography via Google Fonts (Bricolage Grotesque, Inter, JetBrains Mono).
- **Responsive**: Fully responsive CSS layouts with fluid typography and breakpoints optimized for desktop, tablet, and mobile browsers.

## How to Deploy / Push to Git
1. Extract all files into your repository root or target web server folder (`public_html`, `docs/`, or web root).
2. For **GitHub Pages**:
   - Push files to your repository `main` branch.
   - Go to **Settings > Pages** and set source to deploy from the root (`/`) directory.
3. For local testing:
   - Double-click any `.html` file to preview directly in your web browser, or run:
     ```bash
     python3 -m http.server 8000
     ```
   - Open `http://localhost:8000` in your browser.
