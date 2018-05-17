footer: rafael cordones | @rafacm | JAMming with Gentics Mesh, Reat Static and Amazon S3 | We Are Developers Workshops @ APA-IT
slidenumbers: true

![inline](assets/gentics-mesh-react-static-amazon-s3-logos.png)

# JAMming with Gentics Mesh, React Static and Amazon S3
#### We Are Developers /  Workshops @ APA-IT / Vienna, May 16th, 2018

---

# Agenda

1. Teaser talk
1. Gentics Mesh: tour _de_ features 
1. Break (10 min.)
1. React Static & React 
1. Features implementation
1. Amazon S3 
1. Wrap-up

---

# Teaser talk

---

# Credits
![inline](assets/the-front-end-strickes-back.png)

---

# Web Content Projects
![left 35%](assets/screenshot-community-2.png)

1. (Internal) content publication
2. (External) user generated content
3. 6-12 months projects
2. 10x of page types
2. 100x of components
2. 1,000x of content items
2. 100,000x of users

Implemented on a **monolithic CMS**.

---

# The content stays the same 
![left 35%](assets/screenshot-community-2.png)

Web **front-end design** 
<br/>
**changes** every 2 years but 
<br/>
the **content remains the same**

---

# Thinking (and implementing!) in **components**
![inline](assets/top-solution-authors.png)

---

# SEO, SEO, SEO
![left 50%](assets/carmen-marcos-art-page-speed.png)

1. Page speed: Time to first byte (TTFB)
2. Light-weight markup
2. Pre-rendered markup vs render markup per request
3. Nice & structured URLs
4. Breadcrumbs with metadata
5. ...

---

# The Anatomy of a CMS
![left 35%](assets/Rembrandt_Harmensz._van_Rijn_007.jpg)

1. Content modeling (and migrations)
1. Content creation/editing
1. Querying / search
1. Permissions: who can do what
1. **Content rendering (frameworks, libraries, ...)**
1. ...

---

# Content rendering (frameworks, libraries, ...)
![left 50%](assets/que-sera-sera.jpg)

What if...

1. CMS back-end & front-end were completely separated?
1. Content could be managed independently of the front-end?
1. Content could be accessed just via APIs
1. Front-end could be developed with any tech or framework?

... the **CMS would just focus on content**

---

# The CMS* is dead!
## * Content **Management System**

![left](assets/louis16_execution.jpg)

---
 
# The CMS* is dead!
## * Content **Management System**
# Long Live the CMS*
## * Content **Micro-Service**

## a.k.a. Headless CMS
## a.k.a. API-driven CMS

![left](assets/Louis_XVI_-_Execution.jpg)

---

# The content stays the same
![left 60%](assets/headlesscms-gentics-mesh.png)

Headless / API-first CMSs

1. [contentful](https://www.contentful.com/) (Saas)
1. [prismic](https://prismic.io) (Saas)
1. [GraphCMS](https://graphcms.com/) (Saas)
1. [Contenta CMS](https://www.contentacms.org/) (Open-Source)
1. ...
1. [Gentics Mesh](https://getmesh.io) (Open-Source)

... all with different **content APIs**!

---

# Content APIs: O Content, where art thou?

![inline 90%](assets/manofconstantsorrow_obrotherwhereartthou.jpg)

> "I Am A [Dev] of Constant Sorrow" 
-- Soggy Bottom [Devs]

---

# Content APIs: O Content, where art thou?
![left 70%](assets/graphql-screenshot.png)

1. Proliferation of content repository APIs adds overhead for developers to learn about the **semantics** of the API
1. One query API language to rule them all?
1. **GraphQL support is a MUST HAVE.**

---

# Gentics Mesh

![left 50%](assets/getmesh-website-screenshot.png)

1. (Hierarchical) **content tree**: scalability! 
1. APIs: REST, **GraphQL**, ElasticSearch 
1. **Image manipulation**: via API & via management UI
3. **Multi-lingual** support
4. On-(cloud)-premise: **own your content**! 
5. Users, groups, roles & permissions
6. ...

---

# React: it's components all the way down!
![inline](assets/top-solution-authors-components.png)

---

# React Static: my gateway drug to React
![inline](assets/react-phases.jpg)

---

# SEO, SEO, SEO
![left 15%](assets/seo.png)

JAMstack

1. **J**avaScript: the language of the web
2. **A**PIs: to access content
3. **M**arkup: pre-rendered HTML markup

Amazon S3 for content delivery

1. Managed, scalable and cheap
 
/ **The web browser is the new web server!** /

---

# Main takeways (1/2)
![left 75%](assets/back-end.png)

As a back-end developer:

1. Do you build your own search engine, business process engine, ...? 
No you don't.
1. Do you build your own content management infrastructure? 
You should not.

---

# Main takeways (2/2)
![left 75%](assets/front-end.png)

As a front-end developer

1. Abstract away the management aspect of content
1. Focus on the front-end implementation with freedom of choice

---

# The Project
![left 45%](assets/carmen-marcos-art-screenshot.png)

1. ...
2. prismic.io + (Scala) Play! Framework
1. ...
2. Contentful + (JavaScript) Angular 1.x
1. ...
2. GraphCMS + (JavaScript) GatsbyJS
1. **Gentics Mesh + (JavaScript) React Static**

---

# Any questions?!

![inline](assets/spies_like_us_01_641x383.jpg)

---

# Gentics Mesh: Tour de Features
![inline 110%](assets/gentics-mesh-topics.png)

---

# React Static & React
![inline 100%](assets/react-static-mesh-topics.png)

---

# Amazon S3 for website hosting
![left 40%](assets/amazon-s3-website-hosting.png)

1. S3 is the static web server
1. S3 is fully managed and scales
1. (Optionally) add CDN capabilities with CloudFront
 
--- 