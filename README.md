"# CMS-DevMarketer"

Ep-7
-----
1. Instead of Bootstrap I used bulma.io framework, which is based on flexbox.
2. Bulma only provides CSS (UI Components) but not any javascript like Bootstrap. To make things dynamic we need to make our own javascript.
3. In this project I'm going to create vue components using 'buefy', which provides bulma components with javascript in form of vue components.
4. For fonts I used font-awesome.
5. I'm going to use Vue on per page basic, so I removed code from app.js which initialized Vue for entire system.
6. Because I'm not using bootstrap. I have removed bootstrap dependencie in bootstrap.js
7. Import Buefy in app.js and tell Vue to use it.
8. I imported 'Fontawesome','Bulma' and 'Buefy' in app.scss file and also removed bootstrap scss dependencie.
9. compile scss and js using 'npm run dev' command.
10. Setup app name and mysql database settings in .env file. also setup mailtrap here.
11. Set timezone in app.php file config folder.
