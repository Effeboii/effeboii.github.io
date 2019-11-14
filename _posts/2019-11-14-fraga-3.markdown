---
layout: post
title:  "Humans and Robots"
date:   2019-11-13 10:50:22 -0600
categories: blog update
permalink: /blog/fraga-3
comments: true
---

Vad är humans.txt?

Det är ett sätt att få veta vilka/vem som ligger bakom webbplatsen.
Det är egentligen bara en textfil med kort information om skaparna, vilka verktyg som används och eventuellt en "shout-out", som tack.

Jag valde att ta med lite kort information, som mitt namn, e-post, skola och säte.
Samt lite information om sidan och vilka verktyg jag har använt mig av.

Vad är robots.txt?

Det är en textfil som bestämmer vad som ska vara åtkomligt eller inte åtkomligt för sökmotorer/sökrobotar.

Jag har valt att blockera åtkomsten för alla robotar på hela sidan.
Genom att sätta "User-agent: *", så väljer jag att det ska beröra alla robotar.
Genom att sen sätta "Disallow: /", så väljer jag att inga sidor på webbplatsen får besökas.
