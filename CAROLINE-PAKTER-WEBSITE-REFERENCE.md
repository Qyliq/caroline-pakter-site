# Caroline Pakter Website — Reference Document

**Created:** 3 February 2026
**Status:** LIVE at carolinepakter.com
**Site Location:** `/Volumes/NVME/Claude/Code/caroline-pakter-site/`

---

## Project Summary

Built a static HTML/CSS website for Caroline Pakter (Rob's sister-in-law), an Orthodox Jewish singer and former West End performer. Replaces her existing WordPress/Elementor site at carolinepakter.com.

**Why static over WordPress:**
- Elementor basic version made pages look jumbled
- No ongoing subscription needed
- Faster, more secure, free hosting
- Claude can edit directly

---

## Site Structure

| Section | Content |
|---------|---------|
| **Hero** | Headshot, tagline "From Showbiz to Shabbos", CTAs |
| **About** | Full bio with credentials (LIPA, West End, Neve) |
| **The Show** | Performance photos + show description + locations |
| **Watch** | 3 YouTube video embeds |
| **Music** | Both albums with real cover images |
| **Contact** | Phone, location, email, booking CTA |

---

## Design Choices

**Palette:**
- Burgundy: #722F37 (primary)
- Gold: #C9A227 (accent)
- Cream: #FAF8F5 (background)
- Charcoal: #1a1a1a (text)

**Typography:**
- Headlines: Cormorant Garamond (elegant serif)
- Body: Raleway (clean sans)

**Style:** Editorial/refined meets theatrical warmth — matches her "showbiz to shabbos" journey

---

## Files

```
/Volumes/NVME/Claude/Code/caroline-pakter-site/
├── index.html
└── images/
    ├── headshot.jpg           (professional headshot)
    ├── singing.webp           (singing with headband)
    ├── performance-1.webp     (colourful headscarf, gold scarf)
    ├── performance-2.webp     (trench coat, suitcase - theatrical)
    ├── performance-3.webp     (gold scarf, stage)
    ├── album-we-believe.jpg   (purple silhouette design)
    └── album-yachad.jpg       (Western Wall/Kotel design)
```

---

## YouTube Videos

1. https://youtu.be/7J6Ba0OeZaA
2. https://youtu.be/tRDgArwgaFw
3. https://youtu.be/eFzHeq6e1vk

---

## Caroline's Bio Content

### Main Bio
Caroline Pakter (née Cohen) is a London-based Orthodox Jewish singer and performer dedicated to uplifting and inspiring women and girls through soulful, meaningful music. A former West End actress and singer, Caroline was an understudy to Eliza Doolittle in My Fair Lady at Theatre Royal Drury Lane and trained at Paul McCartney's Liverpool Institute for Performing Arts (LIPA).

Caroline performs exclusively for women-only audiences, offering custom performances for concerts and bas mitzvah celebrations. Her repertoire spans traditional and contemporary Jewish music alongside carefully selected, clean musical theatre songs, delivered with warmth, professionalism, and heartfelt connection.

She has released two albums, We Believe and Yachad, both compilations of Caroline's original compositions alongside well-known songs by Abie Rottenberg and Mark Samowitz (aka Shooby Doop Shloimy). These albums reflect her musical depth and spiritual journey and are available for download on this website, with releases on Spotify coming soon.

Having spent formative years at Neve Yerushalayim in Israel, Caroline's music is infused with emunah, joy, and authenticity. She has also run choirs for women and girls, using music as a tool for confidence, unity, and inspiration. Caroline now lives in London with her family and continues to bring light and joy to women around the world through song.

### "From Showbiz to Shabbos" Show Bio
From Showbiz to Shabbos is Caroline Pakter's signature women-only performance, sharing her personal journey from a rising star on the London West End to committing to a life of Torah.

Through story and song, Caroline weaves together her experiences in professional musical theatre with her spiritual growth, creating an engaging, heartfelt, and deeply inspiring performance. The show features a blend of traditional and modern Jewish music alongside clean musical theatre selections, all connected to themes of identity, faith, courage, and joy.

From Showbiz to Shabbos has been performed internationally for women-only audiences in Israel, London, Manchester, Glasgow, Leeds, New York (Monsey and Crown Heights), Palo Alto, Denver, Johannesburg, Cape Town, Belgium, and at Pesach programmes worldwide.

Both uplifting and entertaining, the show resonates with women and girls of all ages and is especially well-suited for women's events, concerts, and bas mitzvah programming—leaving audiences inspired, moved, and uplifted.

---

## Contact Info

- **Phone:** 07867 179 126
- **Location:** Edgware, London
- **Email:** carolinepakter@gmail.com

---

## Domain Info

| Detail | Value |
|--------|-------|
| **Domain** | carolinepakter.com |
| **Registrar** | Hover.com (via Tucows) |
| **Expires** | 25 June 2026 |
| **DNS managed at** | hover.com |
| **Name servers** | ns1.hover.com, ns2.hover.com |

### Hover Login Credentials
- **Username:** carolinecohen
- **Password:** zitmi5-nuctuh-nifkoV
- **URL:** https://www.hover.com/signin

---

## Deployment (Completed 3 February 2026)

**Hosted on:** Netlify
**Netlify project:** melodic-churros-37faf0
**Netlify URL:** https://melodic-churros-37faf0.netlify.app
**Live URL:** https://carolinepakter.com

### Netlify Login
- **Account:** rob@makeamouve.com
- **Auth:** GitHub OAuth (no separate password)
- **Dashboard:** https://app.netlify.com
- **This project:** https://app.netlify.com/projects/melodic-churros-37faf0/overview

### DNS Records at Hover
| Type | Host | Value |
|------|------|-------|
| A | @ | 75.2.60.5 |
| CNAME | www | melodic-churros-37faf0.netlify.app |
| MX | @ | 10 mx.hover.com.cust.hostedemail.com (email - unchanged) |
| CNAME | mail | mail.hover.com.cust.hostedemail.com (email - unchanged) |

---

## Remaining Tasks

1. [ ] Send to Caroline for approval
2. [ ] Cancel old WordPress/Elementor hosting (weitbrdd.elementor.cloud)
3. [ ] Optional: Add proper contact form (Netlify Forms or Formspree)

---

## Additional Assets

**Dropbox folder with more images:**
https://www.dropbox.com/scl/fo/00vfe2s94w6gbtsczxmdc/ALdlRq9f1dGDC3DloqqyyEs?rlkey=96zffli4daqd9mz5dt8uwhnb3&st=qnv8j95t&dl=0

---

## Design Skill Used

Frontend Design skill from Anthropic:
`~/.claude/plugins/cache/claude-plugins-official/frontend-design/27d2b86d72da/skills/frontend-design/SKILL.md`

Key principles applied:
- Bold aesthetic direction (editorial/theatrical)
- Distinctive typography (Cormorant Garamond + Raleway)
- Cohesive colour palette from her photos
- Avoided generic "AI slop" aesthetics
