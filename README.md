# DS 115 Day 5: Building Your BYU Experience

## Updated lecture, October 12, 2026

The Quarto source (`day5-slides.qmd`) and the published website (`docs/day5-slides.html`) include the revised lecture. The slides introduce clubs, research, and informational interviews before the instructor's examples; the conversations slide now offers open-ended topics; and the past-events discussion includes an original BYU research conference flyer and a Statistics Club event.

Quarto website and RevealJS lecture slides. The first slide reviews Day 4. The slides include presenter notes with timings, discussion guidance, story prompts, and source links. The examples in the event discussion are real past BYU events, with their dates shown. One slide attempts to display the actual 2025 BYU Student Research Conference flyer from the BYU website. If BYU blocks the image in a browser, the slide shows a link to the official flyer page instead.

## Preview

Open `docs/index.html` for the site or `docs/day5-slides.html` for the deck. The included `docs/` files can be published directly with GitHub Pages.

## Edit and rebuild

Install Quarto, then run:

```bash
quarto render
```

Quarto writes the site to `docs/`. In repository settings, select GitHub Pages **Deploy from a branch**, your chosen branch, and the **/docs** folder.

`index.qmd` is the site home page, `day5-slides.qmd` is the lecture, and `slides.css` controls the deck's look. Presenter notes can be opened with `S` in the deck. The instructor story slides contain prompts rather than invented details.

This package also includes a prebuilt `docs/` preview because Quarto was not installed in the creation environment. The prebuilt deck uses the same local RevealJS assets and content. The original event flyer requires an online connection. Rebuilding with Quarto generates its own RevealJS output.
