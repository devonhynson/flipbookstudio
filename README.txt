FLIPBOOK STUDIO: PUT IT ON YOUR OWN WEB ADDRESS

What is in this folder
- index.html: the whole studio in one file. It needs no build step and no Claude account to use.

Put it online (about 5 minutes)
1. Go to app.netlify.com/drop and sign in.
2. Drag this whole folder onto the page. Netlify gives you a link like https://something.netlify.app.
3. To use your own address, open the site in Netlify, go to Domain management, and add a subdomain such as studio.devonhynson.com. Netlify shows the DNS record to add where your domain is managed.

Update it later
Open the site in Netlify, go to the Deploys tab, and drag the updated folder there. That keeps the same address.

Where books are saved
Books are saved in the browser of whoever uses the studio, on that device. Use "Download backup file" in the studio to keep a copy or move books to another computer, then "Import" to bring them back.

Publishing a book
In the studio, open a book and click Publish:
- Flipbook file: download it, then drop it on Netlify Drop, or put it in your Bolt site's public/books folder. Its web address is the share link.
- Embed code: paste the share link into the box, copy the code, and paste it into your website page.
- PDF: downloads a print-ready copy with working links.

Next step for a product other people sign up for
Accounts, saved books in the cloud, hosted share links for every user, and payments need a server and database (for example, your own Supabase project). The studio keeps each book as one block of data, so it can be connected to Supabase without changing how books are made.
