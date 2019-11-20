---
layout: post
title:  "doclib a CLI for paper management"
date:   2019-11-20
categories: jekyll update
type: post
kind: "post"

---

A while ago I got sick of using mendeley, and zotero, and whatever else I could find out there for managing my articles (pdf documents). So I thought of what I want a document management system to have:

- a simple interface
- files should be stored locally
- vim keybindings
- keep notes on documents
- easily searchable

With those goals in mind I set out to write [doclib](https://github.com/crvs/doclib). I have essentially drawn inspiration from [todo.txt](https://github.com/todotxt/todo.txt) in the sense that all the formats should be as future-proof and portable as possible. This led me to give up on (direct) pdf annotation which would require me to choose a format and instead keep a plain-text notes file for each document.

To make it usable I have also added a short manpage that explains every available sub-command and how they operate. It builds on very few things, so it should be quite portable. Any comments or feedbacks are welcome!

