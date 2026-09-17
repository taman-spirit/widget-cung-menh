# Your natal element

Pick a birth year for the Na Yin element, with its classical colour and direction.

*[Đọc bản tiếng Việt](README.md)*

**See it running:** https://nhatnguyet.org/widget/cung-menh

## Paste these two lines

```html
<div data-widget="cung-menh"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

No account, no API key, nothing to pay.

## What it gives your page

The one personalised widget in the library: the reader picks a birth year and sees their Na Yin element of the Five Phases. The result is remembered for the next visit, stored on the reader's own machine rather than sent to any server.

## Worth knowing before you embed

- The reading describes the Five Phases system, it does not pronounce on your reader. There is no fortune-telling in it.
- The colour and direction are classical convention rather than computed values, and the widget says so in the frame.
- Only the birth year is stored, on your reader's own machine. No day or month, and nothing is sent anywhere.

## The steps

1. Paste the snippet wherever you want it; no further configuration is needed.
2. The reader picks a birth year once, and the widget shows the same result on their next visit.
3. For a narrow frame set data-size to compact and the large colour disc is dropped.

## Where to paste it

**WordPress.** Add a *Custom HTML* block to the post, or a *Text* widget in
the sidebar, and paste both lines there. Do not paste into the ordinary
editor: it will show the code as text instead of running it.

**Wix, Squarespace, Shopify.** Use the *Embed HTML* / *Custom HTML* block.

**Hand-written sites.** Paste it straight where you want the widget. If you
embed several widgets, the `<script>` line only needs to appear once on the
page.

**A note on width.** The widget fits the width of wherever you put it. If that is narrower than 280px, add
`data-size="compact"`; if it is a wide horizontal strip, use
`data-size="wide"`.

## Make it match your page

| Attribute | Values | Meaning |
|---|---|---|
| `data-widget` | `cung-menh` | Required |
| `data-theme` | light or dark | Defaults to light |
| `data-accent` | #b3341f | Accent colour as a 6-digit hex value, to match your own branding |
| `data-lang` | vi or en | Defaults to vi |
| `data-size` | compact, standard or wide | Level of detail for the width you have: compact drops secondary detail, wide lays out horizontally. Defaults to standard |

With every attribute this widget accepts, it looks like this:

```html
<div data-widget="cung-menh" data-theme="dark" data-accent="#1f6f5c" data-lang="en" data-size="compact"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Want to see it for yourself before it goes near your real page? Open
[`vi-du/index.html`](vi-du/index.html) in a browser, nothing to install.

## A few things we ask

- Free for personal and business websites, with no display limit.
- Keep the attribution line at the foot of the widget. That is what you give
  in return for free use.
- Do not embed on gambling, adult, fraudulent sites or anything unlawful
  under Vietnamese law.
- The content is folk knowledge and cultural convention, offered as
  reference, not as health, financial or legal advice.

Full text: [`TERMS.md`](TERMS.md) · [https://nhatnguyet.org/widget/dieu-khoan](https://nhatnguyet.org/widget/dieu-khoan)

## Who we are

Nhat Nguyet (https://nhatnguyet.org) is a Vietnamese reference site for calendrical and
cultural knowledge: the lunar calendar computed for Vietnam's own time zone,
the sexagenary cycle, solar terms, auspicious hours, astrology, feng shui,
and a glossary of terms.

There is one thing we try hard to keep clear, even inside a 300px frame:
which parts are computed, and which are folk convention.

Lunar dates, sexagenary names and solar terms are **computed**. Run the same
calculation and you get the same answer, and we publish the underlying
datasets under CC BY 4.0 so you can check for yourself.

Auspicious hours, Bat Trach directions and Lo Ban rule bands are **cultural
convention**. There are real lookup tables behind them, but they are not
measurements. The widget tells you what the table says; how much weight to
give it is yours to decide.

Where the schools disagree, we say so, rather than quietly picking a side and
presenting it as the only reading.

Open data: [GitHub](https://github.com/taman-spirit/du-lieu-am-lich) ·
[Hugging Face](https://huggingface.co/datasets/nhatnguyet)

## Something not right?

Open an issue in this repository. We do read them.

The whole widget library: [https://nhatnguyet.org/widget](https://nhatnguyet.org/widget)
