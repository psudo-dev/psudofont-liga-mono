![psudoFont Liga Mono](./img/psudoFont_Liga_Mono.png)

## V.2.0.0

I was naive... I thought I wouldn't actually edit and design glyphs myself, but I was wrong - I underestimated my itch... So here we are, a new version with a lot redesigned characters!

I previously complained that I liked `Menlo/Meslo` but I wanted to make it a bit thinner - like `IBM Plex Mono/Lilex`. So I went ahead and redesigned a lot of glyphs to make it thinner, while still keeping `Menlo/Meslo`'s overall style.

So, now, the `psudoFont Liga Mono Family` is much more cohesive and consistent and now I can say I actually designed it too - not just a fused together Font Family.

## V.1.0.0

I wanted to use `Menlo/Meslo Regular` but I also wanted `IBM Plex Mono/Lilex Italic`... So what if I mixed and matched these two together?

And that's what I did.

Like so many other things, it started with an itch, and thus, this Frankenstein Font was born. It's aliiiiveeee!

![Hourglass Example](./img/typescript_sample.png)
<small>(Nebula Oni Theme: Hourglass)</small>

## psudoFont Liga Mono

This font has two different weights: Regular/Italic (`400`) and Bold/Bold Italic (`700`).

`Regular` and `Italic` have a lot of redesigned glyphs to make them match better together. `Bold` and `Bold Italic` are just a bold version of `Menlo/Meslo` because there was no point in making them thinner and their design already matched the other two - plus, in programming, bold text is not that common.

### Installation

1. [Download](https://github.com/psudo-dev/psudofont-liga-mono/releases/download/v.2.0.0/psudoFont_Liga_Mono.zip) and Unzip the file.
2. Install the font:
   - Windows: Select all font files in the variable folder, right-click and click Install from the menu.
   - Mac: Select all font files in the variable folder and double-click them and Install.

### Visual Studio Code

1. Go to `File` > `Preferences` > `Settings`.
2. Search for `Font Family`.
3. Add `psudoFont Liga Mono` to the list of font families.
4. To enable `ligatures`, search for `Font Ligatures` and edit the `settings.json` file by adding the following line:

   ```json
   "editor.fontLigatures": true
   ```

## Motivation

I've tried several different fonts over the years but I kept using [Meslo](https://github.com/andreberg/Meslo-Font) as my go-to font. For the past few years I've been using the version with ligatures, `Liga Meslo LG M DZ` - which also includes `Powerline` for the Terminal.

I came across `IBM Plex Mono`, I liked its x-height to base ratio, but it wasn't quite it for me. On the other hand, its `italic` was quite different from its `regular` style, it looked elegant, it made me interested in testing it.

So I tried using [Lilex](https://github.com/mishamyrt/Lilex) for a bit - which is based on `IBM Plex Mono` but with ligatures - therefore the name, Ligature Plex, Lilex, or so I think.

I liked `Menlo/Meslo`'s style, but I wanted it to be a bit thinner - like `IBM Plex Mono/Lilex`. But I also liked `IBM Plex Mono/Lilex`'s `italic` style - except for just a few characters. So I tried to redesign and edit it in a way that could be seen a seamless blend of what I really wanted, therefore this can be called a new font family.

## Design Choices

In the version `V.1.0.0` I just fused together both fonts, using `Meslo Regular` and `Lilex Italic` - while also using `Bold` and `Bold Italic` from `Meslo`. And I thought I would stop there...

But now, in version `V.2.0.0`, I redesigned a lot of glyphs, I used `Lilex` as a base, since I liked the fact that it was thinner, but using `Meslo`'s style as reference.

Then I redesigned some `italic` glyphs to make them match better with the `regular` style. Every character that I didn't like from `Lilex`, I adjusted it - even some details that you can only see in the vector files.

I kept some of the `Lilex` stylistic choices, like the `finial` angle, the beginning of the `bowl`, the thickness of the `stem` but also some measurements and proportions in a way that it would still match the other glyphs that I didn't change. I also adjusted some right-angled parts into rounded curves. Everything that I felt like it would make the font family more cohesive and consistent throughout all the different weights and styles.

This is still within the initial idea of mixing and matching two different fonts, taking the parts that I like from each of them, but this time, instead of just putting them together as-is, I went a few steps further, making this font family something different from the fonts that inspired it, but still keeping the essence and style of what I liked from each of them.

![Hourglass Example](./img/python_sample.png)
<small>(Nebula Oni Theme: Cerberus)</small>

## License

This project is licensed under the SIL Open Font License, Version 1.1. See the [LICENSE](./LICENSE) file for details.

## Credits

The version that I based on for Meslo is called `Liga Meslo LG M DZ`. It's a patched version of a patched version. It was patched to include `Powerline` glyphs, and then it was patched again to include ligatures. And unfortunately, I couldn't track down who did what for each patch, only the original author.

![Terminal Example](./img/terminal_sample.png)

The original `Meslo LG` is a customized version of Apple’s `Menlo` font, which on the other hand is based on the open-source font `Bitstream Vera` and the public domain `DejaVu`. While `Lilex` is an extended font on top of `IBM Plex Mono`.

- [Meslo LG](https://github.com/andreberg/Meslo-Font)
- Menlo
- Vera Sans Mono
- DejaVu Mono
- [Lilex](https://github.com/mishamyrt/Lilex)
- [IBM Plex Mono](https://github.com/IBM/plex).

### Author

- [@psudo-dev](https://github.com/psudo-dev/)
