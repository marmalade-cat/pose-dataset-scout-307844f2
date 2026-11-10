PoseDataset-Scout

Small prototype single-file tool (index.html) that fetches given URLs, looks for likely dataset links and simple embedded dataset patterns, and produces a CSV report and an on-page summary. Designed as a browser-based prototype; use a CORS proxy if target sites block cross-origin requests. No dependencies.

Usage: open index.html in a modern browser. Edit the Targets textarea to list URLs to scan, optionally set a CORS proxy. Click "Run Scan". Download CSV report when ready.

Limitations: exploratory prototype. Detection is heuristic: file-extension link hints, data: URLs, and simple JavaScript array patterns. Does not execute remote scripts or follow complex AJAX flows. Treat findings as leads, not authoritative extraction.