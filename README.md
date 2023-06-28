<div align="center">
  
# Tech Fiddle PDF API

[![GitHub](https://img.shields.io/github/license/Comp-Labs/PDF-API)](https://github.com/BetaHuhn/vercel-pdf-converter/blob/master/LICENSE) ![Version](https://img.shields.io/github/package-json/v/Comp-Labs/PDF-API/main) ![Dependencies' Status](https://img.shields.io/librariesio/github/Comp-Labs/comp-labs-website)

Vercel function which generates PDFs from websites. For Tech Fiddle internal use only.

</div>

## 👋 Introduction

This repo contains the code for a simple [Vercel](https://vercel.com) function that generates a PDF file from any webpage using a [headless Chrome instance](https://github.com/puppeteer/puppeteer).

## 📚 Usage

You can use it by placing your function's domain in front of any URL:

```
https://pdf.techfiddle.io/https://github.com/BetaHuhn/vercel-pdf-converter
```

The function will then generate a PDF of that URL and return it as a downloadable file.

Here is how this GitHub Page looks as a PDF:

![example](https://cdn.mxis.ch/assets/vercel-pdf-converter/preview.png)

## ❔ About

This project was developed by ([@betahuhn](https://github.com/BetaHuhn)) originally.

## License

Copyright 2023 Tech Fiddle & 2020 Maximilian Schiller

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
