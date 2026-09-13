Prem Creation Website
Official website for Prem Creation, built with HTML, CSS, and JavaScript and hosted using Firebase Hosting.
🌐 Website
Prem Creation
The website provides information about Prem Creation projects, Android applications, downloads, and related resources.
✨ Features
📱 Android app showcase
📥 App download links
🖼️ App screenshots and media
📄 App information and descriptions
🌐 Responsive design for mobile, tablet, and desktop
🔍 SEO-friendly HTML structure
📊 Google Analytics integration
📢 app-ads.txt support
🔥 Firebase Hosting deployment
⚡ Lightweight HTML/CSS/JavaScript implementation
📱 Mobile-friendly navigation and layout
🛠️ Technologies
HTML5
CSS3
JavaScript
Firebase Hosting
Google Analytics
📁 Project Structure
prem-creation-website/
│
├── index.html
├── style.css
├── script.js
│
├── images/
│   ├── logo/
│   ├── screenshots/
│   └── icons/
│
├── favicon.ico
├── robots.txt
├── app-ads.txt
├── firebase.json
├── .firebaserc
└── README.md

> File and folder names can be adjusted to match the actual project structure.
🚀 Run Locally
Clone the repository:
git clone YOUR_GITHUB_REPOSITORY_URL

Enter the project directory:
cd prem-creation-website

You can open index.html directly in a browser, or use a local development server.
For example:
python3 -m http.server 8000

Then open:
http://localhost:8000

🔥 Firebase Hosting
This website is designed to be deployed using Firebase Hosting.
Install Firebase CLI:
npm install -g firebase-tools

Login:
firebase login

Initialize Firebase Hosting:
firebase init hosting

For this project, the website files are hosted from the project directory.
Deploy the website:
firebase deploy

After deployment, Firebase will provide the live hosting URL.
📢 app-ads.txt
The project can include an app-ads.txt file for advertising verification.
The file should be placed in the public website directory:
app-ads.txt

It should be accessible from:
https://YOUR-DOMAIN/app-ads.txt

Make sure the file is served as a normal text file rather than downloaded incorrectly or replaced by a Firebase error page.
🤖 robots.txt
The website can use robots.txt to provide search-engine crawling instructions.
Example:
User-agent: *
Allow: /

Sitemap: https://YOUR-DOMAIN/sitemap.xml

Update the sitemap URL when a sitemap is available.
📊 Google Analytics
Google Analytics can be integrated into index.html using the Google-provided measurement code.
Place the Analytics script inside the <head> section of the website.
Replace the placeholder measurement ID with the actual Google Analytics measurement ID.
📱 Responsive Design
The website is designed to work across:
Android phones
iPhones
Tablets
Laptops
Desktop computers
CSS media queries are used to adapt the layout to different screen sizes.
🔐 Security
Do not commit sensitive information to this repository.
Never upload:
API keys that must remain private
Passwords
Firebase service-account private keys
Authentication credentials
Private certificates
Personal confidential information
Use .gitignore for files that should not be committed.
🔄 Updating the Website
After making changes:
git status

Review the changes:
git diff

Add the files:
git add .

Commit:
git commit -m "Update website"

Push to GitHub:
git push

If Firebase Hosting is also being used:
firebase deploy

🧪 Before Publishing
Check the following before every deployment:
Website opens correctly
Mobile layout works
Desktop layout works
Navigation links work
App download links work
Images load correctly
Favicon loads
robots.txt works
app-ads.txt works
Google Analytics is configured
No broken links
No sensitive information is committed
Firebase deployment succeeds
📸 Screenshots
Add website screenshots here when available.
Example:
## Screenshots

![Home Page](images/screenshots/home.png)

![Apps Page](images/screenshots/apps.png)

![Mobile View](images/screenshots/mobile.png)

📄 License
Unless otherwise stated, the website source code and original content are the property of Prem Creation.
Third-party libraries, trademarks, images, and services remain the property of their respective owners.
👨‍💻 Developer
Prem Creation
Android applications and software projects developed by Prem Creation.
⭐ Repository
If you find this project useful, consider giving the repository a ⭐ on GitHub.
---
© 2026 Prem Creation. All rights reserved.
