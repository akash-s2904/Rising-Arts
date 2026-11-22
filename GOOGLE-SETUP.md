# Getting Rising Arts found on Google

The website now has the search setup built in: business details Google can read, a sitemap, link previews and a favicon.
Search engines only find a site that someone tells them about, though, so the owner needs to do the steps below once. Do them in this order.

---

## 1. Google Business Profile (most important – do this first)

This is the listing that appears on **Google Maps** and on the right-hand side of Google results when people search for
"wall painting advertisement Tirunelveli", "flex board near me" and similar phrases. For a local business it brings in more calls than the website itself.

1. Sign in to the business Gmail account and open **https://business.google.com**.
2. Click **Add business** and use:
   - **Business name:** `Rising Arts` (exactly this – no extra keywords; Google can suspend profiles that stuff keywords into the name)
   - **Category:** `Advertising agency`. Add extra categories if offered: `Sign shop`, `Painter`.
   - **Location:** choose *Yes, customers can visit*, and enter `5B, Ganesh Complex, Tirunelveli Junction, Tamil Nadu` and the PIN code.
   - **Service areas:** Tirunelveli, Thoothukudi, Tenkasi, Kanyakumari, Virudhunagar, Madurai (and any others you actually serve).
   - **Phone:** `94432 83781`
   - **Website:** `https://rising-arts.vercel.app/` (or your own domain later)
3. **Verify** the business. Google will offer a phone call/SMS, a video of the shop, or a postcard. The listing does not show in search until it is verified.
4. After verification, finish the profile:
   - Add **10 or more real photos**: the shop front, finished walls, hoardings, flex and vinyl boards, the team at work.
   - Add every **service** (wall painting, hoarding fabrication, flex fitting, vinyl board, scaffolding, custom advertisements).
   - Set **opening hours**.
   - Write a description in English and Tamil (you can copy the wording from the website).
5. **Ask happy customers for Google reviews.** In the profile, use *Ask for reviews* to get a link and send it on WhatsApp after each job. Reviews are the biggest factor for ranking on Maps.

## 2. Google Search Console (tells Google the website exists)

1. Open **https://search.google.com/search-console** with the same Gmail account.
2. Click **Add property**, choose **URL prefix** and enter `https://rising-arts.vercel.app/`.
3. Choose the **HTML tag** verification method. Google shows a line like
   `<meta name="google-site-verification" content="abc123..." />`.
   Send that line to whoever edits the website. It goes inside `<head>` in `index.html`, just under the `<meta name="viewport" …>` line. After the change is live, press **Verify**.
4. In the left menu open **Sitemaps**, enter `sitemap.xml` and press **Submit**.
5. Open **URL inspection**, paste `https://rising-arts.vercel.app/` and click **Request indexing**.

The site normally starts showing for its own name ("Rising Arts Tirunelveli") within a few days to two weeks.

## 3. Bing (optional, 5 minutes)

At **https://www.bing.com/webmasters** you can choose *Import from Google Search Console*. It copies everything over.

## 4. Get the link out there

Every place that links to the website helps Google trust it:

- Put the website link on the **WhatsApp Business** profile, Facebook/Instagram pages and visiting cards.
- Add a small "Rising Arts · 94432 83781" credit on the walls and boards you paint, if your customers allow it.
- List the business on **Justdial** and **IndiaMART** with the **same name, address and phone** as on the website.

## 5. Your own domain (recommended)

A `.in` or `.com` address (for example `risingarts.in`, about ₹800/year) looks more professional and ranks better than `rising-arts.vercel.app`.
After buying one, add it in the Vercel project (**Settings → Domains**). Then replace `https://rising-arts.vercel.app/` with the new address in
`index.html`, `sitemap.xml` and `robots.txt`, and add the new address as a separate property in Search Console.
