# pdf2text-ocr

**Forked from [racosa/pdf2text-ocr](https://github.com/racosa/pdf2text-ocr)**

[pdf2text-ocr](https://racosa.github.io/pdf2text-ocr/) is a simple tool for converting PDF to text using OCR. Files are converted locally in the browser and are never uploaded to external servers. You can also save the converted text to a `.txt` file.

It can be useful if you are getting gibberish when copying and pasting text from PDF ([example](https://superuser.com/questions/137824/pdf-has-garbled-text-when-copy-pasting)), specially if you don't want to or cannot use a cloud-based solution.

## How it works

Each page of the PDF is converted to an image using [PDF.js](https://mozilla.github.io/pdf.js/) and each image is converted to text using [Tesseract.js](https://github.com/naptha/tesseract.js). The results are displayed in the browser allowing users to copy the text, or save to a `.txt` file.
