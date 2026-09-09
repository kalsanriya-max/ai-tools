# Quick AI Tools

## Run
1. Unzip the folder.
2. Open `index.html` in Chrome/Edge/Firefox.
3. For best PDF-module compatibility, use a simple local server:
   - VS Code: install Live Server and click "Go Live".
   - Or Python: `python -m http.server 8000`, then open `http://localhost:8000`.

## Included working browser tools
- Dark/light mode
- Responsive mobile navigation
- Tool search/filter
- PDF text extraction + basic extractive summary (PDF.js CDN)
- Text rewriting
- English/Hindi starter translation
- Local SVG image generator + download
- Simple uniform-background remover + PNG download
- Resume builder + browser print/save as PDF
- HTML presentation generator + download
- Toasts, modals, uploads and downloads

## Important
This package does not expose an OpenAI/Claude/Gemini API key in frontend code. A real cloud AI writer/image generator/chatbot needs a backend API and a secret API key. The included tools are designed to work without a paid API.

The PDF.js dependency is loaded from cdnjs, so PDF extraction needs internet access. Other local tools continue to work offline.
