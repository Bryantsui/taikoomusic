# Taikoo Music — Ad Account Setup Guide

**Account:** bryantsui2016@gmail.com  
**WhatsApp:** +852 5988 4031  
**Budget:** HK$1,000/mo Google Ads + HK$500/mo Meta

---

## STEP 1: Google Tag Manager (5 min)

1. Open: https://tagmanager.google.com
2. Sign in with **bryantsui2016@gmail.com**
3. Click **Create Account**
4. Fill in:
   - Account Name: `Taikoo Music`
   - Country: `Hong Kong`
   - Container Name: `kittylau.com`
   - Target Platform: **Web**
5. Click **Create** → Accept terms
6. It will show you a code snippet — **ignore that**, just copy the **GTM-XXXXXXX** ID from the top of the page
7. Send me that ID and I'll update the code

---

## STEP 2: Google Ads (10 min)

1. Open: https://ads.google.com/home/tools/manager-accounts/
2. Sign in with **bryantsui2016@gmail.com**
3. **IMPORTANT:** If it pushes you to create a Smart Campaign, click **"Switch to Expert Mode"** at the bottom
4. Then click **"Create an account without a campaign"** (small link at bottom-left)
5. Confirm:
   - Country: `Hong Kong`
   - Currency: `HKD (HK$)`
   - Time zone: `(GMT+08:00) Hong Kong`
6. Click **Submit** → Add your credit card when prompted

### Create conversion tracking:
7. Left menu → **Goals** → **Conversions** → **Summary**
8. Click **+ New conversion action** → **Website**
9. Enter: `kittylau.com` → click **Scan**
10. Click **+ Add a conversion action manually**:

```
Name:              WhatsApp Lead
Category:          Lead > Submit lead form
Value:             HK$200 (each time)
Count:             One
Click-through window: 30 days
```

11. Click **Done** → **Save and continue**
12. Choose **"Use Google Tag Manager"** → it shows:
    - Conversion ID: `AW-XXXXXXXXX`
    - Conversion Label: `XXXXXXXXXXX`
13. Send me both and I'll update the code

### Create your first campaign:
14. **Campaigns** → **+ New Campaign**
15. Goal: **Leads**
16. Campaign type: **Search**
17. Select your "WhatsApp Lead" conversion
18. Campaign name: `Taikoo Piano & Erhu`
19. Bidding: **Maximize Clicks** (switch to Maximize Conversions after 2 weeks)
20. Budget: **HK$33/day**

### Networks:
21. UNCHECK "Google Display Network" (waste of budget for local)
22. Keep "Google Search Network" checked

### Location:
23. **Locations** → **Enter another location** → search `Taikoo` → choose **Target: Presence**
24. Click **Advanced search** → **Radius** → enter: `Quarry Bay, Hong Kong` → 3 km radius
25. Also add: `Sai Wan Ho, Hong Kong` → 3 km radius

### Language:
26. Add: **English** + **Chinese (Traditional)**

### Ad Group 1: "Piano English"
27. Ad group name: `Piano English`
28. Paste these keywords (one per line):

```
"piano teacher taikoo"
"piano lessons kornhill"
"piano teacher quarry bay"
"ABRSM piano taikoo"
"kids piano lessons taikoo shing"
"piano teacher near kornhill"
"home piano teacher eastern district"
"piano teacher sai wan ho"
```

29. Create ad:

```
Final URL:     https://www.kittylau.com
Headline 1:    Piano Teacher in Taikoo & Kornhill
Headline 2:    ABRSM Exam Prep — Ages 4+
Headline 3:    Free First Lesson — WhatsApp Now
Headline 4:    Home-Based in Kornhill
Headline 5:    Ed Bureau Registered Teacher
Description 1: Home-based piano lessons in Kornhill. 10+ years experience. Trilingual (粵/普/EN). No commute. Free trial lesson via WhatsApp.
Description 2: ABRSM preparation specialist in Taikoo Shing. Personalised 1-on-1 teaching. Same dedicated teacher every lesson. Book your free trial today.
```

### Ad Group 2: "Piano Chinese"
30. Create new ad group: `Piano Chinese`
31. Keywords:

```
"太古鋼琴老師"
"康怡花園鋼琴"
"太古城鋼琴課程"
"鰂魚涌鋼琴老師"
"西灣河學鋼琴"
"ABRSM鋼琴考試太古"
"上門鋼琴老師太古"
"康怡鋼琴老師"
```

32. Ad:

```
Final URL:     https://www.kittylau.com/zh
Headline 1:    太古康怡鋼琴老師 | 上門教學
Headline 2:    ABRSM考試準備 | 4歲起
Headline 3:    首堂免費試堂 — WhatsApp預約
Headline 4:    教育局註冊教師
Headline 5:    十年教學經驗
Description 1: 康怡花園上門鋼琴課。十年教學經驗，教育局註冊教師。三語教學（粵語/普通話/英語），適合本地及國際學校學生。
Description 2: 太古城ABRSM鋼琴考試準備專家。一對一個人化教學，無需適應不同老師。立即WhatsApp預約免費試堂。
```

### Ad Group 3: "Erhu"
33. Create new ad group: `Erhu`
34. Keywords:

```
"erhu teacher hong kong"
"erhu lessons taikoo"
"二胡老師香港"
"二胡課程太古"
"learn erhu hong kong"
"二胡老師東區"
"chinese orchestra instrument lessons"
```

35. Ad:

```
Final URL:     https://www.kittylau.com
Headline 1:    Erhu Teacher — The Blue Ocean Edge
Headline 2:    Rare Skill for School Admissions
Headline 3:    Degree-Qualified Instructor
Headline 4:    All Ages Welcome
Headline 5:    Former Orchestra Conductor
Description 1: Stand out from thousands of pianists. Erhu gives your child a competitive edge in school applications. Degree-qualified teacher, all ages.
Description 2: 專業二胡課程，前中樂團指揮任教。學校面試獨特優勢，適合所有年齡。太古區上門教學。
```

### Negative Keywords:
36. Campaign level → **Negative keywords** → add:

```
free download
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
piano price
琴行
買琴
鋼琴價錢
```

37. Click **Publish Campaign** → Done!

---

## STEP 3: Google Search Console (3 min)

1. Open: https://search.google.com/search-console
2. Sign in with **bryantsui2016@gmail.com**
3. Click **Add property** → **URL prefix** → enter: `https://www.kittylau.com`
4. Verification method: choose **Domain name provider**
   - It will give you a TXT record like: `google-site-verification=XXXXXXXXXXXX`
5. Go to Dynadot → DNS Settings for kittylau.com
   - Add a **TXT** record with that value
6. Back in Search Console → click **Verify**
7. Go to **Sitemaps** → enter: `https://www.kittylau.com/sitemap.xml` → **Submit**

---

## STEP 4: Meta Ads (10 min)

1. Open: https://business.facebook.com/overview
2. Sign in with your **personal Facebook** (NOT measurable.ai)
3. Click **Create a Business Portfolio**
   - Name: `Kitty Music Studio`
   - Your name
   - Email: `bryantsui2016@gmail.com`

### Create a Facebook Page:
4. Go to: https://www.facebook.com/pages/create
5. Fill in:
   - Page name: `Kitty Music Studio 太古音樂教室`
   - Category: `Music School`
   - Bio: `Professional piano & erhu lessons in Taikoo & Kornhill. ABRSM exam prep. Trilingual teaching. 太古康怡鋼琴二胡課程。`

### Set up Meta Pixel:
6. Go to: https://business.facebook.com/events_manager
7. **Connect Data Sources** → **Web** → **Meta Pixel**
8. Pixel name: `Taikoo Music Pixel`
9. Enter website: `kittylau.com`
10. Choose **Install code manually**
11. Copy the **Pixel ID** (number like `123456789012345`)
12. Send me that ID and I'll update the code

### Create ad campaign:
13. Go to: https://adsmanager.facebook.com
14. Click **+ Create**
15. Objective: **Leads**
16. Campaign name: `Taikoo Music - Parents`
17. Budget: **HK$16/day** (≈ HK$500/month)
18. Schedule: Start today, no end date

### Ad Set:
19. Ad set name: `Taikoo Parents EN+ZH`
20. Conversion location: **Website**
21. Pixel: select your Taikoo Music Pixel
22. Optimization: **Leads**

### Audience:
23. Location: **Drop a pin** on Taikoo Shing → **2 km radius**
24. Age: **28-50**
25. Detailed targeting → type and add each:
   - `Music education`
   - `Piano`
   - `ABRSM`
   - `Parenting`
   - `International schools`
   - `Hong Kong parents`
26. Languages: **English (All)** + **Chinese (Traditional)**

### Placements:
27. Select **Manual placements**
28. Check ONLY:
   - Instagram Feed
   - Instagram Stories
   - Facebook Feed
   - Facebook Stories

### Ad Creative:
29. Ad name: `Piano Kornhill - WhatsApp`
30. Format: **Single image or video**
31. Use a nice photo of a piano / your studio
32. Primary text (paste this):

```
🎹 Piano & erhu lessons right here in Kornhill.

No busy centres. No rotating teachers. Just consistent, personalised teaching from an Ed Bureau registered instructor.

✅ ABRSM exam prep (Ages 4+)
✅ Trilingual: 粵語 · 普通話 · English  
✅ Free first lesson

Tap below to WhatsApp →
```

33. Headline: `Piano Teacher Taikoo — Free Trial Lesson`
34. Description: `Home-based in Kornhill. 10+ years experience.`
35. Call to action: **Send WhatsApp Message**
36. WhatsApp number: `+852 5988 4031`
37. Click **Publish**

### Create a second ad (Chinese):
38. Duplicate the ad → change:
- Primary text:

```
🎹 康怡花園上門鋼琴及二胡課程

無需奔波琴行，無需適應不同老師。
教育局註冊教師，十年教學經驗。

✅ ABRSM考試準備（4歲起）
✅ 三語教學：粵語 · 普通話 · English
✅ 首堂免費試堂

WhatsApp預約 →
```

- Headline: `太古康怡鋼琴老師 — 免費試堂`
- Description: `康怡花園上門教學。十年經驗。`
39. **Publish**

---

## AFTER SETUP — Send me these 3 values:

1. **GTM ID:** `GTM-XXXXXXX` (from Step 1)
2. **Google Ads Conversion:** `AW-XXXXXXXXX` and label `XXXXXXXXXXX` (from Step 2)
3. **Meta Pixel ID:** `123456789012345` (from Step 4)

I'll update the code and push — site updates in 1 minute.

---

## Budget Summary

| Platform | Daily | Monthly | What it does |
|----------|-------|---------|-------------|
| Google Ads | HK$33 | HK$1,000 | Catches parents searching "piano teacher taikoo" |
| Meta Ads | HK$16 | HK$500 | Shows ads to parents in Taikoo on Instagram/FB |
| **Total** | **HK$49** | **~HK$1,500** | |
