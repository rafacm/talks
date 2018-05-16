footer: rafael cordones | @rafacm | JAMming with Gentics Mesh, Reat Static and Amazon S3 | We Are Developers Workshops @ APA-IT
slidenumbers: true

![inline](assets/gentics-mesh-react-static-amazon-s3-logos.png)

# JAMming with Gentics Mesh, Reat Static and Amazon S3
#### We Are Developers /  Workshops @ APA-IT / Vienna, May 16th, 2018

---

# Workshop Agenda 1/2

1. Talk: how did we get here? ~10 min.
1. Gentics Mesh: Tour de Force ~15 min.
1. React & React Static (Reader's Digest Version) ~10 min.
1. Amazon S3 ~5 min.
1. React Static Gentics Mesh Example ~10 min.
1. Let's play! 

---

# Intro talk

---

# Credits
![inline](assets/the-front-end-strickes-back.png)

---

# Who are you?

![inline](assets/wall-e-and-eve.jpg)

---

# Topics
1. Monolithic CMSs up to now where CMS = Content Management System
1. Use-cases for API-first / headless CMSs where CMS = Content Micro-Service 
1. Mesh unique features and how they compare to others (GraphCMS, Contentful, ...)
1. Use-cases for "statically" generated websites
1. Progressive Static-Site generators: React Static vs GatsbyJs

--- 

# WeAreDevelopers

![inline](assets/wad-people-code-future.jpg)

---

# Past

---

# Hosted CMSs

![left](assets/theUsualSuspects_1416603356.jpg)

# Spectrum of choices:

1. Blogs, websites, communities, ...
1. Full-stack = back-end + front-end
1. Many offer REST APIs
1. ...
1. They are actually **development platforms**

---

# The Anatomy of a CMS

![left](assets/Rembrandt_Harmensz._van_Rijn_007.jpg)

1. Content modeling, versioning, ...
1. Content editing, versioning, ...
1. Querying / search
1. ACLs: who can do what
1. Audit: who did what when
1. Content rendering (frameworks, libraries, ...)
1. Content analytics, personalization, SEO, ...
1. ...

---

# We need a "website"

![left](assets/leonardo-da-vinci.jpg)

> "Software is never finished, just abandoned"
-- Leonardo Dev Vinci

# The website initial **successful website** turns into ...
# ... a **web app**.

---

# The Neutron Dance

![left](assets/neutron-dance.png)

> And it's hard to say
> Just **how some [content] never changes**
> And it's hard to find
> Any **strength to draw the line**
> Oh I'm just burning doin' the neutron dance
> I'm just burning doin' the neutron dance
-- "Neutron Dance" The Pointer Sisters 

---

# The Neutron Dance

![left](assets/neutron-dance.png)

1. The half-life of content is considerable higher than that of its presentation.
1. Content **editing** and content **presentation** are different concerns
1. Developers need to learn *each* CMS *APIs* and *framework*
1. Editors need to *learn* the specific CMS administration interface
1. Customers need to find developers for the implementation... every 2 years

---

![inline](assets/800px-Kernspaltung.svg.png)

# CMS -> Back-end + Front-end

---

# Back-end?

![inline](assets/2000px-Nuclear_fission_chain_reaction.svg.png)

---

# Back-end?

![inline](assets/1_oZi6DlwCAzCuMfrvp29KBg.png)

---

# Back-end?

![inline](assets/cloud.png)

---

# The CMS (Content Management System) is dead!

![left](assets/louis16_execution.jpg)

---
 
# Long Live the CMS (Content Micro-Service)!
# a.k.a. Headless CMS

![left](assets/Louis_XVI_-_Execution.jpg)

---

# Headless CMS

![inline](assets/headlesscms.png)

--- 

# JAMstack

![inline](assets/jamstack.png)

---

# The Shape of Things to Come

![left](assets/Shape_of_things_to_come_dust_jacket.jpg)

## API-driven CMSs:
1. [contentful](https://www.contentful.com/)
1. [prismic](https://prismic.io)
1. [GraphCMS](https://graphcms.com/)
1. [GENTICS Mesh](https://getmesh.io) (Made in Vienna!)
1. ...

---

# O Content, where art thou?

![inline](assets/manofconstantsorrow_obrotherwhereartthou.jpg)

---

# O Content, where art thou?

### "I Am A [Dev] of Constant Sorrow" --- Soggy Bottom [Devs]

1. Proliferation of content repository APIs adds overhead for developers to learn about the **semantics** of the API
1. One API to rule them all?

![inline](assets/graphql.png)

---

# GraphCMS

![inline](assets/graphcms-web.png)

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

# Why headless CMS?

![inline](assets/headlesscms.png)

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

# A CMS just does CRUD, or?

![inline](assets/vectorstock_11234419.jpg)

---

# If all you have is a hammer...

![inline](assets/2001-a-space-odyssey.jpg)

---

# Yeah, well, that's just like, your opinion, man

![inline](assets/big-lebowski-opinion.jpg)

---

# What's yours?!

![inline](assets/spies_like_us_01_641x383.jpg)

---

![inline](assets/Were-jammin.jpg)

---

---

# Gentics Mesh: Tour de Force
![inline](assets/gentics-mesh-topics.png)

---

# React & React Static (Reader's Digest Version)
1. Components: a function by another name

---

## Reader's Digest Version


#
---

# Talk Main Points
