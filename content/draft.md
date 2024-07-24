---
title: 'OCR on PDfs'
description: 'Implementation of OCR for PDF data extraction'
pubDate: '7/24/2024'
tags: ['PDF', 'OCR', 'Optical Character Recognition', 'Golang', 'Text from Image']
heroImage: '/placeholder.jpg'
---
Problem: Getting text from PDF to csv 
Possible Solutions: Parse Text from pdf, OCR
Solution I chose to impplement: OCR
Why: Previously used pyPDF, a python library for parsing text from the PDF, in this case it did not work due to two column data on a pdf page, needed a different approach

Found repo that implements ocr service in golang:
https://github.com/oscarpfernandez/go-tesseract-ocr-service

...

### Definitions
OCR (Optical Character Recognition): 
the identification of printed characters using photoelectric devices and computer software
