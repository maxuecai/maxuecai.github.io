---
title: "Manage blog comments with Giscus"
tags:
    - user manual
    - utility
    - giscus
date: "2024-02-03"
thumbnail: "https://i.ibb.co/V9j2Qsg/giscus-Wl0-X3byd-az-U68-1.webp"
bookmark: true
---

# Research
---

## Create a github repo

You need a GitHub repository first. If you gonna use *GitHub Pages* for hosting your website, you can choose the corresponding repository (i.e., `[userID].github.io`)

The repository should be **public**, otherwise visitors will not be able to view the discussion.

## Turn on Discussion feature

In your GitHub repository Settings, make sure that `General` > `Features` > `Discussions` feature is enabled.

![Discussion](https://i.ibb.co/P1FV02D/giscus-00.png)

# Notes and Slides
---
1. Analytic Geometry and Homotopy Groups  of the $K(n)$-Local Sphere
 SUSTech Graduate Topology Seminar, 2024. [PDF](files/K(n)sphere.pdf)
2. Derived Level Structures
SUSTech Graduate Topology Seminar, 2024. [PDF](files/Derived_Level_Talk.pdf)     
3. Formal Moduli Problems
SUSTech Graduate Topology Seminar, 2023. [PDF](files/FMP.pdf)
4. An Overview of Chromatic Homotopy Theory
SUSTech Graduate Topology Seminar, 2022. [PDF](files/cht.pdf) 
5. Methods of Spectral Algebraic Geometry  in Chromatic Homotopy Theory
SUSTech Graduate Topology Seminar, 2022. [PDF](files/sag_cht.pdf)
      

## Copy  `_config.yml`

Now, you get the giscus script. Copy the four properties marked with a red box as shown below:

![](https://i.ibb.co/Z154x8P/giscus-04.png)

Paste those values to `_config.yml` placed in the root directory.

```
# External API
giscus_repo: "[ENTER REPO HERE]"
giscus_repoId: "[ENTER REPO ID HERE]"
giscus_category: "[ENTER CATEGORY NAME HERE]"
giscus_categoryId: "[ENTER CATEGORY ID HERE]"
```
