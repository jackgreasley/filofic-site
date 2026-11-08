---
layout: default
title: FiloFic Release Notes
---

# What's new in FiloFic

The newest release comes first. Each beta in TestFlight gets its own section here, published
at https://jackgreasley.github.io/filofic-site/release-notes/.

## Coming in the next beta

- **A steady scroll bar.** While you scroll, a slim bar at the edge shows how far through the
  whole fic you are. It stays the same size and never jumps as chapters load. EPUBs had no
  scroll bar at all before, and other fics had one that grew, shrank and jumped.
- **Pictures full size.** Hold your finger on a picture in an EPUB to see it on its own, then
  pinch or double-tap to zoom in.
- **Credits.** Settings › About › Acknowledgements now lists every piece of open-source
  software inside the EPUB reader.

## Beta 202611081338 · 8 November 2026

**EPUBs now look the way they were made.** They're shown by Readium, the open-source engine
many reading apps use:

- each book keeps its own styling, pictures, fonts, poems and tables;
- footnotes open in a small sheet over the page;
- links inside the book take you to the right place;
- scrolling runs straight on from one chapter into the next, with a gap between them, as in
  Apple Books (you can switch to turning pages in each fic's reading settings);
- the original EPUB is kept, compressed, inside your encrypted library, and a book still can't
  fetch anything from the internet.

To get this for fics you already have, go to Settings › Clear Library, then import your EPUBs
again with **+ › Import from Files › EPUBs Only**. Fics imported before this beta don't have
their original file, so they open in FiloFic's own reader, and sharing one gives a copy
rebuilt from its text, without its pictures.

**Also fixed:**

- On iPad, Clear Library closes Settings first, so you land on your fresh library.
- On iPad, a reading milestone opens Settings at your reading stats.

## Beta 202611080859 · 8 November 2026

- **Reading:** scrolling runs on from one chapter into the next. Text is justified and
  hyphenated, with spacing like Apple Books and bold chapter headings. AO3's notes are set apart
  from the story, and the title page lists its tags with each label above its value. You can
  choose justified or ragged text in the reading settings.
- **Links:** web links in a fic, like AO3's "leave feedback", open in your own browser.
  FiloFic itself still never goes online.
- **Importing:** an import keeps going when you leave the app, and picks up where it stopped
  if it's interrupted. You can import just EPUBs, PDFs or text files, and see your library
  fill as the fics arrive. Anything already in your library, or in a format FiloFic can't
  read, is skipped and listed.
- **Fandoms:** a fic listed in several fandoms appears under each of them. Fandoms and ships
  can be merged and renamed (Fandoms › Merge). The Browse button is now called Fandoms.
- **Search:** results are grouped behind pills, with titles and authors first. Quoted phrases
  match exactly, and FiloFic Search needs everything you ask for, so "spicy horror" means
  both.
- **Settings:** Clear Library, at the bottom, deletes everything and asks twice first.
- **Fixed:** typing in search could freeze the app; swiping to delete a tag didn't work; the
  same fic could be imported twice.

## First betas · 7 November 2026

The first versions of FiloFic, in builds 202611071949 to 202611080549:

- an encrypted library that opens only with Face ID or Touch ID, and never goes online;
- importing EPUB, PDF, HTML, Markdown and text files, or whole folders, with the fandom, ship,
  rating, tags, summary and dates read from AO3's headers;
- fandom, ship and mood suggested by Apple Intelligence on the device, where it's available;
- browsing by fandom, then ship, then mood, and a shelf of summaries to skim;
- FiloFic Search: describe what you'd like to read in your own words;
- searching inside every fic, with the passage highlighted;
- your own rating scales, each with its own emoji;
- a reader with paper, light and dark themes, your choice of font and size, and words read
  counted with milestones;
- sharing a fic as an EPUB, or sending it to your Kindle.
