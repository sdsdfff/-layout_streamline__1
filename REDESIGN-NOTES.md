# Streamline — October 2026 redesign

Main page rebuilt into eight sections. Existing 16 auxiliary HTML pages and portfolio assets retained. Archived pages share the new palette via theme.css.

Verified source: https://streamline-msk.com/index.php/contacts (search index): office, three phones, info@streamline-msk.com. Events page reports the events practice since 2006. No invented team profiles, tariff rules, legal documents or partnership claims.

The previous source has only an external online-event calculator link, no calculator implementation or rates. New project estimator builds a brief, allows local download, and opens an email draft; it does not send messages. Prices require company-approved rates.

Outstanding company inputs: staff photos/names, official partner logo assets and relationship descriptions, high-resolution portfolio originals, approved legal documents and pricing rules. Current team tab describes professional disciplines; partner tab identifies portfolio brands with links to corresponding cases.

QA: browser desktop inspected; calculator opens, selections update, service tabs, case switching, photo switching and partner tab verified. Yandex map renders. Local links, anchors, images and JavaScript syntax checked. Mobile CSS implemented; device viewport testing not available in browser API.

Typography update: locally hosted Unbounded variable (SIL OFL) for headings and buttons, following supplied geometric wide-sans reference. Body, navigation and input typography unchanged.

Atmosphere update: warmer paper/sage backgrounds, faint tiled grain, seven restrained inline SVG contour accents; headings, body content and functionality preserved. Decorative SVGs are hidden from accessibility tree and ignore pointer input.

Controls update: rounded capsule CTAs, subtle milk/sage cloud-like gradients, softened service/portfolio tabs, partner buttons and form controls. Interaction code unchanged; focus and reduced-motion styles retained.

Screenshot-directed cleanup: removed hero sketch sheet/grid; rounded photograph frame. Removed decorative section, service, team and case-label numbering. Added meaningful service/team SVG symbols and dot-based section navigation with accessible names. Sequential process and gallery counts retain plain numbers. Browser checked hero, service switching and matching icon; no horizontal overflow.

## Photo and map update
Embedded Google Maps with route and fallback links. Added three AI editorial concepts (hero, design process, event space), responsive WebP assets and service illustration switching. Seven lead portfolio photographs have AI-restored alternatives, visibly labeled, with original/restore toggle; original archive remains unchanged. Small details in restorations may be reconstructed.

## 2026-10-27 focused refinement
Removed editable AI captions and restore toggle. Added 100+ projects / 10 years supplied by owner, with anchor to existing gallery and reduced-motion-aware reveal. Preserved actual olive palette (the request called it Petrol Teal). Audited 53 archival photos; re-encoded directly from supplied original JPEGs to WebP quality 94, added dimensions, decoding hints, restrained display contrast and limits on enlargement. Disabled generated restoration variants for documentary accuracy. Fine detail missing from 290px originals cannot be safely restored without higher-resolution source files. Main and case layouts checked at 390/768/1440 iframe widths; no horizontal document overflow. Local targets checked across 17 pages.

## 2026-10-27 portfolio and hero update
Removed metrics, unnamed pharmaceutical case, team tab, and service illustrations. Added requested adidas, Nike, Sportmaster partner names and updated phones. Full-width real-case hero with four manual slides, accessible controls and reduced-motion handling. Shared /projects/ collection contains all seven retained cases and 39 supplementary source photos; individual case pages expose all projects. Supplementary images use originals already optimized in WebP and native-scale lightbox; no generative upscaling because original details must remain faithful. Main and collection verified at 390/768/1440 widths without horizontal overflow; slider, catalog navigation and lightbox verified.

## Client-facing copy and photo presentation
Rewrote all seven result paragraphs without missing-metric/editorial caveats, using only existing source facts. Synced collection, detail pages and JSON. Added restrained SVG edge enhancement and contrast/saturation for project imagery and lightbox; source files and actual resolution unchanged. Verified result text and photo lightbox in browser.

## 2026-10-28 photo restoration and brands
Connected 46 enhanced project photos, including all hero slides, seven case covers and 39 supporting images. Original images are preserved. User explicitly authorized minor reconstruction; imagegen restored detail and compression, with visual review and three signage corrections. Responsive 640px WebP variants and lazy loading keep gallery transfers small; lightboxes use full resolution. Disabled redundant CSS sharpening. Renamed partners heading to “Бренды, с которыми мы работали.” and removed adidas, Nike, Sportmaster and “И многие другие” from that block. Previous client-facing copy cleanup is included.

## Contact options
Replaced calculator with tel links, callback form and mailto. Callback uses FormSubmit POST with CAPTCHA, honeypot, phone validation, consent and branded return page. Recipient vbabaeva733@gmail.com must activate FormSubmit email before reliable delivery. Updated visible email throughout pages. No service credentials stored.
