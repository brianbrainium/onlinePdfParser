# onlinePdfParser

This project contains a simple HTML/JavaScript page that demonstrates how to extract
sections from a PDF using the document's outline (table of contents). Open
`index.html` in a modern browser and select a PDF file to view its outline and
extract sections as separate PDF files.

The implementation uses [PDF.js](https://mozilla.github.io/pdf.js/) for reading
the outline and [pdf-lib](https://github.com/Hopding/pdf-lib) for writing new
PDF files.

Note: Some features from the original Python version (such as accurate page
range detection or text extraction) are simplified or marked as TODO in the
JavaScript version.

For the current status of planned functionality, see [docs/features.md](docs/features.md). A tentative implementation sequence is outlined in [docs/roadmap.md](docs/roadmap.md).

