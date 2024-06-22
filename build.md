```

pj4
├── Dockerfile
├── docker-compose.yml
├── docs
│   ├── exampledoc4.md
│   └── exampledoc5.md
├── docusaurus.md
└── website
    ├── README.md
    ├── blog
    │   ├── 2017-09-26-adding-rss.md
    │   └── 2017-10-24-new-version-1.0.0.md
    ├── core
    │   └── Footer.js
    ├── package.json
    ├── pages
    │   └── en
    │       ├── help.js
    │       ├── index.js
    │       └── users.js
    ├── sidebars.json
    ├── siteConfig.js
    ├── static
    │   ├── css
    │   │   └── custom.css
    │   └── img
    │       ├── favicon.ico
    │       └── undraw_youtube_tutorial.svg
    └── yarn.lock


cd website
npm start
http://localhost:3000

cd website
npm run build

node -v
v20.15.0
nmp -v
6.11.3

cd build

git init
git remote add origin https://github.com/tztechno/tz_blog_docusaurus
git add .
git commit -m "Initial commit"
git push -u origin master

 https://tztechno.github.io/tz_blog_docusaurus/
```