# Daily English Coach — MVP v1.0

## Included
- Mobile-first daily dashboard
- 30-minute mixed-mode session checklist
- Three starter roleplays: pharma project update, PK accumulation, workplace small talk
- Useful expressions, sample spoken lines, model answers and reflection prompts
- Text entry for spoken answers (use iPhone keyboard dictation)
- System text-to-speech where supported
- Local progress, saved expressions and personal error notes
- PWA manifest and service worker for home-screen installation/offline shell

## Important limitations
This first version does not include a live AI conversation backend, automatic speech recognition, pronunciation scoring, or cloud sync. The review prompts are self-review scaffolding, not AI grading. Progress is stored in the browser on the current device.

## Deploy to iPhone
A PWA must be served from HTTPS to install reliably:
1. Upload the contents of this folder to a static HTTPS host (e.g. GitHub Pages or another host you control).
2. Open the deployed URL in Safari on iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Launch from the new home-screen icon.

Opening index.html directly from Files is fine for preview, but does not provide full PWA installation/offline service-worker behavior.

## Content and references
The roleplays are original practice scenarios informed by public professional guidance; they are not quotations or substitutes for regulatory advice.
- FDA Exposure-Response Relationships: https://www.fda.gov/regulatory-information/search-fda-guidance-documents/exposure-response-relationships-study-design-data-analysis-and-regulatory-applications
- ICH E4 / FDA Dose-Response: https://www.fda.gov/regulatory-information/search-fda-guidance-documents/e4-dose-response-information-support-drug-registration
- ICH M12 / FDA Drug Interaction Studies: https://www.fda.gov/regulatory-information/search-fda-guidance-documents/m12-drug-interaction-studies
- Establishing Good Practices for Exposure–Response Analysis: https://pmc.ncbi.nlm.nih.gov/articles/PMC4625861/
