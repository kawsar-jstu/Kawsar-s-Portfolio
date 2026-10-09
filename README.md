# Kawsar Alam — Multi-page EEE Portfolio

এই version-এ সব content এক পেজে রাখা হয়নি। প্রতিটি বড় বিষয় আলাদা HTML page-এ রাখা হয়েছে।

## Pages
- `index.html` — Home (মূল landing page)
- `about.html` — About Me
- `skills.html` — Skills
- `projects.html` — Projects
- `education.html` — Education
- `experience.html` — Experience
- `gallery.html` — আলাদা আলাদা photo collections
- `certificates.html` — Certificates & Achievements
- `contact.html` — Contact details
- `style.css` — সব পেজের shared design ও color grading
- `script.js` — mobile menu, theme toggle, gallery preview
- `assets/` — নিজের সব ছবির folder

## কীভাবে edit করবে
1. ZIP extract করো।
2. VS Code বা অন্য code editor-এ folder খোলো।
3. যে page বদলাতে চাও, সেই `.html` ফাইল খোলো।
4. রং বদলাতে `style.css`-এর একদম উপরে `:root`-এর variables বদলাও।
5. ছবি বদলাতে `assets/`-এ নিজের ছবি রাখো এবং HTML-এ `src` path বদলাও।
6. নতুন card যোগ করতে একই ধরনের card-এর পুরো block copy করে paste করো।
7. `index.html` browser-এ খুলে পরিবর্তন পরীক্ষা করো।

## Photo folder names
- Profile: `assets/profile.jpg`
- Campus: `assets/campus-01.jpg`, `campus-02.jpg`, `campus-03.jpg`, `campus-04.jpg`
- Projects: `assets/project-01.jpg`, `project-02.jpg`, `project-03.jpg`
- Lab / personal gallery: `assets/lab-01.jpg`, `lab-02.jpg`, `lab-03.jpg`, `lab-04.jpg`
- Certificates: `assets/certificate-01.jpg`, `certificate-02.jpg`, `certificate-03.jpg`

ছবির নাম আলাদা হলে সংশ্লিষ্ট HTML file-এ `src` এবং `data-full` path বদলাতে হবে। কিছু sample image URL placeholder হিসেবে আছে; internet connection না থাকলে তা দেখা নাও যেতে পারে।

## Color grading
`style.css`-এর `:root` অংশে:
- `--bg`: page background
- `--panel`: card background
- `--text`: main text
- `--muted`: secondary text
- `--primary`: blue/cyan highlight
- `--secondary`: purple gradient
- `--accent`: extra highlight
- `--border`: outlines

## Contact details
`contact.html`-এ `your-email@example.com` search করে নিজের email বসাও। LinkedIn ও GitHub links নিজের profile URL দিয়ে বদলাও।

## GitHub Pages-এ publish
1. GitHub repository-তে এই folder-এর files upload করো; ZIP-টা নিজে extract করে upload করবে।
2. সব `.html` files, `style.css`, `script.js` এবং `assets` folder repository root-এ থাকবে।
3. GitHub → Repository → Settings → Pages-এ গিয়ে `main` branch এবং `/(root)` নির্বাচন করো।
4. Save করার পর deployment complete হলে site URL খুলো।
5. Navigation থেকে Home, About, Projects, Gallery ইত্যাদি আলাদা পেজে যায় কি না পরীক্ষা করো।

নোট: এই ZIP একটি editable multi-page redesign template। তোমার live GitHub site-এ এটি নিজে থেকে deploy হয় না। নিজের আসল ছবি, email, social links এবং সঠিক academic information বসিয়ে প্রকাশ করবে।
