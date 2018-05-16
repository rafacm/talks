footer: rafael cordones | @rafacm | JAMming with Gentics Mesh, Reat Static and Amazon S3 | We Are Developers Workshops @ APA-IT
slidenumbers: true

![inline](assets/gentics-mesh-react-static-amazon-s3-logos.png)

# JAMming with Gentics Mesh, React Static and Amazon S3
#### We Are Developers /  Workshops @ APA-IT / Vienna, May 16th, 2018

---

# Agenda

1. Teaser talk: how did I get here? (15 min.)
1. Gentics Mesh: Tour de Force (30 min.)
1. Break (10 min.)
1. React Static & React (10 min.)
1. Feature implementation (30 min.) 
1. Amazon S3 (10 min.)
1. Wrap-up (5 min.) 

---

# Talk

---

# Fasten your seatbelts...

![inline](assets/Forklift-Safety-Signs-Stop-Fasten-Your-Seat-Belts-With-Seat-Belt-Symbol-W1539-ba.jpg)

---

# Credits
![inline](assets/the-front-end-strickes-back.png)

---

# Who am I?

![inline](assets/rafa.jpg)

---

# Background
![inline](assets/thewml-org.png)

---

# Web Content Projects
![left 40%](assets/screenshot-community-2.png)

1. Internal content publication
2. External user generated content
3. 6-12 months projects
2. 10x of page types
2. 100x of components
2. 1000x of content items
2. 100000x of users

---

## Patterns

![left 60%](assets/the-song-remains-the-same.jpg)

## ...
## Web front-end design 
## ...
## changes every 2 years but 
## ...
## the content remains the same

---

# Patterns: thinking in components
![inline](assets/top-solution-authors.png)

---

# Patterns: the anatomy of a component
![left 70%](assets/1024px-Da_Vinci_Vitruve_Luc_Viatour-1.jpg)

1. Retrieve and aggregate data 
1. Render the data + HTML markup + styling 
1. React to user input

---

# Patterns: "we need a website"
![left 40%](assets/leonardo-da-vinci.jpg)

> "Software is never finished, just abandoned"
-- Leonardo Dev Vinci

# The initial **successful website** turns...
# into a **web application**.

# CMSs are **development platforms**

---

# Monolithic/full-stack CMS, we need to talk: what if...
![left 60%](assets/que-sera-sera.jpg)

1. CMS back-end & front-end were completely separated?
1. Front-end could be developed with any tech or framework?
1. Content could be managed independently of the front-end?

---

# The CMS* is dead!
## * Content **Management System**

![left](assets/louis16_execution.jpg)

---
 
# Long Live the CMS*
## * Content **Micro-Service**
### a.k.a. API-driven CMS
### a.k.a. Headless CMS

![left](assets/Louis_XVI_-_Execution.jpg)

---

# Headless CMS

![inline](assets/headlesscms.png)

---

# Headless CMS
![left 75%](assets/joel-spolsky.png)

> "Making a major horizontal product that's
> useful in any walk of life is almost 
> impossible to pull off." 
-- Joel Spolsky*

*He is here at WeAreDevelopers! 
Tomorrow Friday @ 09:30 h. on Stage F1!

---

# Why headless CMS?

![inline](assets/headlesscms.png)

---

# The Anatomy of a CMS

![left 35%](assets/Rembrandt_Harmensz._van_Rijn_007.jpg)

1. Content modeling
1. Content editing
1. Querying / search
1. Permissions: who can do what
1. Audit: who did what when
1. Content rendering (frameworks, libraries, ...)
1. Content analytics, personalization, SEO, ...
1. ...

---

# Headless / API-first CMSs
![left 25%](assets/theUsualSuspects_1416603356.jpg)

1. [contentful](https://www.contentful.com/) (Saas)
1. [prismic](https://prismic.io) (Saas)
1. [GraphCMS](https://graphcms.com/) (Saas)
1. [Contenta CMS](https://www.contentacms.org/) (Drupal)
1. ...

---

# Content APIs: O Content, where art thou?

![inline](assets/manofconstantsorrow_obrotherwhereartthou.jpg)

---

# Content APIs: O Content, where art thou?

### "I Am A [Dev] of Constant Sorrow" --- Soggy Bottom [Devs]

1. Proliferation of content repository APIs adds overhead for developers to learn about the **semantics** of the API
1. One API to rule them all?

![inline](assets/graphql.png)

---

# How did I get here?
![inline 45%](assets/carmen-marcos-art-screeenshot.png)

---

# How did I get here?

1. ...
2. prismic.io + (Scala) Play! Framework
1. ...
2. Contentful + (JavaScript) Angular 1.x
1. ...
2. GraphCMS + (JavaScript) GatsbyJS
1. **Gentics Mesh + (JavaScript) React Static**

---

# Gentics Mesh
![inline 110%](assets/gentics-mesh-topics.png)

---

# Gentics Mesh

![left 100%](assets/gentics-mesh-logo.png)

1. (Hierarchical) content tree: scalability! 
1. Users, groups, roles & permissions
1. APIs: REST, GraphQL, ElasticSearch 
1. Image manipulation: via API & via management UI
1. Multi-linguality
1. On-(cloud)-premise: own my data! 

---

# JAMstack
![inline](assets/jamstack.png)

---

# Yeah, well, that's just like, your opinion, man

![inline](assets/big-lebowski-opinion.jpg)

---

# What's yours?!

![inline](assets/spies_like_us_01_641x383.jpg)

---

---

# Topics
1. Monolithic CMSs up to now where CMS = Content Management System
1. Use-cases for API-first / headless CMSs where CMS = Content Micro-Service 
1. Mesh unique features and how they compare to others (GraphCMS, Contentful, ...)
1. Use-cases for "statically" generated websites
1. Progressive Static-Site generators: React Static vs GatsbyJs

----

# WeAreDevelopers

![inline](assets/wad-people-code-future.jpg)


---

# Gentics Mesh

![left 100%](assets/gentics-mesh-logo.png)

## If you want to ***own your content infrastructure*** 

---

# How does it compare?

![left 100%](assets/gentics-mesh-logo.png)

---

# Gentics Mesh

![inline](assets/getmesh-screenshot.png)

---

# Gentics Mesh

---

# GatsbyJS

![inline](assets/gatsbyjs-web.png)

---

> "It’s like déjà vu all over again"
-- Yogi Berra

---

# My background?

### Back-end Java/Scala development (type and function signatures)
### Server-side "front-end" generated with dashes of JavaScript

---

# Why GatsbyJS? JavaScript?! NodeJS?!

![inline](assets/friends-enemise-close.jpg)

---

# GatsbyJS GraphCMS Plugin

![inline](assets/graphcms-gatsbyjs.png)

---

# GatsbyJS GraphCMS Plugin

![inline](assets/gatsby-source-graphcms-github.png)

---

# GatsbyJS GraphCMS Plugin

# Tour de code

---

# GatsbyJS GraphCMS Plugin Credits

![inline](assets/gatsby-source-graphcms-github-credits.png)

---

![inline](assets/carmen-marcos-web.png)

---

![inline](assets/carmen-marcos-github.png)

---

# GatsbyJS GraphCMS Plugin

# Lessons learned?

1. GatsbyJS codebase: O Brother! Where art thou TYPES?!
1. NPM: at the end of the day, relase/ship the f* thing
1. GraphQL: introspecting (metadata/types) GraphQL query **results** 
1. GraphCMS: content **hierarchy** a must have when scaling 

---
# Computers

![inline](assets/1280px-Thomas_J_Watson_Sr.jpg)

> "I think there is **a world market for maybe five computers**."
-- Thomas J. Watson, president of IBM, **1943**

---

# Computers?

![inline](assets/02102016_ENIAC_programmers_LA.2e16d0ba.fill-735x490.jpg)

---

# Computers?

![inline](assets/pic016.jpg)

---

# Computers?

![inline](assets/ZXSpectrum48k.jpg)

---

# Computers?

![inline](assets/Ibm_pc_5150.jpg)

---

# Computers?

![inline](assets/blockchian-k5dG--621x414-LiveMint.jpg)

---

# Computers?

![inline](assets/chartoftheday_4546_cloud_infrastructure_market_share_2015_n.jpg)

---

# 5 Computers!

![inline](assets/1280px-Thomas_J_Watson_Sr.jpg)
---

# A CMS just does CRUD, or?

![inline](assets/vectorstock_11234419.jpg)

---

# If all you have is a hammer...

![inline](assets/2001-a-space-odyssey.jpg)

---

![inline](assets/Were-jammin.jpg)

---

# Gentics Mesh: Tour de Force
![inline 100%](assets/gentics-mesh-topics.png)

---

# React Static & React
![inline 100%](assets/react-static-mesh-topics.png)

---

# Talk Main Points
