# Igor Gerbeev Web Resume

Production-ready static personal resume page for GitHub Pages.

## Files
- `index.html`
- `assets/profile.jpg`
- `assets/favicon.svg`
- `robots.txt`
- `sitemap.xml`
- `.nojekyll`

## Positioning
The page presents Igor Gerbeev as a Senior Software Developer focused on:
- Data Engineering
- AI and Machine Learning
- Azure Databricks
- Python automation
- Airflow and TensorFlow
- Enterprise data platforms
- DWH / ETL / ELT
- Oracle, SQL and PL/SQL as supporting database expertise

## Public links
Configured links:
- LinkedIn: `https://www.linkedin.com/in/gerbeev/`
- GitHub: `https://github.com/gerbeev`

## GitHub Pages deployment
1. Create or open a public GitHub repository.
2. Upload all files and keep the `assets/` folder unchanged.
3. Open **Settings -> Pages**.
4. Choose **Deploy from branch**.
5. Select branch `main` and folder `/root`.
6. Save and wait for GitHub Pages to publish the site.

Expected URL for a user site:
`https://gerbeev.github.io/`

If the site is published from a project repository, update these URLs:
- `index.html` - canonical URL, Open Graph URL, JSON-LD `url`, JSON-LD `image`
- `robots.txt` - sitemap URL
- `sitemap.xml` - page URL

## SEO checklist
- Public GitHub Pages site is enabled.
- `index.html` has a canonical URL.
- `robots.txt` allows crawling and references `sitemap.xml`.
- `sitemap.xml` contains the final public URL.
- Google Search Console has the final site property.
- The sitemap is submitted in Google Search Console.
- LinkedIn and GitHub link back to the site.

## Theme mode
The page follows the visitor's system preference with CSS `prefers-color-scheme`.
- Light system theme -> light page.
- Dark system theme -> dark page.

## Validation notes
Checked before packaging:
- local asset references exist;
- internal anchors point to existing IDs;
- LinkedIn and GitHub links use final public URLs;
- only short hyphens are used instead of long dashes.
