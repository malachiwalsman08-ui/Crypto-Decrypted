Icons for Crypto Basics

Files created in ./icons:
- icon-coin.svg     # coin/monogram mark (uses accent gradient)
- icon-shield.svg   # shield with accent stroke and inner circle
- icon-circuit.svg  # circuit-style nodes and lines
- icon-spark.svg    # abstract spark/flare with center dot

Design notes
- Colors follow your theme: background #0f1724, text #e6eef6, accent #FFD24C.
- SVGs are square 256x256 and include a rounded background to look good as favicons or in cards.

Usage examples (inline SVG or <img>):
- Inline in HTML (small, scales cleanly):
  <div class="icon"> <!-- will inherit text color if needed -->
    <!-- copy contents of icon-coin.svg here or use object/embed -->
  </div>

- Use as image:
  <img src="icons/icon-coin.svg" alt="coin icon" width="48" height="48">

Converting to PNG/ICO
- ImageMagick (recommended):
  magick convert icons/icon-coin.svg -resize 32x32 icons/favicon-32x32.png
  magick convert icons/icon-coin.svg -resize 16x16 icons/favicon-16x16.png icons/favicon.ico

- Alternatively use an online converter.

Accessibility
- Provide descriptive alt text when using <img>.

If you'd like, I can:
- Add these icons inline in `index.html` as examples (I can add a small "features" section),
- Produce PNG/ICO files for favicons,
- Or change their sizes/colors.
