## Web development intro

- [Webdesign Intro videos](http://www.dontfeartheinternet.com) (watch from bottom to top)
- tools: [MDN](https://developer.mozilla.org), [CSS-Tricks](https://css-tricks.com
), [canIuse.com](http://caniuse.com)
- [Browser dev tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools) and [VSCode editor](https://code.visualstudio.com/)
- Start with writing your HTML. Only then add CSS:
  - [Layout Land videos](https://www.youtube.com/channel/UC7TizprGknbDalbHplROtag) by Jen Simmons
  - [Things I Wish I’d Known About CSS](https://cssfordesigners.com/articles/things-i-wish-id-known-about-css)
  - How to structure your CSS:
    1. Define some design tokens (like colors and font) as [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties): [What are Design Tokens? video](https://www.youtube.com/watch?v=wtTstdiBuUk)
    2. Style the basic html elements you need, like headings, links, buttons, forms, main, header and footer: read [CSS Inheritance, The Cascade And Global Scope](https://www.smashingmagazine.com/2016/11/css-inheritance-cascade-global-scope-new-old-worst-best-friends/) for a convincing argument for this basic global CSS.
    3. Once your website grows to have reusable components that consist of multiple HTML elements, consider scoping your CSS to affect only that component: use [CSS Modules](https://css-tricks.com/css-modules-part-1-need/). Or if you can't, do the same thing manually with something like [rscss](https://ricostacruz.com/rscss/) or [BEM](http://getbem.com/naming/).
- [Resilient Web Design](https://resilientwebdesign.com): about the medium web.
- JavaScript
    - interactive: [programming intro at Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming)
    - book: [Eloquent JavaScript](http://eloquentjavascript.net/)
- [Building a Modern Website? SSG vs. SSR, SPA vs. MPA, Svelte vs. Solid](https://mb21.github.io/blog/2023/09/18/building-a-modern-website-ssg-vs-ssr-spa-vs-mpa-svelte-vs-solid.html)


### Static Site Generation

- [GitHub Pages](https://pages.github.com) – great to create your first static website
- for more advanced static web sites I would use either [Astro](https://astro.build/) or [Middleman](https://middlemanapp.com), and deploy to [Netlify](https://www.netlify.com).


### More articles

- A List Apart
  - [A Dao of Web Design](http://alistapart.com/article/dao), best article about the web ever.
  - [Article that invented Responsive Web Design](http://alistapart.com/article/responsive-web-design)
  - [Style Guide/Pattern Library Intro](http://alistapart.com/article/creating-style-guides)
  - [Surveying the Big Screen](http://alistapart.com/article/surveying-the-big-screen)
  - [canvas in vs content out](http://alistapart.com/article/frameworks)
  - [The Pain With No Name – Information Architecture](http://alistapart.com/article/pain-with-no-name)
- GUI/UX
  - [Bret Victor](http://worrydream.com)
  - [Why You Should Avoid Using the Hamburger Menu](http://jamesarcher.me/the-hamburger-menu/)
  - [Misused mobile UX patterns](https://medium.com/@kollinz/misused-mobile-ux-patterns-84d2b6930570)
- Accessibility
  - [Accessibility](http://a11yproject.com)
  - [Test accessibility with Voice Over](https://bbc-news.github.io/accessibility-news-and-you/accessibility-and-testing-with-voiceover-os.html)
- [How to Code HTML Email Newsletters](https://www.sitepoint.com/how-to-code-html-email-newsletters/)
- [iA blog](https://ia.net/know-how), e.g. [Multichannel Text Processing](https://ia.net/know-how/multichannel-text-processing)
- Websites:
    - [motherfuckingwebsite.com](http://motherfuckingwebsite.com/)
    - [bettermotherfuckingwebsite.com](http://bettermotherfuckingwebsite.com)
    - [Brutalist Websites](http://brutalistwebsites.com)
- TypeScript
  - [Error handling](https://blog.logrocket.com/pattern-matching-and-type-safety-in-typescript-1da1231a2e34/)
  - [Take control of unexpected data at runtime with TypeScript](https://blog.logrocket.com/using-typescript-to-stop-unexpected-data-from-breaking-your-app/)


### Specific Techniques

- New native CSS features:
    - [CSS nesting](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_nesting) instead of SASS (in modern browsers incl. Safari >= 17.2).
    - [@scope rule](https://developer.mozilla.org/en-US/docs/Web/CSS/@scope) instead of CSS Modules (in Chrome, Safari >= 17.4, [to be implemented in Firefox](https://bugzilla.mozilla.org/show_bug.cgi?id=%40scope)).
    - [Container queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_containment/Container_queries): like media query but asks a container element's size (in modern browsers incl. Safari >= 16).
    - [:has() pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:has) is a parent element selector (in modern browsers incl. Safari >= 15.4).
    - [relative colors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_colors/Relative_colors) (in modern browsers incl. Safari >= 17.6)
- Grid (for two-dimensional layouts)
    - [Grid Intro](https://alistapart.com/article/the-new-css-layout-excerpt)
- Flexbox (for one-dimensional stuff)
    - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    - [simple Flexbox algorithm explanation](http://madebymike.com.au/writing/understanding-flexbox/)
    - [Playground](http://codepen.io/justd/pen/yydezN)
- [Responsive Images](http://alistapart.com/article/using-responsive-images-now)
- [Google Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/)
- [Google Search Console](https://www.google.com/webmasters/tools/)
- [Test Android, etc.](https://developers.google.com/web/tools/chrome-devtools/device-mode/testing-other-browsers)
    - [Ghost Lab, Remote Preview etc.](https://www.html5rocks.com/en/tutorials/tooling/synchronized-cross-device-testing/)
- <https://www.browserstack.com>
- [WebDevChecklist](http://webdevchecklist.com/)

#### Animation / Graphics

- [D3.js](https://d3js.org) and [his blog](https://bost.ocks.org/mike/)
- SVGs
    - [scaling SVGs](https://css-tricks.com/scale-svg/)
    - [wait for SVG loaded](http://stackoverflow.com/questions/11434916/javascript-accessing-inner-dom-of-svg)
