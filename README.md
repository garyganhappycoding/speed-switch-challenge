# Speed Switch Challenge

PSY 111 Creative Exhibition booth (HELP University) — "Are You Banana or Coconut?"

A bilingual picture-naming game that measures language switch costs (Meuter & Allport, 1999; Green, 1998).
Visitors warm up in their weaker language, name colour-cued pictures in their strongest (blue) and weaker (red) language,
and see their results, including whether switching back into their strongest language cost more extra time.

- Single static page: `index.html` (no build step)
- Visitor results are saved to a shared Supabase database (table `speedswitch_visitors`), so every device that opens the link adds to the same booth results. Results are also kept on the device and uploaded automatically if the internet drops.
- Names and courses are only visible on the Booth results page after entering the booth PIN. Visitors' own results pages only see anonymous scores from other visitors.
- Use **Copy data as CSV** on the Booth results page to export everything.
