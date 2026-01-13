# README

A Jupyter notebook that logs into the GESIS Eurobarometer Data Service, iterates through all “Eurobarometer …” projects up to the 2016 cutoff, and opens each study’s “Downloads → Datasets” modal.

It then downloads only the .dta (Stata) files into a structured local/Drive folder, skipping already-downloaded items via a CSV manifest and falling back to click-based downloads when direct requests return an HTML interstitial.
