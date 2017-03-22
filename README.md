# Groundwork

Modular CSS starter kit using Metalsmith static site generator.

    $ npm run dev

Now with [nodemon](https://www.npmjs.com/package/nodemon) to watch for file changes and [browser-sync](https://www.npmjs.com/package/browser-sync) to automatically preview changes in browser.

## Organisation of CSS

1. **Variables**: global variables and site-wide settings eg `responsive.css`
* **Base**: unclassed HTML elements eg `a {}`
* **Objects**: cosmetic-free objects, abstractions, and design patterns eg `media.css`
* **Components**: discrete, complete chunks of UI eg `carousel.css`
* **Utilities**: high-specificity, very explicit selectors that **trump** everything else. Overrides and helper classes eg `.u-hiddenvisually {}`

Organisation derived from [Inuit CSS](https://github.com/inuitcss) by [@CSSWizardry](https://twitter.com/csswizardry) ([guide](https://github.com/SonniesEdge/inuitcss-guide) by [@SonniesEdge](https://twitter.com/sonniesedge)), [SUIT CSS](https://github.com/suitcss/suit) by [@necolas]() and [SMACSS](https://smacss.com/) by [@snookca](https://twitter.com/snookca).

/**
 * Trumping display utilities derived from SUIT CSS display utilities:
 * https://github.com/suitcss/utils-display
 */

 /**
 * Trumping layout utilities derived from SUIT CSS layout utilities:
 * https://github.com/suitcss/utils
 */

/**
 * Trumping text utilities derived from SUIT CSS text utilities:
 * https://github.com/suitcss/utils-text
 */
