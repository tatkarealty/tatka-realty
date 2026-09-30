# Tatka Realty website

Serves both domains from one Netlify site:

- **tatkarealty.com** opens the landing page (Residential / Commercial).
- **tatkacre.com** opens the Commercial page directly.

## Editing listings

1. Go to **tatkarealty.com/admin** and sign in with GitHub.
2. Open **Listings**, then **Residential homes** or **Commercial properties**.
3. Add or edit a listing, drag in photos (the first photo is the cover), and select **Publish**.
4. The site updates in about a minute.

To hide a listing without deleting it, turn off **Show on site**.

## Inquiries

The residential and commercial contact forms use Netlify Forms. Submissions appear in the
Netlify dashboard under **Forms**, and email notifications can be turned on there.

## Files

- `index.html`: the whole site (landing, residential, commercial)
- `content/residential.json`, `content/commercial.json`: listings, edited through /admin
- `images/uploads/`: listing photos uploaded through /admin
- `admin/`: the listings editor (Decap CMS)
