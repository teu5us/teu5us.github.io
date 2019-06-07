---
layout: default
title: Конвертируем документы с помощью Pandoc
permalink: /pandoc/
---

# Конвертируем из Word в Markdown

`pandoc -f docx -t markdown --wrap=none -s <file>.docx -o <file>.md`

# Конвертируем из Markdown в Word

`pandoc -f markdown -t docx --reference-doc=<template-file>.docx --toc -o <new-file>.docx`
