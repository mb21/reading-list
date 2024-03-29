## Web development intro

- [Webdesign Intro videos](http://www.dontfeartheinternet.com) (watch from bottom to top)
- tools: [MDN](https://developer.mozilla.org), [CSS-Tricks](https://css-tricks.com
), [canIuse.com](http://caniuse.com)
- [browser dev tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools) and [VSCode editor](https://code.visualstudio.com/) 
- CSS
  - [Layout Land videos](https://www.youtube.com/channel/UC7TizprGknbDalbHplROtag) by Jen Simmons
  - CSS scope naming: use [CSS Modules](https://css-tricks.com/css-modules-part-1-need/). Or if you can't, do the same thing manually with something like [rscss](http://rscss.io) or [BEM](http://getbem.com/naming/).
  - CSS token naming: [What are Design Tokens? video](https://www.youtube.com/watch?v=wtTstdiBuUk)
  - [Things I Wish I’d Known About CSS](https://cssfordesigners.com/articles/things-i-wish-id-known-about-css)
- [Resilient Web Design](https://resilientwebdesign.com): about the medium web.
- JavaScript
    - interactive: [programming intro at Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming)
    - book: [Eloquent JavaScript](http://eloquentjavascript.net/)
- [Building a Modern Website? SSG vs. SSR, SPA vs. MPA, Svelte vs. Solid](https://mb21.github.io/blog/2023/09/18/building-a-modern-website-ssg-vs-ssr-spa-vs-mpa-svelte-vs-solid.html)

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


### Static Site Generation

- [GitHub Pages](https://pages.github.com) – great to create your first static website
- for more advanced static web sites I would use [Netlify](https://www.netlify.com) and either [Astro](https://astro.build/) or [Middleman](https://middlemanapp.com)

### Specific Techniques

- [Responsive Images](http://alistapart.com/article/using-responsive-images-now)
- [CSS-in-JS](https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660)
- Grid (for two-dimensional layouts)
    - [Grid Intro](https://alistapart.com/article/the-new-css-layout-excerpt)
    - [Should I try to use the IE implementation of CSS Grid Layout?](https://rachelandrew.co.uk/archives/2016/11/26/should-i-try-to-use-the-ie-implementation-of-css-grid-layout/)
    - [Grid bugs](https://github.com/rachelandrew/gridbugs)
- Flexbox (for one-dimensional stuff)
    - [IE 11 bugs](https://github.com/philipwalton/flexbugs)
    - [A Visual Guide to CSS3 Flexbox Properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
    - [simple Flexbox algorithm explanation](http://madebymike.com.au/writing/understanding-flexbox/)
    - [Playground](http://codepen.io/justd/pen/yydezN)
- [Google Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/)
- [Google Search Console](https://www.google.com/webmasters/tools/)
- [Test Android, etc.](https://developers.google.com/web/tools/chrome-devtools/device-mode/testing-other-browsers)
    - [Ghost Lab, Remote Preview etc.](https://www.html5rocks.com/en/tutorials/tooling/synchronized-cross-device-testing/)
    - [Chrome USB devices](chrome://inspect/#devices)
    - `~/Library/Android/sdk/tools/android avd`, `~/Library/Android/sdk/tools/emulator -netdelay none -netspeed full -avd Nexus_5X_API_24_x86`
- [Android Emulators for macOS (they all suck)](http://techapple.net/2014/05/3-best-android-emulators-for-mac-os-macbook-run-and-install-android-app-on-your-mac-os-x-macbook-airpro/)
- <https://www.browserstack.com>
- [WebDevChecklist](http://webdevchecklist.com/)

#### Animation / Graphics

- [Sketch](https://www.sketchapp.com)
- [D3.js](https://d3js.org) and [his blog](https://bost.ocks.org/mike/)
- SVGs
    - [scaling SVGs](https://css-tricks.com/scale-svg/)
    - [wait for SVG loaded](http://stackoverflow.com/questions/11434916/javascript-accessing-inner-dom-of-svg)
