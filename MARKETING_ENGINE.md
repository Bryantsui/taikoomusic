# Taikoo Music Studio — SEO + AIEO + Paid Ads Engine

## Budget: HK$1,000–2,000/month

---

## 1. SETUP CHECKLIST (Do These First)

### Google
- [ ] Create **Google Business Profile** at https://business.google.com
  - Business name: `Kitty Music Studio` (keep identical everywhere)
  - Category: `Music School` + `Piano Instructor`
  - Address: Your Kornhill address (must match website exactly)
  - Phone: Your WhatsApp number
  - Hours: Your teaching hours
  - Photos: Upload 5+ photos of your studio, piano, erhu
  - **Ask 3-5 existing parents to leave Google Reviews** (this is the #1 Local Pack ranking factor)

- [ ] Set up **Google Ads** at https://ads.google.com
  - Create a conversion action for "WhatsApp Click" (type: Website → Lead)
  - Copy the Conversion ID and Label into `index.html` (replace `AW-CONVERSION_ID/CONVERSION_LABEL`)

- [ ] Set up **Google Tag Manager** at https://tagmanager.google.com
  - Create a container, copy the `GTM-XXXXXXX` ID
  - Replace both instances of `GTM-XXXXXXX` in `index.html`
  - Inside GTM, add your **GA4** tag (free analytics)

- [ ] Set up **Google Search Console** at https://search.google.com/search-console
  - Verify kittylau.com
  - Submit sitemap: `https://www.kittylau.com/sitemap.xml`

### Meta (Facebook/Instagram)
- [ ] Create a **Meta Business Suite** at https://business.facebook.com
- [ ] Create a **Meta Pixel** at Events Manager → Data Sources → Add Pixel
  - Copy the Pixel ID, replace both `PIXEL_ID` instances in `index.html`
- [ ] Create a **Facebook Page** for "Kitty Music Studio 太古音樂教室"
- [ ] Connect your Instagram account to the Business Suite

---

## 2. GOOGLE ADS STRATEGY (60% of budget = HK$600-1,200/month)

### Campaign: "Taikoo Piano & Erhu Leads"

**Campaign Type:** Search (text ads only — best ROI for local services)

**Location Targeting:** 
- Radius: 3km around Taikoo Shing / Kornhill
- OR target these areas specifically: Taikoo Shing, Kornhill, Quarry Bay, Sai Wan Ho, Heng Fa Chuen

**Language:** English + Traditional Chinese

### Ad Group 1: Piano (English)
**Keywords** (Phrase Match):
```
"piano teacher taikoo"
"piano lessons kornhill"
"piano teacher quarry bay"
"ABRSM piano taikoo"
"kids piano lessons taikoo shing"
"piano teacher near kornhill"
"home piano teacher hong kong island"
```

**Ad Copy:**
```
Headline 1: Piano Teacher in Taikoo & Kornhill
Headline 2: ABRSM Exam Prep | Ages 4+
Headline 3: Free First Lesson — Book via WhatsApp
Description: Home-based piano lessons in Kornhill. 10+ years experience. 
Trilingual (粵/普/EN). Ed Bureau registered. No commute for your family.
```

### Ad Group 2: Piano (Chinese)
**Keywords:**
```
"太古鋼琴老師"
"康怡花園鋼琴"
"太古城鋼琴課程"
"鰂魚涌鋼琴老師"
"西灣河學鋼琴"
"ABRSM鋼琴考試"
"上門鋼琴老師太古"
```

**Ad Copy:**
```
標題1: 太古康怡鋼琴老師 | 上門教學
標題2: ABRSM考試準備 | 4歲起
標題3: 首堂免費試堂 — WhatsApp預約
描述: 康怡花園上門鋼琴課。十年教學經驗，教育局註冊教師。
三語教學（粵語/普通話/英語），適合本地及國際學校學生。
```

### Ad Group 3: Erhu (Blue Ocean — Low Competition)
**Keywords:**
```
"erhu teacher hong kong"
"erhu lessons taikoo"
"二胡老師香港"
"二胡課程太古"
"chinese orchestra instrument hong kong"
"learn erhu hong kong"
```

**Ad Copy:**
```
Headline 1: Erhu Teacher — The Blue Ocean Advantage
Headline 2: Rare Skill for School Admissions
Headline 3: Degree-Qualified | Former Orchestra Conductor
Description: Stand out from thousands of pianists. Erhu gives your child 
a competitive edge in school applications. All ages welcome.
```

### Bidding Strategy
- Start with **Maximize Clicks** (first 2 weeks to gather data)
- Switch to **Maximize Conversions** once you have 5+ WhatsApp conversions
- Set daily budget: HK$20-40/day

### Negative Keywords (add these to avoid wasted spend):
```
free
download
sheet music
tutorial
youtube
job
hiring
salary
second hand
used piano
buy piano
piano for sale
```

---

## 3. META ADS STRATEGY (40% of budget = HK$400-800/month)

### Campaign 1: Awareness / Retargeting

**Objective:** Lead Generation or Traffic

**Audience:**
- Location: Taikoo Shing, Kornhill, Quarry Bay, Sai Wan Ho (2km radius)
- Age: 28-50 (parents)
- Interests: Music education, Piano, ABRSM, Parenting, International schools HK
- Language: English AND/OR Chinese (Traditional)

**Placements:** Instagram Feed + Instagram Stories + Facebook Feed

**Ad Creative Ideas (rotate 3-4):**

1. **Carousel:** "3 Reasons Kornhill Families Choose Home Piano Lessons"
   - Slide 1: No commute (photo of Kornhill with overlay text)
   - Slide 2: Same teacher every time (vs. center rotation)
   - Slide 3: Free first lesson (CTA → WhatsApp)

2. **Video (15-30 sec):** Student playing piano or erhu, overlay: "From Grade 0 to Grade 3 in 18 months. Taikoo Shing."

3. **Testimonial Image:** Quote from a parent + "Kornhill resident" tag

4. **Erhu Hook:** "In a sea of pianists, be the rare soloist schools need." → WhatsApp CTA

**Ad Copy (English):**
```
🎹 Piano & erhu lessons right here in Kornhill.

No busy centres. No rotating teachers. Just consistent, 
personalised teaching from an Ed Bureau registered instructor.

✅ ABRSM exam prep (Ages 4+)
✅ Trilingual: 粵語 · 普通話 · English
✅ Free first lesson

Tap to WhatsApp →
```

**Ad Copy (Chinese):**
```
🎹 康怡花園上門鋼琴及二胡課程

無需奔波琴行，無需適應不同老師。
教育局註冊教師，十年教學經驗。

✅ ABRSM考試準備（4歲起）
✅ 三語教學：粵語 · 普通話 · English
✅ 首堂免費試堂

WhatsApp預約 →
```

### Campaign 2: Retargeting (use 20% of Meta budget)

**Custom Audience:** Website visitors (from Meta Pixel) who didn't WhatsApp

**Ad:** "Still thinking about music lessons? Your first lesson is free."

---

## 4. AIEO (AI ENGINE OPTIMIZATION) — Free, Ongoing

AIEO ensures your business shows up when parents ask ChatGPT, Google AI Overview, 
or Perplexity: "Who is the best piano teacher in Taikoo?"

### What's Already Done (in your code):
- ✅ LocalBusiness + MusicSchool JSON-LD schema
- ✅ FAQPage schema (6 Q&As) → feeds Google AI Overviews
- ✅ Person schema with credential → establishes authority
- ✅ Bilingual content → matches both EN and ZH queries
- ✅ areaServed with all neighborhood names

### What You Should Do Monthly:

1. **Google Reviews (most important):**
   - Ask every happy parent to leave a review mentioning "piano" + "Taikoo/Kornhill"
   - Respond to every review (Google ranks responsive businesses higher)
   - Goal: 10+ reviews with 4.8+ stars

2. **Google Business Posts (weekly):**
   - Post once a week: student achievement, ABRSM tip, erhu fact
   - Include "Taikoo" or "Kornhill" in every post
   - This feeds Google's Knowledge Panel about your business

3. **Answer Sites (build citations):**
   - Answer questions on Quora, Reddit, HK parenting forums about:
     "Best piano teacher in Taikoo"
     "ABRSM preparation tips for kids"
     "Is erhu good for school applications?"
   - Link back to kittylau.com
   - AI models train on these sources

4. **Directory Listings (NAP consistency):**
   - List your business on:
     - OpenRice (yes, it indexes for local)
     - HK Moms Facebook Groups (Taikoo Moms, Kornhill Parents)
     - ClassicWanted.com
     - HKMusicians.com
     - Yellow Pages HK
   - Name, Address, Phone must be IDENTICAL everywhere

---

## 5. MONTHLY CONTENT CALENDAR

| Week | Google Business Post | Meta Ad Rotation |
|------|---------------------|------------------|
| 1 | "ABRSM 2026 exam dates announced — here's how to prepare" | Carousel: 3 Reasons |
| 2 | Student achievement (with permission): "Grade 3 Distinction!" | Video: Student playing |
| 3 | "Why erhu gives your child a school admission edge" | Erhu hook ad |
| 4 | "Tips for practicing piano at home — for Taikoo families" | Parent testimonial |

---

## 6. KPI TRACKING

| Metric | Tool | Target (Month 1) | Target (Month 3) |
|--------|------|-------------------|-------------------|
| WhatsApp clicks | GTM + GA4 | 20 | 50 |
| Google Ads CTR | Google Ads | 5%+ | 8%+ |
| Cost per lead | Google Ads | < HK$100 | < HK$60 |
| Google Reviews | GBP | 5 | 15 |
| Local Pack rank | Manual search | Top 3 | #1 |
| "piano teacher taikoo" rank | Search Console | Page 1 | Top 3 |
| Meta ROAS | Meta Ads Manager | 2x | 4x |

---

## 7. DNS: SWITCH TO VERCEL

Your domain currently points to Manus (ns1.dyna-ns.net). To switch to Vercel:

**Option A (Recommended):** Change A records at your DNS provider:
```
A    kittylau.com      →  76.76.21.21
A    www.kittylau.com  →  76.76.21.21
```

**Option B:** Change nameservers to Vercel:
```
ns1.vercel-dns.com
ns2.vercel-dns.com
```

---

## QUICK START (Do Today)

1. Replace `GTM-XXXXXXX` in index.html with your Google Tag Manager ID
2. Replace `PIXEL_ID` in index.html with your Meta Pixel ID
3. Replace `AW-CONVERSION_ID/CONVERSION_LABEL` with your Google Ads conversion
4. Update DNS to point to Vercel (76.76.21.21)
5. Submit sitemap to Google Search Console
6. Ask 3 parents to leave Google Reviews this week
7. Launch Google Ads with HK$20/day on the piano keywords
