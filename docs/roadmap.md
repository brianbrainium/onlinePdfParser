# Roadmap

This document lists the planned features in the order they are expected to be implemented. Each step builds on previous work and expands the functionality of the browser-based PDF section extractor.

1. **Browser-memory check & size advice**
   - Warn the user when a PDF may exceed available memory
   - Suggest splitting large files before upload

2. **Upload progress bar**
   - Show real-time feedback while loading the PDF
   - Helps users understand how long the process will take

3. **Collapsible TOC tree view**
   - Display the table of contents in an expandable tree
   - Makes navigation easier for large documents

4. **Multi-select / bulk selection**
   - Allow choosing multiple sections at once
   - Enables batch extraction in a single operation

5. **Full-document "iterate all" option**
   - Iterate through every section automatically
   - Useful for extracting all parts with one command

6. **Export format choice (PDF or text)**
   - Add text-output support alongside PDF export
   - Provide options to save plain text versions of sections

7. **Zip export with TOC-based folder structure**
   - Package extracted sections into a ZIP archive
   - Mirror the original outline hierarchy inside the archive

See [features.md](features.md) for the current implementation status of each feature.
