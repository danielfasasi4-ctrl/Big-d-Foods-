
Big D Foods — Website package
============================

Files included:
- index.html
- menu.html
- about.html
- contact.html

How to use (quick steps) — upload to GitHub Pages
1. Go to https://github.com and sign in.
2. Click the + (top-right) → New repository.
3. Name the repository (e.g. big-d-foods) and create it (public is fine).
4. Click "Add file" → "Upload files" and select the four HTML files from this ZIP.
5. Commit changes.
6. Go to Settings → Pages and set Source to the main branch and root (/) then Save.
7. Wait a minute and open https://yourusername.github.io/your-repo-name/ (replace with your username and repo name).

Notes about ordering & notifications
- Menu buttons use your Selar product links and open in a new tab so customers complete payment on Selar.
- Selar sends order confirmation emails to the email you registered with Selar (abosedefasasi8@gmail.com).

Contact form (email notifications)
- The contact form has two sending options:
  1) Send Message (Email) — this opens the device's default mail client (Gmail app or Mail) with a prefilled message addressed to abosedefasasi8@gmail.com. The customer must press Send in the mail app.
  2) Send via Formspree — optional automatic method. To use it:
     - Create a free Formspree form at https://formspree.io and get your endpoint (it looks like https://formspree.io/f/xxxx).
     - Replace the placeholder string FORM_ENDPOINT_REPLACE_ME in contact.html with your Formspree endpoint URL.
     - After replacing, the "Send via Formspree" button will POST messages automatically to Formspree and Formspree will email you (no extra server required).

Editing
- To edit text, open the HTML files in a text editor and change the content.
- Images used are linked from Unsplash (free to use). If you want to host images inside the repo, create an 'images' folder and update the <img> src paths accordingly.

Support
- If you want, I can guide you step-by-step to upload the files to GitHub Pages on your phone.
