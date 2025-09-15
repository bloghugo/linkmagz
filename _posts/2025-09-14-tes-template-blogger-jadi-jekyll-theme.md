---
layout: post
title: "Tes Template Blogger Jadi Jekyll Theme"
date: 2025-09-14 10:00:00 +0700
---

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

Ini adalah artikel **pertama** dengan _Markdown_ di Jekyll.  
Bisa juga tulisan ***tebal miring***.

---

## Tes Gambar
Gambar berikut diambil dari URL dan tampil **responsif** di semua ukuran:

![Blogger Icon](https://upload.wikimedia.org/wikipedia/commons/b/b9/Blogger_icon_2017.svg){:style="max-width:100%; height:auto;"}

---

## Kode Program
Contoh kode di Jekyll (liquid + HTML):

```html
{% raw %}
{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
{% endraw %}
```

---

## Quotes
> Ini adalah contoh kutipan (quotes) menggunakan Markdown.  

---

## Link
Kunjungi [Google](https://www.google.com) untuk mencari informasi lebih banyak.
