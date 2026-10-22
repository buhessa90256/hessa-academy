# Hessa Academy · أكاديمية حصة

An Arabic/English learning garden built for iPad, Apple Pencil, touch, and desktop browsers. No build step, accounts, analytics, or backend. Public source contains learning activities only, never the source evaluation or private child records.

## Activities

- Arabic alphabet, English upper/lowercase letters, name writing, pencil patterns; visual tracing with hide-model practice.
- Arabic short vowels, English short vowels, three-letter blending, listen-and-write practice.
- Initial letter/picture matching, beginner sight words, a story with comprehension questions.
- Ordered listening games, cooperation and everyday problem solving.
- Drawing prompts with save-image, pressure-sensitive pen strokes, undo, and a Pencil-only option that ignores fingers.
- Al-Fatiha for supervised reading, a hadith about guiding others to good, mealtime manners, UAE facts and quizzes.

Stars reward practice and participation, **not mastery**. A grown-up must assess grip, stroke order, letter formation, reading and pronunciation. Browser speech synthesis depends on installed Arabic/English voices. Quran text is for supervised reading; use a trusted reciter for tajweed rather than synthetic speech.

## Run and publish

Serve this directory over HTTP, e.g. `python -m http.server 8080`. GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

Live site: https://buhessa90256.github.io/hessa-academy/

All resources and service-worker scope are relative to this repository path. No custom domain, root site, or other repository is needed or changed.

## iPad

Open in Safari, Share → Add to Home Screen. Visit once online before offline use. Activities are cached; optional external references and uninstalled voices need a connection. Enable **Pencil only** to ignore palm and finger touches on the drawing canvas. Drawings can be exported as PNG. Progress is stored only in localStorage in the current browser; the parent guide exports it as JSON. Clearing site data removes it. Browser testing cannot certify physical Apple Pencil or iPad Safari hardware behavior.

## Content sources

- Al-Fatiha: https://quran.com/1
- Hadith: Sahih Muslim 1893a, https://sunnah.com/muslim:1893a (English explanation simplified for children).
- UAE government: https://u.ae/en/about-the-uae (political facts checked 2026-10-22).

No child evaluation photo, assessment scores, private attachments, tokens or credentials belong in this repository.
