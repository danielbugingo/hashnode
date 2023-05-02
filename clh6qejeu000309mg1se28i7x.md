---
title: "Why Is The UTM Zone "36M" And Not "36S""
seoTitle: "WHY IS THE UTM ZONE "36M" AND NOT "36S""
seoDescription: "Learn about the UTM coordinate system and what the "M" suffix means in zone 36M, which can cause confusion for GPS users in the southern hemisphere."
datePublished: Tue May 02 2023 20:38:11 GMT+0000 (Coordinated Universal Time)
cuid: clh6qejeu000309mg1se28i7x
slug: why-is-the-utm-zone-36m-and-not-36s
canonical: https://www.linkedin.com/pulse/why-utm-zone-36m-36s-daniel-bugingo/
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1683043083898/041440d2-17f3-441c-af23-90c63d985753.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1683059260969/3b922a20-65d4-468f-b62f-3ed56ce68875.png
tags: gis, geography, utm-zoning, coordinate-systems, coordinate-reference-syste

---

### Introduction

A colleague of mine wanted to know what the letter "**M"** meant in the **UTM zone 36M** as usually seen especially while picking GPS coordinates. I felt the need to clarify even for anyone else that may want to know.

![UTM Zone 36M Coordinates](https://cdn.hashnode.com/res/hashnode/image/upload/v1683056967327/65881831-543a-4e1a-835c-235baaedc659.png align="center")

It is very clear where the confusion comes from especially for regions where the Equator passes. See, usually, when picking GPS coordinates from anywhere above (North of) the equator (Latitude 0) the UTM Zone will include a suffix "**N**" **(36N)** a notation that most people take for North thereby expecting coordinates picked below (South of) the Equator to have the suffix "**S**" (36S). But instead, the coordinates appear with a suffix "**M**" (36M) for example ***226681 E***\*,\* ***989241 N*** ***36M.***

### How the zoning comes about.

The UTM system is divided into 60 zones and each zone is further divided into 10 bands south of the equator and 10 bands north of the equator making 20 rows of latitude. This makes a grid of 60 zones and 20 bands. The 20 bands in each UTM zone are each identified by an alphabetical notation (letter) starting from **C** in the extreme south of the equator to **X** in the extreme north of the equator arranged in the same alphabetical order.

### Further explanations

The simple explanation is that the "**M**" or "**N**" suffixes are just notations used to further identify a given segment or area on a particular UTM zone. For example 36N or 36M and 35N or 35M for the case of Uganda. The "**N"** does not necessarily mean the Northern Hemisphere although it is literally found north of the equator as illustrated in the image below.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1683058700507/3db37b37-09e4-4c3a-a0a4-64388265cf91.jpeg align="center")

### Conclusion

So every time the suffix "**M" appears on your UTM zone**, you are actually standing south of the Equator. All GPS devices are programmed to indicate the UTM zone and its band notation of that particular zone. You can also follow the link for an in-depth explanation. [Universal Transverse Mercator coordinate system - Wikipedia](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system). Also, find attached the illustration image for visual guides.