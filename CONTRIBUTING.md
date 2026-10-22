# Contributing

Thanks for wanting to add wallpapers. Everything in this repository is
dedicated to the public domain under [CC0 1.0 Universal](LICENSE), and your
contribution will be too. Please read the licensing section before you open a
pull request.

## Licensing: what you agree to

When you submit a contribution (images or text), you dedicate it to the
public domain under CC0 1.0. In practice that means:

- You give up your copyright and related rights in the contribution, worldwide,
  as far as the law allows. Anyone can copy, modify, sell, or redistribute it,
  for any purpose, without asking you and without crediting you.
- Where a full waiver isn't legally possible, CC0 falls back to granting
  everyone an unconditional, irrevocable, royalty-free license to do all of the
  above.
- This can't be taken back later.

You also confirm that:

- The work is entirely your own, or you otherwise have the right to dedicate it
  to the public domain.
- It contains nothing that belongs to someone else: no photos, textures,
  brushes, fonts, icons, logos, or code snippets from other sources, and no
  traced or closely copied artwork.

To make this explicit, include this line in your pull request description:

> I dedicate this contribution to the public domain under CC0 1.0 Universal,
> and I confirm it is my own work and contains no third-party material.

We can't accept a contribution without it.

This is a plain-language summary, not legal advice. The [LICENSE](LICENSE)
file has the full legal text.

## What we can't accept

Every file here has to be something we can safely release into the public
domain, so we turn down:

- Third-party assets of any kind, even ones under permissive licenses such as
  the SIL Open Font License, CC BY, or MIT. Those licenses come with
  conditions, and CC0 has none.
- Text set in an existing font. Some countries protect typeface designs, and
  font licenses add their own terms. If your wallpaper has text, draw the
  letters yourself.
- Output from AI image generators. We can't check where it came from, and its
  copyright status is still unsettled.
- Real photographs or real-world data, such as map elevation data or telescope
  images, unless you made them yourself and say so.
- Imitations of a specific artist, an existing artwork, a brand, a logo, or an
  operating system's default wallpaper.

## What to submit

Submit finished images. You can make them with your own code, by hand in a
drawing or painting program, or any other way, as long as everything in them
is your own work. You don't need to send the code or project files.

Images go in a folder per style:

```
wallpapers/<style>/<style>-NN-<descriptor>.png
```

For example, `wallpapers/minimal/minimal-04-dune-sage.png`. You can add new
variants to an existing style or start a new one. If you start a new style,
add a row for it to the table in the main README.

Technical requirements:

- PNG format, 3840x2160 pixels.
- Lowercase file names in the pattern above, numbered after the last existing
  image in that style.
- Don't change existing images. Add new ones instead.

## Quality bar

Wallpapers sit behind icons and windows all day, so they should be calm and
free of rendering artifacts:

- No jagged edges.
- No visible banding in gradients. A little dither or grain helps.
- No clipped highlights.
- Look at your image at 100% zoom before submitting, not only as a thumbnail.
- Keep files reasonably small. Flat colour compresses well; heavy grain doesn't.

## Submitting

1. Fork the repository and create a branch.
2. Add your images to the right `wallpapers/<style>/` folder.
3. Open a pull request. Include the CC0 statement above and a sentence about
   what you added.
