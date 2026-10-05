CloudPage preview isolation (paste each file into its own new CloudPage, one at a time)

1. 01-html-only
   Preview must work. If it fails, fix CloudPages setup before using push_adv_prf.

2. 02-amp-only
   If 01 works but 02 fails, AMPscript is blocked or paste corrupted the %%[ tags.

3. 03-ssjs-only
   If 01 works but 03 fails, SSJS / Platform.Load is the issue in this Business Unit.

4. push_adv_prf_diagnostic (repo root)
   DE connectivity check after 01–03 pass.

SFMC checklist when preview always shows "An error occurred while previewing this content":
- Web Studio > CloudPages (not Email Studio)
- New collection or use existing; associate a domain; publish the collection/site
- Asset type: CloudPage, code format HTML
- Paste from GitHub Raw URL, not the rendered web page
- Full replace of editor content; save; then preview

Publish often works when preview does not. After publish, open the live URL from the collection.
