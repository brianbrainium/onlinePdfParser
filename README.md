# onlinePdfParser

This project contains a simple HTML/JavaScript page that demonstrates how to extract
sections from a PDF using the document's outline (table of contents). Open
`index.html` in a modern browser and select a PDF file to view its outline and
extract sections as separate PDF files.

The implementation uses [PDF.js](https://mozilla.github.io/pdf.js/) for reading
the outline and [pdf-lib](https://github.com/Hopding/pdf-lib) for writing new
PDF files.

Note: Some features from the original Python version are simplified.
The browser version now supports exporting each section as either PDF or
plain text, and can automatically iterate through all sections to export
them into a ZIP archive that mirrors the document outline.

For a minimal demonstration of the ZIP download logic on its own, open
`ziptest.html` in your browser. This small page creates a test archive
when you click the **Make ZIP** button, allowing you to verify that the
JSZip-based download works independently from the main application.

For the current status of planned functionality, see [docs/features.md](docs/features.md). A tentative implementation sequence is outlined in [docs/roadmap.md](docs/roadmap.md).

## License

This project is licensed under the [MIT License](LICENSE).
