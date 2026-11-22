# AGENTS.md — jonathanmccallum-th (Thai mirror of jonathanmccallum.com)

Thai mirror site. Same theme and design as the main site (Paper Light),
content translated into Thai, meaning-first. Repo: streamjonathan/jonathanmccallum-th.
Live (when approved): th.jonathanmccallum.com. Proof: jonathanmccallum-th.pages.dev.

## Mission

Mirror jonathanmccallum.com in Thai — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Thai site goes live on th.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: plain, warm, honest; short sentences; Jonathan speaks as ผม, the
  reader as คุณ; no preaching. Scene → reflection → question shape kept.
  God = พระเจ้า, Jesus = พระเยซู, Christ = พระคริสต์.
- Names (never vary): อัสลาน, นาร์เนีย, ลูซี่, ดิกอรี่, ทิเรียน, อาดัม / เอวา,
  เปโตร, แคร์ พาราเวล, แม่มดขาว. Book titles use the published Thai editions
  (สำนักพิมพ์ผีเสื้อ, แปลโดยสุมนา บุณยะรัตเวช): ตำนานแห่งนาร์เนีย,
  กำเนิดนาร์เนีย, อวสานการยุทธ์. The Great Divorce (การหย่าร้างครั้งยิ่งใหญ่)
  and The Space Trilogy (ไตรภาคอวกาศ) have NO published Thai edition — translated
  for this site, English kept in parentheses on first use.
- Bible verses: none of the 5 articles contains a direct Bible quotation, so no
  verse text was reproduced. The bread/water of life lines are Jonathan's
  paraphrase (echoing John 6:35 / 4:14) — ขนมปังแห่งชีวิต / น้ำแห่งชีวิต — never
  presented as quoted Scripture.
- No direct Lewis quotations appear either; none were invented.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
