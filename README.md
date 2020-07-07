![image](https://user-images.githubusercontent.com/6764957/83363763-7d5c1a80-a3ce-11ea-95fb-2df3dd5aad34.png)

> **Easy ways to add design flair, user delight, and whimsy to your product!**

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Web Design in 4 minutes](#web-design-in-4-minutes)
- [UI frameworks](#ui-frameworks)
- [Spacing](#spacing)
- [Layout](#layout)
- [Typography](#typography)
- [Color Picking](#color-picking)
- [Icons and Favicons](#icons-and-favicons)
- [Graphics and SVG Illustrations](#graphics-and-svg-illustrations)
- [Pure CSS](#pure-css)
- [Design Software](#design-software)
- [Canvas](#canvas)
- [Page Transitions](#page-transitions)
- [WebGL](#webgl)
- [ThreeJS](#threejs)
- [React](#react)
- [Fun React UI frameworks](#fun-react-ui-frameworks)
- [Video](#video)
- [Onboarding](#onboarding)
- [Misc Genres (Handwriting, Pixel, ASCII styles)](#misc-genres-handwriting-pixel-ascii-styles)
- [Other Lists like this one](#other-lists-like-this-one)
- [Helpful podcasts and talks](#helpful-podcasts-and-talks)
- [More Free Stuff](#more-free-stuff)
- [Narratives](#narratives)
- [Interaction/Design Inspo](#interactiondesign-inspo)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Web Design in 4 minutes

Keep it simple: https://jgthms.com/web-design-in-4-minutes/

## UI frameworks

- Heavy: (has js, bigger learning curve) 
  - Bootstrap, [Foundation](https://get.foundation/sites/docs/), [Blaze UI](https://www.blazeui.com/), [PatternFly](https://www.patternfly.org/v4/documentation/core/components/aboutmodalbox), [UIKit](https://getuikit.com/docs/introduction)
  - Utility CSS: [Bonsai CSS](https://www.bonsaicss.com/)
  - Web Components: [Weightless](https://weightless.dev/elements/checkbox)
- Drop-in:
  - [Spectre.css](https://picturepan2.github.io/spectre/getting-started/installation.html)
  - https://purecss.io/
  - https://ajusa.github.io/lit/
  - https://screencss.com/
  - https://andybrewer.github.io/mvp/
  - https://github.com/xz/new.css
  - https://github.com/oxalorg/sakura
  - https://native-elements.dev/
  - Collections of even more:
    - https://github.com/dohliam/dropin-minimal-css
    - https://github.com/dbohdan/classless-css
    - https://github.com/ubershmekel/cssbed
- Fun
  - https://www.getpapercss.com/ (handrwritingey css similar to roughjs)
  - https://terminalcss.xyz/
  - [NES.css](https://github.com/nostalgic-css/NES.css): NES.css is a NES-style(8bit-like) CSS Framework.
  - [PSone.css](https://github.com/micah5/PSone.css): PS1 style CSS Framework, inspired by NES.css.
  - [LaTeX.css](https://latex.now.sh/)
  - [98.css](https://github.com/jdan/98.css): A Windows 98 inspired framework for building faithful recreations of old UIs.
  - [XP.css](https://github.com/botoxparty/XP.css): A Windows XP inspired framework for building faithful recreations of operating system GUIs. An extension of 98.css.
  - [BOOTSTRA.386](https://github.com/kristopolous/BOOTSTRA.386): A vintage 1980s DOS inspired Twitter Bootstrap theme
  - [New Dawn](https://github.com/npjg/new-dawn): A mac classic After Dark inspired stylesheet.
- Resets
  - https://github.com/tiaanduplessis/nanoreset
  - https://nicolas-cusan.github.io/destyle.css/
  - https://hankchizljaw.com/wrote/a-modern-css-reset/
  - http://necolas.github.io/normalize.css/

## Spacing

More. Spacing. Please.

[Double your whitespace](https://learnui.design/blog/7-rules-for-creating-gorgeous-ui-part-1.html#rule-3-double-your-whitespace)

## Layout

- https://gedd.ski/post/article-grid-layout/
- https://every-layout.dev/
- https://csslayout.io/ ([github](https://github.com/phuoc-ng/csslayout))

## Typography

<details>
  <summary>For speed, use System Font Stacks (incl. Segoe and Roboto)</summary>
  
  ([what are these?](https://css-tricks.com/snippets/css/system-font-stack/))
  - GitHub: `font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Noto Color Emoji",  "Segoe UI Emoji", "Segoe UI Symbol";`
  - [VS Code Autocomplete](https://twitter.com/kudapara/status/1093553125661773825?s=20): `font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif`
  - [`font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif;`](https://twitter.com/_etiennemartin/status/1221114860479696896?s=20)
  - [`font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
  "Roboto", "Oxygen", "Ubuntu", "Helvetica Neue", Arial, sans-serif;`](https://twitter.com/laurosilvacom/status/1221138641923141632)
  - [`font-family: ‘system-ui’, sans-serif;`](https://twitter.com/esojrafael/status/1221107296127729664?s=20)
    - the ['system-ui' generic font family is new, standardizing name across Safari, Firefox and Blink](https://www.chromestatus.com/feature/5640395337760768)
  - [Sanitize.css](https://github.com/csstools/sanitize.css#typography-uses-the-default-system-font): 
  
```css
  html {
    font-family:
      system-ui,
      /* macOS 10.11-10.12 */ -apple-system,
      /* Windows 6+ */ Segoe UI,
      /* Android 4+ */ Roboto,
      /* Ubuntu 10.10+ */ Ubuntu,
      /* Gnome 3+ */ Cantarell,
      /* KDE Plasma 5+ */ Noto Sans,
      /* fallback */ sans-serif,
      /* macOS emoji */ "Apple Color Emoji",
      /* Windows emoji */ "Segoe UI Emoji",
      /* Windows emoji */ "Segoe UI Symbol",
      /* Linux emoji */ "Noto Color Emoji";
  }
  code, kbd, pre, samp {
    font-family:
      /* macOS 10.10+ */ Menlo,
      /* Windows 6+ */ Consolas,
      /* Android 4+ */ Roboto Mono,
      /* Ubuntu 10.10+ */ Ubuntu Monospace,
      /* KDE Plasma 5+ */ Noto Mono,
      /* KDE Plasma 4+ */ Oxygen Mono,
      /* Linux/OpenOffice fallback */ Liberation Mono,
      /* fallback */ monospace;
  }
```

  - [Some systems come with good premium fonts](https://twitter.com/MatiasEduardoPR/status/1093508700378144768?s=20) - Apple OSes have `“avenir next”, “avenir”, “proxima-nova”`
  
</details>

- Consider your site personality
  - Elegant/Classic: serif like [`Freight Text`](https://fonts.adobe.com/fonts/freight-text), [`Adobe Garamond`](https://fonts.adobe.com/fonts/adobe-garamond), [`PT Serif`](https://fonts.google.com/specimen/PT+Serif)
  - Playful: rounded sans serif like [`Proxima Soft`](https://fonts.adobe.com/fonts/proxima-soft)
  - Plain/Safe: neutral sans serif like [`Freight Sans`](https://fonts.adobe.com/fonts/freight-sans), [`Inter`](https://rsms.me/inter/), [`Proxima Nova`](https://fonts.adobe.com/fonts/proxima-nova)
  - Sciency/technical: squared off (geometric) sans like [`DIN`](https://fonts.adobe.com/fonts/din-2014), [`Industry`](https://fonts.adobe.com/fonts/industry)
- Free fonts that are great with examples (thanks [@edadams](https://github.com/sw-yx/spark-joy/issues/22))
  - Google Fonts - ([see Harry Roberts on Google Font loading perf](https://csswizardry.com/2020/05/the-fastest-google-fonts/))
    - [Noto Sans](https://www.google.com/get/noto/)
    - [Fira Sans](https://fonts.google.com/specimen/Fira+Sans) - related to [Fira Code](https://github.com/tonsky/FiraCode) for devvy stuff
    - [Raleway](https://fonts.google.com/specimen/Raleway)
    - [Open Sans](https://fonts.google.com/specimen/Open+Sans)
    - Cavivanar https://twitter.com/atav1k/status/1178096244490723328?s=19
  - Chivo https://www.latinxswhodesign.com/
  - [Lato](http://www.latofonts.com/) Well known, very readable, pretty, client favorite
  - [Libre Franklin](https://beautifulwebtype.com/libre-franklin/) Elegant and thin
  - [IBM Plex Sans](https://www.ibm.com/plex/) Loads of weights, beautifully done
  - [Clear Sans](https://01.org/clear-sans)
  - [Inter](https://rsms.me/inter/) [Rasmus'](https://rsms.me/) typeface carefully crafted & designed for computer screens.
  - [Jetbrains Mono](https://www.jetbrains.com/lp/mono/) - Monospace font for devvy stuff
  - Handwritten Fonts - great for presentations, annotated illustrations
    - https://www.urbanfonts.com/fonts/handwritten-fonts.htm
    - Caveat and Reenie Beanie on google fonts  https://twitter.com/round/status/1178090890004455424?s=19
- Font Pairing
  - Canva has a great tool: https://www.canva.com/font-combinations/
- [Font variants and oldstyle numbers](https://www.jonathan-harrell.com/blog/better-typography-with-font-variants/)
- steve schoger blessed typekit fonts **for UI's**
  - proxima nova
  - aktiv grotesk
  - acumin pro
  - Museo Sans ([example](https://youtu.be/ZJj7uNdzPpM?t=566)) and similar from [TypeKit](https://fonts.adobe.com/fonts?browse_mode=default&filters=cl:ss,rc:p,ns:uc)
- https://practicaltypography.com/system-fonts.html
- https://practicaltypography.com/free-fonts.html
- eye catching fun fonts
  - https://www.haleyfiege.fun/fonts
- more opinions places
  - https://muffingroup.com/blog/best-free-fonts/
  - https://qodeinteractive.com/magazine/google-font-combinations/
  - https://type-scale.com/
  - [6 ways to justify font choices in your designs](https://learnui.design/blog/justifying-font-choices.html)
<details>
  <summary> Premium fonts and some examples </summary>
  
  - Proxima Nova https://a16z.com/ (on Typekit)
  - Graphik https://type.today/en/Graphik
  - https://www.typewolf.com/
  - [Dank Mono](https://dank.sh/)
  - Tekton https://twitter.com/round/status/1178090204562968576?s=19
  
you can learn more about proofing premium fonts here https://www.typography.com/blog/text-for-proofing-fonts

</details>

Font-size things you might try:

- [`font-size: calc(1rem + 2px + ((100vw - 550px) / 250))`](https://twitter.com/Kikobeats/status/1093620157912616966?s=20) - you can [fit text to screen width] (https://twitter.com/shshaw/status/1240647643388395521?s=20) 
- [FlowType.js](https://simplefocus.com/flowtype/)
- [FitText](https://css-tricks.com/viewport-sized-typography/)
- [Inter/Tailwind font-size combo](https://twitter.com/samselikoff/status/1204412222593568769?s=20)
- [BAD, SLOW fontsize calc](https://twitter.com/drewml/status/1115339490179072000?s=20)
- [Complete font-size notes](https://manishearth.github.io/blog/2017/08/10/font-size-an-unexpectedly-complex-css-property/)
- Don't rely on varying fontsize to control hierarchy - also use font weight (normal = 400/500, heavy = 600/700) and color
  - Don't go under font weight 400, use a lighter color or smaller fontsize instead

Note: `vw` has known a11y issues: Preserve Zooming. [Sara Soueidan](https://twitter.com/SaraSoueidan/status/1121645149983891457?s=20) recommends wrapping with `calc`, e.g. `font-size: calc(16px + .3vw);`

You may wish to use `max-width: 60ch` on content. [Note on the `ch` unit not being EXACTLY 60 chars](https://meyerweb.com/eric/thoughts/2018/06/28/what-is-the-css-ch-unit/)

## Color Picking

Pick a primary color to match your personality:

- Blue: safe, familiar
- Gold: expensive, sophisticated ([Examples](https://twitter.com/erikdkennedy/status/948914185596960768))
- Pink: fun, not so serious

You can also have a grey for secondary content, and lighter grey for tertiary content.

Don't use system default/named colors, too brutal. Soften it a bit. 

<details>
<summary>
Example blueish palette
</summary>


- Black: #1d1d1d.
- purple: #b066ff;
- blue: #203447;
- lightblue: #1f4662;
- blue2: #1C2F40;
- yellow: #ffc600;
- pink: #EB4471;
- white: #d7d7d7;

</details>


<details>
<summary>  
Use generic names if you want it swappable for dark mode. Example [yellowish palette](https://codepen.io/oliviale/full/XyqQYL):
</summary>


- primary-light: #FFD151 mustard
- primary-dark: #FFAE03 UCLA gold
- secondary-success: #20A39E light sea green
- secondary-warning: #EF5B5B sunset orange
- secondary-info: #08D377 dark cerulean
- grays: #E8E9E9, #D1D3D4, #BABDBF, #808488, #666A6D, #4D5052, #333537, #1C1D1E

</details>

One liner dark mode (careful about perf!): `filter: invert(100%) hue-rotate(180deg);`



But here are tools to help generate palettes:

- https://color.adobe.com/create
- https://coolors.co/
- https://duo.alexpate.uk/
- https://colorhunt.co/
- https://dribbble.com/colors/4030e8
- https://palettte.app/ (advanced tool; try importing the default palettes)
- http://colours.neilorangepeel.com/category/red/
- https://www.colorbox.io (by Lyft Design https://design.lyft.com/)
- Consider [darker/lighter color variations](https://learnui.design/blog/color-in-ui-design-a-practical-framework.html)
- https://croncolor.com/color-tool
- https://leonardocolor.io/?colorKeys=%236fa7ff&base=ffffff&ratios=3%2C4.5&mode=CAM02
- https://happyhues.co/
- gradients https://mybrandnewlogo.com/color-gradient-generator
- https://www.colourlovers.com/ *recommended by Tracy Osborn*
- https://flatuicolors.com/
- https://colorsupplyyy.com/
- [chroma.js color palette helper](https://gka.github.io/palettes/#/9|s|00429d,96ffea,ffffe0|ffffe0,ff005e,93003a|1|1)
- https://palx.jxnblk.com/
- https://hotpot.ai/assistant/color_assistant Get suggestions for palettes, gradients, and text colors. Hit the space bar for ML-powered ideas.
- https://yeun.github.io/open-color/
- http://khroma.co/ neural network generated color palettes
- https://learnui.design/tools/data-color-picker.html Color picker for data visualizations
- https://learnui.design/tools/accessible-color-generator.html Accessible color generator

### Color knowledge

<details>
  <summary> Not tools but still important so here they are </summary>
  
- [Sarah Drasner on Color](https://css-tricks.com/nerds-guide-color-web/)
- [Louisa Barret on Color](https://www.youtube.com/watch?v=NdKAUXAvt8E)
- [Erik Kennedy on HSB](https://learnui.design/blog/the-hsb-color-system-practicioners-primer.html)
- [Erik Kennedy on color variations](https://learnui.design/blog/color-in-ui-design-a-practical-framework.html)
- [JustinMezzell on Color](https://medium.com/@JustinMezzell/how-i-work-with-color-8439c98ae5ed) - advanced stuff on picking color tone/temperature
- [Justin Baker on Color Theory](https://medium.muz.li/the-ultimate-ux-guide-to-color-design-4d0a18a706ed)
- [How to do Dark Mode right](https://darkmodedesign.xyz/)
- [Inventorying and naming a Color Palette at UXPin](https://medium.com/@marcintreder/design-system-sprint-2-one-color-palette-to-rule-them-all-d0114ed1f659)
</details>

## Icons and Favicons

### Favicons

Don't forget them!

  - **[Real Favicon generator](https://realfavicongenerator.net/)** - pop in an image, get back a favicon! The most comprehensive one for all platforms (Windows, iOS, Android)
  - [Favicon.io](https://favicon.io/) - Generate a favicon from text, from an image, or from an emoji. Download in .ico and .png formats
  - [FontIcon](https://gauger.io/fonticon/) - Generate favicons and images from Font Awesome icons
  - [Favicon Generator](http://tools.dynamicdrive.com/favicon/) - another one
  - https://textmoji.app/ small text icons meant for Slack but also can use for faviconning
  - SVG favicons are modifiable by scroll percentage
    - you can https://css-tricks.com/svg-favicons-and-all-the-fun-things-we-can-do-with-them/
    - put the scroll percentage! https://css-tricks.com/how-i-put-the-scroll-percentage-in-the-browser-title-bar/

### Icons

- https://logosear.ch/ superfast metasearch of 200k svg logos from GitHub
- https://thenounproject.com/ Every icon you can think of, in PNG or SVG formats. They offer over 20 million icons, with built-in customization colors like size and color. Requires login, needs creative commons attribution or $3 download
- https://hotpot.ai/free_icons 5,000+ free icons. Customize colors, size, and other properties. PNG, JPG, iOS, Android, PDF. No svg.
- **https://iconmonstr.com/** Discover 4486+ free icons in 310 collections. SVG, EPS, PSD, PNG. [OK without attribution, don't sell it](https://iconmonstr.com/license/).
- https://icomoon.io/ - 450 icons, SVG, PDF, EPS, Ai, PSD. Paid tier goes up to 1600 icons.
- https://orioniconlibrary.com/ has customizable colors and packs eg for ecommerce
- https://material.io/resources/icons/?style=baseline
- http://www.entypo.com/
- https://www.heroicons.com/
- https://feathericons.com/
- https://www.zondicons.com/
- animated icons http://www.transformicons.com/builder.html
- https://game-icons.net/
- https://www.fontisto.com/icons 
- https://boxicons.com/ - 1462 icons available in PNG and SVG formats, but you can also copy the icon’s code and paste it to your HTML.
- brand icons
  - http://simpleicons.org/ icons for every brand like graphql, adobe xd, youtube, etc
  - https://css.gg/ 700+ Customizable & Retina-Ready app icons — entirely built in CSS 
  - https://worldvectorlogo.com/
  

**premium/paid icons**

- http://shape.so/ 4300+ Icons & Illustrations (by Meng To)
- https://logobly.com/ create custom logos
- https://hatchful.shopify.com/ more custom logos
- https://symbolicons.com/
- https://streamlineicons.com/ (used in [Glide Apps](https://twitter.com/glideapps/status/1199396690182230016))
- https://www.flaticon.com/
- https://gumroad.com/l/primaries

## Graphics and SVG Illustrations

Hipster Logo Generator? any others?

- https://hipsterlogogenerator.com/

Diagramming - when describing something prefer pictures over words. Make pictures.

- https://excalidraw.com/ (free, open source)
- miro.om - freemium, used by Maggie
- https://www.draw.io/ (free) - has [VS Code extension](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
- https://inkscape.org/ (free)
- https://whimsical.com/ ($10/mo)
- more tools - lucidcharts, miro, plectica - [see hn thread](https://news.ycombinator.com/item?id=21513337)

Backend entity/ ERD /SQL diagramming 

- SQL https://drawsql.app/
- Cloud AWS/Azure/GCP diagrams https://www.cloudskew.com/

Mocking your browser/phone

- Browser: https://shooot.bourhaouta.com/, https://screenshot.rocks/
- Books: https://diybookcovers.com/3Dmockups/
- Macbook: https://magicmockups.com/mockup/
- phone/watch: https://www.rotato.xyz/

### Illustrations

- :star: https://undraw.co/ An open-source illustrations website, where you can change the colors of the illustrations online before downloading.
- :star: https://www.humaaans.com/ diverse, customizable human svgs
  - https://fresh-folk.com/ is similar
- :star: https://www.blackillustrations.com/ "Beautiful, FREE illustrations of black people for your next digital project"
- :star: https://www.vecteezy.com/ High quality vector graphics with worry-free licensing for personal and commercial use.
- https://icons8.com/illustrations (previously ouch.pics)
- https://blush.design/ good random generator
- :star: https://www.freepik.com/ Graphic resources for everyone: Find Free Vectors, Stock Photos, PSD and Icons
- https://freellustrations.com/
- https://gallery.manypixels.co/ ManyPixels offer free svg illustrations with the possibility to customize the color as well.
- https://generator.opendoodles.com/ illustrations with color generator for svgs
- https://opengameart.org/
- https://illlustrations.co/ 100 beautiful illustrations, designed by Vijay Verma during a 100 days of illustrations challenge.
- https://isometric.online/ This website offers a searchable list of nice and free isometric illustrations.
- https://www.glazestock.com/ 
- https://lukaszadam.com/illustrations
- https://woobro.design/
- https://pimpmydrawing.com/
- https://www.drawkit.io/ Hand-drawn vector illustration resources for your next project
- https://www.isometriclove.com/ Cute Isometric Objects For Your Design
- https://www.karthiksrinivas.in/charco  A set of 16 handcrafted illustrations for your web & app projects. This set includes categories like 404 error, no internet connection, no service, fatal error, page not found, something went wrong, under construction and many more.
- https://www.veila.me/freebies/scandinavian-houses-free-vector-images
- https://absurd.design/
- https://github.com/MariaLetta/mega-doodles-pack
- https://iradesign.io/
- https://autodraw.com Google AI assisted drawing
- https://hotpot.ai Free or paid. Create icons, app screenshots, MacBook/browser mockups, social media posts, and other graphics for mobile apps and browser extensions.
- https://www.opendoodles.com/
- https://mixkit.co/free-stock-art/

### DIY Graphic Design

- https://snappa.com/
- https://www.canva.com/

### Stock Photos and Videos

- https://artvee.com/?s=nasa&post_type=product&product_cat=0 public domain art
- https://covers.alphacoders.com/by_category/4/2/twitter-header
- https://www.nappy.co/ "Beautiful, high-res photos of black and brown people. For free."
- https://photos.icons8.com/creator/ Create custom stock photos
- https://pexels.com
- https://generated.photos/ AI-generated stock photos
- https://unsplash.com/ of course
- https://duotone.shapefactory.co/?f=f56468&t=27184f&q=_&i=oMpAz-DN-9I (unsplash with duotone filter)
- https://github.com/neutraltone/awesome-stock-resources
- https://allthefreestock.com/
- https://pixabay.com/
- https://picjumbo.com/


### Avatars

- instead of showing people's faces, try stippling https://github.com/pshihn/stippled-image
- https://www.avatars.io/
- https://en.gravatar.com/
- https://unavatar.now.sh/ grab social images from username/email
- http://avatars.adorable.io/#demo
- https://personas.draftbit.com/ A playful avatar generator for the modern age.
- https://getavataaars.com/
- https://joeschmoe.io/ An illustrated avatar collection for
developers and designers
- https://amritpaldesign.com/toy-faces Toy Faces is a fun diverse library of 3D avatars for your design mockups and personal use.

## Pure CSS

MAKE SURE TO CHECK OUT https://components.ai

### Pure CSS Tricks

- https://twitter.com/JoshWComeau/status/1170358024319492097?s=20
- Sarah Drasner picks https://codepen.io/collection/nMgKxJ?cursor=ZD0xJm89MCZwPTEmdj0yNjc5NTQ1
- CSS3 3D Buttons http://simurai.com/archive/buttons/#
- Lea Verou CSS Secrets https://twitter.com/swyx/status/982786353216843776?s=20
  - CSS3 Patterns https://leaverou.github.io/css3patterns/
- Shadows
  - Box shadows https://brumm.af/shadows
    - drop shadows - eg -1px left -1px top - makes buttons look stamped
    - text shadows
    - experiment with multiple shadows on one element
  - Card border Generator https://card.surge.sh/
  - Components.ai box shadows https://components.ai/box-shadows
  - Neuomorphism Generator https://neumorphism.io/#f3d2c3

```css
border-radius: 50px;
background: #f3d2c3;
box-shadow:  20px 20px 22px #cfb3a6, 
             -20px -20px 22px #fff2e0;
```

- Blend Modes
  - [`background-blend-mode` color-burn, lighten, multiply are cool](https://codemenatalie.com/blog/background-blend-mode-property/)
- CSS clip path
  - https://labs.jensimmons.com/#shapes 
  - https://bennettfeely.com/clippy/ 
  - https://youtu.be/u9bDe3Bw0sA
  - CSS tricks clip path animation tutorial https://css-tricks.com/animating-with-clip-path/
  - slanted image gallery with clip path https://24ways.org/2019/flexible-captioned-slanted-images/


### SVG/Canvas Masking

- Transparent fill SVG and color in on Hover - [Codepen](https://codepen.io/m4r1vs/pen/qVReQz)
- https://speckyboy.com/css-svg-canvas-masks/
- https://www.blobmaker.app/
- https://www.shapedivider.app/
- https://getwaves.io/
- https://wweb.dev/resources/css-separator-generator
- https://inkscape.org/
- text effects https://css-tricks.com/animate-blob-text-with-svg-text-clipping/
- animate an existing svg https://svgartista.net/
- `mix-blend-mode: screen` is [really good for SVG icons, with hover](https://ishadeed.com/article/blending-modes-css/)
- SVG animations
  - https://www.svgator.com/
  - scroll based svg text path animation https://www.youtube.com/watch?v=Tae96ze3xwY
  - stroke path animation https://css-tricks.com/a-trick-that-makes-drawing-svg-lines-way-easier/

### Background Gradients and Patterns

Not just for background backgrounds - applying gradients and background images to text is super underrated. Examples:

- [https://philcoffman.com/](https://user-images.githubusercontent.com/6764957/64589989-7985f500-d374-11e9-9d8a-2a8888df6981.png)
- [https://css-tricks.com/](https://user-images.githubusercontent.com/6764957/64590103-beaa2700-d374-11e9-8a84-95ab4826a577.png)

#### Background Gradients


```css
background-image: linear-gradient(
  120deg,
  hsl(200 50% 90%) 0%,
  hsl(200 100% 90%) 100%
);
```

- https://mycolor.space/gradient Generate a CSS Color Gradient
- https://webgradients.com/ free collection of 180 linear gradients 
- https://uigradients.com/#Petrichor
- https://www.grabient.com/
- ANIMATED GRADIENTS https://www.gradient-animator.com/
- Subtle gradients by bumping only saturation on HSL (thanks [argyleink](https://twitter.com/argyleink/status/1197205254623780864)) - You can [really take this to the extreme](https://twitter.com/argyleink/status/1216815958917992450?s=20)!


#### Background Patterns

- https://leaverou.github.io/css3patterns/
- https://github.com/bansal-io/pattern.css
- http://www.heropatterns.com/
- https://www.transparenttextures.com/
- https://www.toptal.com/designers/subtlepatterns/ (exports png though :( )
- https://pattern.flaticon.com/ (create a bg pattern of icons)
- https://coolbackgrounds.io/
- https://css-doodle.com/
- https://hero-generator.netlify.app/ hero picture CSS generator
- https://www.gradientmagic.com/
- http://thepatternlibrary.com/

#### Misc Backgroundy Stuff

- CSS Doodle https://css-doodle.com/
- CSS backgroundy patterns https://leaverou.github.io/css3patterns/
- this guy https://twitter.com/yuanchuan23
- Generative Gradients http://generative-placeholders.glitch.me/
- Dimming/coloring text on background images https://coder-coder.com/background-image-opacity/
- [True Grit Texture Supply](https://www.truegrittexturesupply.com/) PNG textures (paid)

### Spinners

- web components https://wc-spinners.cjennings.dev/
- Spinners https://tobiasahlin.com/spinkit/
- Buttons, hover, inputs, and loaders https://cssfx.netlify.com/
- Conic gradient loader in CSS - [Codepen](https://codepen.io/keithclark/pen/aEbEoo)
- React, Vue and Angular Spinners https://github.com/JoshK2/react-spinners-css
- https://andrew.wang-hoyer.com/experiments/svg-animations/
- Single Element CSS Spinners https://projects.lukehaas.me/css-loaders/

### Animations & Transitions

- Buttons, hover, inputs, and loaders https://cssfx.netlify.com/
- general http://animista.net
  - animate an existing svg https://svgartista.net/ (by the same people as animista)
- general https://daneden.github.io/animate.css/
- general https://ianlunn.github.io/Hover/
- Burgers https://march08.github.io/animated-burgers/
- Burgers http://negomi.github.io/react-burger-menu/
- Layout https://github.com/aholachek/react-flip-toolkit
- Hover and loaders: https://www.csswand.dev/
- Graphic animations: https://lottiefiles.com/
- HTML animation? https://tumult.com/hype/ (paid)


### Animating Individual Elements

- links https://cssanimation.rocks/animating-links/
- tooltips on hover https://kazzkiq.github.io/balloon.css/
- Link and Button hover effects https://www.youtube.com/watch?v=ceNMP-aQkQ4

### Styling Forms

- Accessible Styled Forms https://github.com/scottaohara/a11y_styled_form_controls
- WTF Forms: Nicer Forms eg Radio Buttons with pure CSS https://github.com/mdo/wtf-forms
- Output-inspired form: https://twitter.com/steveschoger/status/1171429842442522625
- show button when placeholder-shown:  https://codepen.io/liamj/pen/vYYLGZj
- Toggles: https://jnkkkk.github.io/MoreToggles.css/allToggles.html

### Sound

- https://www.zapsplat.com/
- https://www.myinstants.com/index/se/
- https://www.youtube.com/audiolibrary/music?nv=1
- https://freesound.org/
- https://www.audacityteam.org/
- https://joshwcomeau.com/react/announcing-use-sound-react-hook/

### Lightweight Charts/Dataviz

- https://rbitr.github.io/ChartS.css/
- Sparkline fonts in text: https://github.com/aftertheflood/sparks and https://www.scribbletone.com/typefaces/ff-chartwell


### Misc Weird fun stuff

- Perspective stairstep text effects https://codepen.io/jamc92/details/KaMLvY (in action: http://tennentbrown.co.nz)
- Duotone blend modes: https://jmperezperez.com/duotone-using-css-blend-modes/
- Decovar Font with Text shadows: https://codepen.io/mandymichael/details/dJZQaz (and other [Variable Fonts by Mandy](https://variablefonts.dev/))
- Drop shadows: `box-shadow: 10px 12px 0.5rem rgba(0,0,0,0.5);`
- Expanding Search buton and text from Ana Tudor [mentioned here](https://dev.to/chriscoyier/learn-about-css-custom-properties-through-clever-uses-of-them-2fjo)
- ClippyJS https://www.smore.com/clippy-js
- Rythm.js - make your page dance https://okazari.github.io/Rythm.js/
- XKCD chart https://timqian.com/chart.xkcd/
- Netflix slide-in menu - [Codepen](https://codepen.io/FlorinPop17/pen/KKPBgeQ)
- Peek Href on Links - [2min video](https://www.youtube.com/watch?v=zMZckWl_B4c&feature=youtu.be)
- [Gooey Effect with SVG and Filters](https://css-tricks.com/gooey-effect/)
- [CSS only hover effect with Headers](https://codepen.io/oliviale/pen/YgzNzK)
- [SVG iPhone mock and animated notification transition](https://codepen.io/sdras/pen/LYELqPX)
- RoughJS Annotation - https://roughnotation.com/
- Greensock GSAP scroll trigger demo with a ThreeJS Plane model https://codepen.io/ste-vg/pen/GRooLza
- little HTML tricks that are handy https://htmldom.dev/


## Design Software

- Image editing/Export to SVG/Object Removal/Photoshop - [Photopea](https://www.photopea.com/)
- GIMP alternative - https://glimpse-editor.org/
- Lunacy - https://icons8.com/lunacy Graphic design software with built-in assets
- Figma

## Canvas

- Trianglify http://qrohlf.com/trianglify/
- generative artistry https://generativeartistry.com/
- Canvas Cards https://canvas-cards.glitch.me/
- Open Processing https://www.openprocessing.org/

## Page Transitions

- swup https://github.com/swup/swup ([css tricks](https://css-tricks.com/page-transitions-for-everyone/))

## WebGL

- [Curtains.js](https://www.curtainsjs.com/) ([example](https://codepen.io/martinlaxenaire/post/webgl-enhanced-drag-slider-tutorial-with-curtains-js-part-3))

## ThreeJS

- LowPoly 3D models from Google https://poly.google.com/search/duck

## React

### Simple Animation

- https://react-simple-animate.now.sh/
- https://yubabajs.com
- https://github.com/brunnolou/react-morph
- https://github.com/kitze/react-genie

### Page transitions

- https://github.com/joerez/react-transitions/

### Nice React Components

- https://react-smooth-range-input.now.sh/
- Theme-ui-sketchy - https://github.com/beerose/theme-ui-sketchy roughjs components with themeui
- React Physics Dragger https://react-physics-dragger-demo.netlify.com/
- [React-Designer](http://react-designer.github.io/react-designer/): Easy to configure, lightweight, editable vector graphics in your react components.
- `<Foldable>` from [Folding the DOM](https://www.joshwcomeau.com/posts/folding-the-dom/)
- React Hamburger Icons https://hamburger-react.netlify.com/
- React Curved Arrow https://react-curved-arrow.nickjanssen.com/
- Spinners
  - https://github.com/tienpham94/react-awesome-spinners - requires styled components
  - https://github.com/davidhu2000/react-spinners
  - https://github.com/JoshK2/react-spinners-css
  - https://github.com/jameygleason/aperitif
  - https://github.com/JoshK2/react-spinners-css
  - https://www.npmjs.com/package/react-loaders-kit - 200kb tho
  - https://github.com/adexin/spinners-react
  - https://gooey-react.netlify.app/examples/rotating-loader/
- PDF viewer https://react-pdf-viewer.dev/

## Fun React UI frameworks

- Arwes - Futuristic Sci-Fi and Cyberpunk Graphical User Interface Framework for Web Apps https://arwes.dev/

### Toasting

- https://cogoport.github.io/cogo-toast
- https://fkhadra.github.io/react-toastify/

### Gamification

- https://github.com/thedevelobear/react-rewards
- React Confetti https://alampros.github.io/react-confetti/
- React DOM Confetti https://daniel-lundin.github.io/react-dom-confetti/

### Icons

- https://github.com/miukimiu/react-kawaii
- https://react-icons.netlify.com/#/icons/fa (typically fontawesome)
- https://github.com/useAnimations/react-useanimations

## Video

- https://animoto.com/ - drag and drop video maker
- https://biteable.com/ - video maker with templates
- https://powtoon.com - videos and presentations for engaging and explaining

## Onboarding

- https://www.appcues.com/ show people things they need as they need them
- React Curved Arrow https://react-curved-arrow.nickjanssen.com/

## Misc Genres (Handwriting, Pixel, ASCII styles)


### RoughJS Tools

- RoughJS Animated Annotation - https://roughnotation.com/
- https://excalidraw.com/

### Pixel Art

- http://pixelartmaker.com/
- https://nostalgic-css.github.io/NES.css/
- SNES music https://www.zophar.net/music/nintendo-snes-spc

### ASCII Art

- https://fatiherikli.github.io/archetype/
- https://textik.com/#a4ec12a68785f25f
- http://asciiflow.com/
- https://monodraw.helftone.com/
- text to diagramming tools [list](https://smusamashah.github.io/text-to-diagram)

## Other Lists like this one

- https://github.com/bradtraversy/design-resources-for-developers
- https://tiny-helpers.dev/
- https://nodesign.dev/
- https://github.com/LisaDziuba/Awesome-Design-Tools

## Helpful podcasts and talks

- [How do I learn design?](https://www.codenewbie.org/podcast/how-do-i-learn-design) (CodeNewbie)
- [Design foundations for developers](https://syntax.fm/show/196/design-foundations-for-developers) (Syntax)
- [Design tips for developers](https://syntax.fm/show/068/design-tips-for-developers) (Syntax)
- [Tactical design advice for developers](https://changelog.com/podcast/333) (The Changelog)
- [UI Design for Developers](https://designcode.io/ui-design-for-developers) (Meng To)
- [Learning How to Design](https://shoptalkshow.com/343/) (ShopTalk)
- [Simple Layout checklist](https://docs.google.com/file/d/0B0gPtgNVonXPT1NsWGpKZWZKV1U/edit)
  - [ ] Clear idea of purpose, target audience, where/how long it will be seen
  - [ ] Information hierarchy (vary size, contrast, position)
  - [ ] Clear visual structure - pick the most suitable way to group elements
  - [ ] Space - leave enough whitespace. Too much > too little
  - [ ] Alignment - use as few lines as possible
- Steve Schoger - [little details of visual ui design](https://twitter.com/swyx/status/1206234577821286406?s=20)
  - [ ] add a bit of color to your greys
  - [ ] saturate greys when using a colored background
  - [ ] consider temp when saturating greys
  - [ ] use a consistent corner radius
  - [ ] use consistent icon set
  - [ ] use font size to emphasize impt info
  - [ ] use color to create a hierarchy
  - [ ] use consistent spacing scale
  - [ ] use color to draw attention
  - [ ] offset box-shadows
  - [ ] easy on the link styles
  - [ ] use contrast to create balance
  - [ ] pick an appropriate line height
  - [ ] use alignment to clean up your design
  - [ ] give actions hierarchy
  - [ ] consider spacing instead of borders
  - [ ] use color to create depth and hierarchy
  - [ ] use good fonts
- [Buffer Design tips](https://buffer.com/library/social-media-design-tips)
  - [ ] Color: emotion, personality
  - [ ] Balance: symmetry, asymmetry
  - [ ] Lines: straight lines for harmony, curved for movement. guide the eyes
  - [ ] Typography: 3 max, san-serif for web, kerning for headlines
  - [ ] Add Contrast with shapes, color, element sizes
  - [ ] Scale: size elemnts differently to draw attention or demonstrate concept
  - [ ] Proximity: group related items together. connect colors, fonts, shapes
  - [ ] Hierarchy: most impt elements first
  - [ ] Repetition: consistency of fonts, colors, logos
  - [ ] Direction: F, E, Z pattern. Put key info in left
  - [ ] Space: use space to amplify other objects
- [Refactoring UI](https://refactoringui.com/)
  - Starting from Scratch
    - Choose a personality
    - Don't design too much
    - Detail comes later
  - Hierarchy
    - Size isn't everything
    - Emphasize by de-emphasizing
  - Layout and Spacing
    - Establish a spacing/sizing system
  - Designing Text
    - Keep your line length in check
  - Working with Color
    - Ditch hex for HSL
  - Creating Depth
    - (to be continued)
  - Emulate a light source
    - (to be continued)
  - Working with Images
    - (to be continued)
  - Finishing Touches
    - (to be continued)
- [Tracy Osborn Checklist](https://www.youtube.com/watch?v=uKpfO331DY4&list=WL&index=4)
  - Reduce Clutter
    - use ColourLovers for color palettes
    - Fonts - max 2. Use fancy fonts sparingly
    - more whitespace
    - break up walls of text with bullet points
    - big clear CTA buttons
  - Headlines: talk benefits not details. short.
- [Design Details: Principles of Design](https://designdetails.fm/episodes/220880) - Design Details' most downloaded episode of all time!
- [7 Rules for Creating Gorgeous UI](https://learnui.design/blog/7-rules-for-creating-gorgeous-ui-part-1.html)
  - Light comes from the sky
  - Black and white first
  - Double your whitespace
  - Learn the methods of overlaying text on images
  - Make text pop — and un-pop
  - Use only good fonts
  - Steal like an artist

## More Free Stuff

- [Canva Design School](https://designschool.canva.com/)
- [Degreeless.design](https://www.degreeless.design/#basics)
- Free tier software https://free-for.dev/#/
- https://github.com/Vincenius/link-list
- Public API's for demos https://github.com/public-api-lists/public-api-lists
- [The Design Newsletter](https://learnui.design/newsletter.html)


## Narratives

- https://medium.com/@awilkinson/slack-s-2-8-billion-dollar-secret-sauce-5c5ec7117908


## Interaction/Design Inspo

- Dribbble ofc
- https://pageflows.com/
- https://uimovement.com/
- https://uidesigndaily.com/
- https://www.siteinspire.com/
- https://www.landingfolio.com
- http://www.cssmania.com/
- https://www.uisources.com/
- [Codrops](https://tympanus.net/codrops/2019/06/04/inspirational-websites-roundup-5/)
- https://collectui.com/
