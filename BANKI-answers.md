# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list without answers, courtesy of https://leonnoel.com/100devs/

## Behavioral

Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering begin with "At my last opportunity..." or "At my last company". Don't sell yourself out and say "bootcamp" or "school".

### CAR

- **Cause**
  - Why did you need to take action?
- **Action**
  - Steps you took so solve problem
  - Be positive
  - Don't be humble
- **Result**
  - How are you better?

### Questions

- [x] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
  - **Cause:** At a previous company we had project managers assigned to several different teams where workload would fluctuate quite a bit.
  - **Action:** I noticed an opportunity to flatten the workload of the PM's, by creating a shared PM pool.
  - **Result:** This was possible by running a high level kanban of all projects assigned by PM to get visibility to workload. It also allowed knowledge sharing such that it was much easier for a PM to step in on any given team.
- [x] Tell me about a time you had to work on several projects at once. How did you handle this?
  - **Cause:** I was working on two large projects for two separate clients that were at different stages of their lifecycle. One project was in production and the other project was in the implementation phase.
  - **Action:** I decided to send a less experienced colleague to the installation site while I went to do a production check-in on the other project in China. Prior to leaving I briefed my colleague in on the project and told them what to look out for.
  - **Result:** While in China I had daily calls with my colleague as well as received daily photo reports to review the installation. Both projects end up being financially successful. The tight communication and teamwork is ultimately what allowed it to be so.
- [x] Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?
  - **Cause:** I had a direct report working on building a client quote within a spreadsheet template.
  - **Action:** I explained to them how to use and fill out the template and then left them to finish it.
  - **Result:** After a few hours I came to see what the final result was and found that they only partially completed it and had many mistakes. What I did then and with subsequent reports was to have them work on the quote in front of me for 30 minutes so that I could guide them and allow them to ask question. I found that technique brought people up to speed more quickly.
- [ ] Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give an example of an important project goal you reached and how you achieved it.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about yourself.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your experience at 100Devs.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you know about our company?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why do you want to work for us?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why are you interested in this opportunity?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your dream job?  What do you really want to do with your career?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me a time when you failed.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you read on a regular basis?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What's some critical feedback you've gotten recently?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Do you have any questions?
  - **Cause:**
  - **Action:**
  - **Result:**

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [x] What does a doctype do?
  - **Explanation:** Instructions to the browser about what version of HTML the webpage is written in, ensuring the web page is parsed the same way across web browsers.
  - **Use:** It's the first line of code in the HTML document.
  - **Example:** For an HTML5 document the tag would be `<!DOCTYPE html>`
  - **Source:** https://www.freecodecamp.org/news/what-is-the-doctype-declaration-in-html/
- [x] How do you serve a page with content in multiple languages?
  - **Explanation:** By setting the lang attributes on the various elements within the page.
  - **Use:** The lang attribute can be used on various elements (typically html, p, li...)
  - **Example:** You can set the whole site as being english by setting the html element `<html lang="en">` Or you could set a paragraph as spanish with `<p lang="es">`
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang
- [x] What kinds of things must you be wary of when designing or developing for multilingual sites?
  - **Explanation:** There are quite a few different nuances to pay attention to including:
    - Including the `lang` attribute
    - Allowing users to change the language
    - Minimize text in raster based images
    - Text overflow when translated
    - How colors are perceived
    - Date and currency formats
    - Language reading direction
    - Don't concatenate translated strings
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] What are `data-` attributes good for?
  - **Explanation:** They store data private to the page or application.
  - **Use:** They were often used for storing extra data in the DOM, but are generally discouraged now.
  - **Example:** The exception is to add a hook for end to end testing frameworks like Selenium.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:**
    - Semantics: Describe the content
    - Connectivity: Communicate with the server
    - Offline and storage: Store data client-side
    - Multimedia: Make audio and video first-class citizens
    - Graphics and effects: Diverse range of presentation options
    - Performance and integration: Speed optimization
    - Device access: Various input and output devices
    - Styling: More sophisticated themes
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:** Cookies can be initiated by the server, have a manually set expiration date are small file size and are sent to the server with HTTP request. Local and session are both initiated by the client, are a relatively large file and aren't sent to the server. The main difference between local and session is that local storage will persist forever until cleared manually.
  - **Use:** They are all used for client side storage of strings in key-value pairs.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] Describe the difference between `<script>, <script async> and <script defer>`.
  - **Explanation:**
    - `<script>` HTML parsing is blocked, script is fetched and executed immediately.
    - `<script async>` script fetched in parallel to HTML parsing and executed as soon as it is available.
    - `<script defer>` script fetched in parallel to HTML parsing and executed when the page has finished parsing.
  - **Use:**
    - Use `async` when the script is independent of any other scripts on the page
    - `defer` is useful when you need to make sure the HTML is fully parsed before executing.
  - **Example:**
    - `async` could be used for analytics scripts.
    - A deferred script must not contain `document.write`
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:** Putting `<link>`s in the `<head>` allows for quick "first meaningful paint". When a page first loads, HTML and CSS are being parsed simultaneously. Conversely `<script>` tags block HTML parsing while they are being downloaded and executed which can slow down your page. Placing the scripts at the bottom will allow the HTML to be parsed and displayed to the user first.
  - **Exceptions:** When your script contains `document.write`, however it isn't consider good practice to use `document.write`. Also if you need scripts to run on page load it may be beneficial to split them out from your main script and place in the head.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] What is progressive rendering?
  - **Explanation:** Techniques used to improve the performance of a webpage to render content for display as quickly as possible.
  - **Use:** Improving perceived load time
  - **Example:** Lazy loading of images, Prioritizing visible content (or above-the-fold rendering) and Async HTML fragments
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:** When you want to serve different images to users depending on their device display width.
  - **Use:** Sending lower resolution to limit data waste and increase performance or sending larger images to a higher resolution display to enhance the UX.
  - **Example:** `<img srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 2000w" src="..." alt="">`
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
- [x] Have you used different HTML templating languages before?
  - I've used nunjucks, haml and markdown. They seem relatively similar and have helpful features.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

### CSS

- [x] What is CSS selector specificity and how does it work?
  - **Explanation:** The means by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied.
  - **Use:** Specificity is a weight that is applied to a given CSS declaration, determined by the number of each selector type in the matching selector.
  - **Example:** A selector of `#id .class tag` would have 111 points as id's count for 100, classes for 10 and tags 1.
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
- [x] What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  - **Explanation:** "Normalize" alters the default styles of various browser to match each other. "Reset" will remove the browsers default styles so you are starting from scratch.
  - **Use:** Applying one or the other is done to try and make websites visually consistent across different browsers. I prefer to use a mix of both. Starting with the normalize to keep it conscise and then add some elements like anchors and headers with a reset. Going full "nuke" is often unnecessary and creates a larger, harder to debug file.
  - **Example:**

Normalize:

```css
/**
 * Correct the font size and margin on `h1` elements within `section` and
 * `article` contexts in Chrome, Firefox, and Safari.
 */

h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
```

Reset:

```css
html,
body,
h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
  padding: 0;
}
```

**Source:** https://elad.medium.com/normalize-css-or-css-reset-9d75175c5d1e

- [x] Describe floats and how they work.
  - **Explanation:** Floats are a positioning property where the element that is floated will be removed from the flow of the page and affect the elements around it. A parent element will collapse to zero height if it contains only floated elements, to fix this it was common to use a `.clearfix` hack.
  - **Use:** It was used prior to flex and grid to layout pages in a more flexible manner.
  - **Example:** You could float three elements left and give them widths of 33% to create three even width columns.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Describe z-index and how stacking context is formed.
  - **Explanation:** The `z-index` property in CSS controls the vertical stacking order of elements that overlap. A stacking context is an element that contains a set of layers. The z-index values of its children are set relative to that element rather than to the document root. Layers outside of that context can't sit between layers within it.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Describe BFC (Block Formatting Context) and how it works.
  - **Explanation:** A BFC is an HTML box that satisfies at least one of the following conditions:
    - The value of float is not none.
    - The value of position is neither static nor relative.
    - The value of display is table-cell, table-caption, inline-block, flex, or inline-flex, grid, or inline-grid.
    - The value of overflow is not visible.
  - **Use:** Knowing how to establish a block formatting context is important, because without doing so, the containing box will not contain floated children.
  - **Example:** Without forming a BFC you could have content of a float that is taller than the content alongside it. The border of the parent element could then "cut-through" the floated box.
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context
- [x] What are the various clearing techniques and which is appropriate for what context?
  - **Explanation:**
    - Empty `div` method
    - Clearfix method
    - `overflow: auto` or `overflow: hidden` method
  - **Use:** `.clearfix` utility class is probably the best method to use in general as it doesn't take long to construct and doesn't suffer from clipping issues like the overflow methods.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Explain CSS sprites, and how you would implement them on a page or site.
  - **Explanation:** CSS Sprites are a means of combining multiple images into a single image file for use on a website, to help with performance.
  - **Use:** Browsers limit the number of concurrent requests a site can make so leading several images with a single HTTP request helps increase page load speed.
  - **Example:** An example would be combining press logo's for Wired, NY Times and The Washington Post into a single image file. Then on the site, with CSS, placing the file three times and moving/cropping it to display the applicable logo.
  - **Source:** https://css-tricks.com/css-sprites/
- [x] How would you approach fixing browser-specific styling issues?
  - **Explanation:** There are a handful of ways to solve the issue such as browser specific stylesheets, using a library like bootstrap, etc. MY preference would be to use a combination normalize/reset style sheet. I'd rather use a combination as going full nuke with a reset isn't necessary and makes it a little harder to debug.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:** My preference is to try and build lightweight simple websites that incorporate progressive enhancement.
  - **Use:** Build the base level of HTML/CSS with semantics and accessibility in the forefront you get a site that works well on feature-constrained browsers. I would then add any CSS on JavaScript enhancements deliberately, checking [caniuse.com](https://caniuse.com/) and using vendor prefixs and polyfills if required.
  - **Example:** Instead of filling the site with `<div>` using more semantically appropriate tags like `<section> <aside> <article> <header> <footer>`
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:**
    - Make the element have a size of zero `width: 0; height: 0`
    - Absolute position off screen `position: absolute; left: -99999px`
    - Text indent off screen if within block element `text-indent: -9999px`
    - aria-label which will read the string given to the attribute.
  - **Use:** I typically absolutely position the element off screen as it covers the most scenarios.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:** I typically use a 12 column "grid" system when doing my initial web layout.
  - **Use:** I find that it works well for laying out the average website and giving the site some visual consistency. When if comes to coding the site I find it helps speed up the layout immensely.
  - **Source:** https://www.flux-academy.com/blog/how-to-use-a-grid-in-web-design
- [x] Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:** I use them quite frequently.
  - **Use:** I use them on every website and typically build mobile first. The breakpoints and media queries are then used to convert the layout from mobile to desktop.
  - **Example:** Some examples is changing a bunch of cards from being a single column stack on mobile to a three column layout on desktop.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Are you familiar with styling SVG?
  - **Explanation:** Yes there are a few ways to style them including inline CSS, embedded CSS or an external style sheet. Basic coloring can be done with the fill and stroke attributes.
  - **Example:**
  ```html
  <rect width="100" height="100" stroke="blue" fill="purple" />
  ```
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Can you give an example of an `@media` property other than screen?
  - **Explanation & Use:** There are four types:
    - `all` - for all media type devices
    - `print` - for printers
    - `speech` - for screenreaders that "reads" the page out loud
    - `screen` - for computer screens, tablets, smart-phones etc.
  - **Example:** An example of using print and making all the text black:
  ```css
  @media print {
    body {
      color: black;
    }
  }
  ```
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] What are two "gotchas" for writing efficient CSS?
  - **Explanation:**
    - Browsers match selectors from rightmost (key selector) to left. The shorter the length of the chain the faster the browser can find a match. Avoid using tag and universal selectors for your key selector.
    - Avoid using styles that trigger reflow.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] What are the advantages/disadvantages of using CSS preprocessors?

  - **Explanation:** Some advantages would be:

    - The code is easier to maintain
    - More efficient to write with nested selectors
    - Mixins can be used for repeated styles
    - Ability to split into different files

    Disadvantages would be:

    - Additional tooling is required
    - You aren't able to use the most current features of standard CSS

  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [x] Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:** I've found that being able to split files and nest selectors is the most useful. A couple of downsides are that debugging is a little more difficult and having to wait for compilation.
  - **Source:** https://adamsilver.io/blog/the-disadvantages-of-css-preprocessors/
- [x] How would you implement a web design comp that uses non-standard fonts?
  - **Explanation:** Use @font-face and define font-family
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Explain how a browser determines what elements match a CSS selector.
  - **Explanation:** Browsers match selectors from rightmost (key selector) to left.
  - **Example:** For example with this selector `p span`, browsers firstly find all the `<span>` elements and traverse up its parent all the way up to the root to find the `<p>` element. For a particular `<span>`, as soon as it finds a `<p>`, it knows that the `<span>` matches and can stop its matching.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Describe pseudo-elements and discuss what they are used for.
  - **Explanation & Use:** A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s)
  - **Example:** ::first-line can be used to change the font of the first line of a paragraph
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements
- [x] Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:** The CSS box model describes the rectangular boxes that are generated for elements in the document tree and laid out according to the visual formatting model. Each box has a content area and optional surrounding padding, border, and margin areas.
  - **Use:** The standard box model calculates box size by taking a specified `height` and `width`, then adding the padding and border. However to change to the alternative box model you would set `box-sizing: border-box` which allows you to set the box size with `height` and `width`.
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model
- [x] What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation & Use:** It allows you to specify the actual width and height of a box using the `width` and `height` properties. This allows you to input true sizes and not have to do any math to take padding and borders into account.
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#the_alternative_css_box_model
- [x] What is the CSS `display` property and can you give a few examples of its use?
  - **Explanation & Use:** The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.
  - **Example:** `display: block` would make the element consume the whole line width. `display: grid` would allow you to layout children in a grid system. If you wanted three columns you could pair it with something like `grid-template-columns: 1fr 1fr 1fr`
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/display
- [x] What's the difference between `inline` and `inline-block`?
  - **Explanation:**
    - `inline`
      - CANNOT specify width and height
      - Can only set margin and padding for the sides, not top and bottom.
    - `inline-block`
      - CAN specify width and height
      - Can set margin and padding on all sides
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Explanation:**
    - Relative - Position is relative to it's original static position. Original space on the page is preserved.
    - Fixed - Element removed from page flow and placed in spot relative to viewport. It won't move when scrolled.
    - Absolute - Element removed from page flow and positioned relative to it closest "positioned" ancestor. Original space on the page is not preserved
    - Static - The default position. `top`, `right`, `bottom`, `left` and `z-index` properties do not apply.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  - Bootstrap - It takes a while to get the latest CSS features added. Your sites end up looking very similar to others.
  - Tailwind - The HTML can feel very cluttered. Reusing styles is a bit clunky.
- [x] Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:** I have used both flexbox and grid and like to employ both of them.
  - **Use:** I find grid to be useful for the top level page layout and any elements which have a typical grid layout. I prefer using flexbox for sections and other elements which don't need a rigid grid alignment.
  - **Example:** If I had something like a tic-tac-toe board I would use grid as it is easy to get the boxes to align and be the same size. If I had some sort of information card with multiple pieces of information I would likely use flexbox.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:** Making a website responsive means the some elements will respond by adapting its size or other functionality according to the device's screen size. A mobile-first strategy is also responsive, however it agrees we should default and define all the styles for mobile devices, and only add specific responsive rules to other devices later.
  - **Use:** You would use media queries to make the above changes at certain screen size breakpoints.
  - **Example:** An example of mobile first and responsive would be:

```css
.my-class {
  font-size: 12px;
}

@media (min-width: 600px) {
  .my-class {
    font-size: 24px;
  }
}
```

- **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] How is responsive design different from adaptive design?
  - **Explanation:** Both responsive and adaptive design attempt to optimize the user experience across different devices.
  - **Use:** Responsive design works on the principle of flexibility - a single fluid website that can look good on any device. Instead of one flexible design, adaptive design detects the device then provides the appropriate feature and layout based on a predefined set of viewport sizes and other characteristics. I believe responsive is the best approach to provide a great experience for all users.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:** Retina is just a marketing term to refer to high resolution screens with a pixel ratio bigger than 1. In order to have crisp, good-looking graphics that make the best of retina displays we need to use high resolution images whenever possible. However using highest resolution images will have an impact on page load times.
  - **Use:** To overcome this problem, we can use responsive images, as specified in HTML5 with the `srcset` attribute.
  - **Example:**
  ```html
  <img
    src="/images/test-1600.jpg"
    srcset="
      /images/test-400.jpg   400w,
      /images/test-800.jpg   800w,
      /images/test-1200.jpg 1200w
    "
  />
  ```
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
- [x] Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Explanation:** `translate()` is a value of CSS `transform`. `transform` causes the browser to create a GPU layer for the element but changing absolute positioning properties uses the CPU. `translate()` would be the more efficient solution with shorter paint times. If you do not want the original space of the element preserved you would want to use `absolute` positioning.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

### Javascript

- [x] Explain event delegation
  - **Explanation:** Setting an event listener on a parent element an having events that happen on a child element bubble up to the parent.
  - **Use:** When you want some code to run when the user interacts with any one of a large number of child elements.
  - **Example:**

```html
<div id="container">
  <div class="tile"></div>
</div>
<script>
  container.addEventListener(
    'click',
    (event) => (event.target.style.backgroundColor = bgChange())
  );
</script>
```

**Source:** https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_delegation

- [x] Explain how `this` works in JavaScript
  - **Explanation:** `this` references an object. When inside of a constructor function or class it will reference the object on instantiation.
  - **Use:** It is used to assign properties and values to an object on instantiation.
  - **Example:**

```javascript
class MyThing {
  constructor(passThisIn) {
    this.passThisIn = passThisIn;
  }
}
```

**Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this

- [x] Explain how prototypal inheritance works
  - **Explanation:** All JavaScript objects have a `__proto__` property that is a reference to another object, which is called the object's "prototype". If a property is accessed on an object, but not found the JavaScript engine check's that object prototype. If again it's not found it checks that prototypes prototype on up the chain until it reaches the top of the chain.
  - **Use:** It can help reduce redundant code.
  - **Example:**

```javascript
function Parent() {
  this.name = 'Parent';
}
Parent.prototype.greet = function () {
  console.log('Hello from ' + this.name);
};
const child = Object.create(Parent.prototype);
child.cry = function () {
  console.log('waaaaaahhhh!');
};
child.cry();
// waaaaaahhhh!
child.greet();
// hello from Parent
child.constructor;
// ƒ Parent() {
// this.name = 'Parent';
// }
child.constructor.name;
// 'Parent'
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions
- [x] What do you think of AMD vs CommonJS?
  - **Explanation:** I would actually prefer to use ESM (ECMAScript Modules) due to it's simple syntax and async nature. Historically CommonJS was used in the back end and runs synchronous and AMD was used in the front end and runs asynchronous.
  - **Use:** CJS has been used in node.js for a while, but the current version of node now allows the use of EMS.
  - **Source:** https://dev.to/iggredible/what-the-heck-are-cjs-amd-umd-and-esm-ikm
- [x] Explain why the following doesn't work as an IIFE: `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:** The parser reads it as two seperate statements. First the function declaration `function foo(){ }` and then a blank function call attempt `();` The best way to fix this would be to add another set of parenthesis wrapping the function declaration `(function foo(){ })()` This changes it from a function declaration to a function expression.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions
- [x] What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:**
    - `null`: the value is intentionally absent (points to nothing in memory).
    - `undefined`: not yet assigned a value or not yet declared.
    - `undeclared`: improperly declared without let/const/var
  - **Use:** null can be used to assign the primitive value of null to a variable. undeclared throws an error where as null and undefined can be checked with a conditional
  - **Example:** `null` and `undefined` can be checked using strict equality `===`. Undeclared will throw it's own error so you could use `try...catch`
  - **Source:** https://www.30secondsofcode.org/articles/s/javascript-undeclared-undefined-null
- [x] What is a closure, and how/why would you use one?
  - **Explanation:** Closure allows you to use an outer function’s scope (go into a parent, grandparent function, etc.) from within an inner function. In JavaScript a closure is created every time a function is created.
  - **Use:** It allows you to combine data with the function that will operate on that data. It is similar to OOP.
  - **Example:**

```javascript
function init() {
  var name = 'Mozilla'; // name is a local variable created by init
  function displayName() {
    // displayName() is the inner function, a closure
    alert(name); // use variable declared in the parent function
  }
  displayName();
}
init();
```

- **Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
- [x] Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:** `.forEach()` executes a callback function on each element, but does not return a value. `.map()` executes a callback function on each element and "maps" the result to a new array. The new array is returned.
  - **Use:** If you need the result and don't want to mutate the original array, use map. If you only need to iterate over the array then forEach can be used.
  - **Example:**
    `.forEach()`:

```javascript
const a = [1, 2, 3];
const doubled = a.forEach((num, index) => {
  // Do something with num and/or index.
});
// doubled = undefined
```

`.map()`:

```javascript
const a = [1, 2, 3];
const doubled = a.map((num) => {
  return num * 2;
});
// doubled = [2, 4, 6]
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What's a typical use case for anonymous functions?
  - **Explanation:** I've typically encountered them as callback functions that don't need to be used anywhere else.
  - **Use:** Essentially when you don't need a named function and the function is bound to some other action.
  - **Example:**

```javascript
setTimeout(function () {
  console.log('Hello world!');
}, 1000);
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:** My preference is to use ES6 Modules to organize my code for the following reasons:
    - Easier to reuse code
    - Easier to keep code separated leading to...
    - Easier to maintain
  - **Source:** https://www.theodinproject.com/lessons/node-path-javascript-es6-modules
- [x] What's the difference between host objects and native objects?
  - **Explanation:** Native objects are part of the language as defined by ECMAScript specification. Host objects are those provided by the runtime (browser or Node).
  - **Example:** Some native objects are `String`, `Math`, `RegExp`, and `Object`. A couple of host objects are `window` and `console`
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What is the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation & Use:**
    - `function Person(){}` is likely being used as a constructor.
    - `var person = new Person()`is instantiated a new Person object as person.
    - `var person = Person()` is not correct and would likely return undefined. To create a new instance you would need to use the `new` operator as above.
  - **Example:**

```javascript
function Person(name) {
  this.name = name;
}

var person = Person('John');
console.log(person); // undefined
console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

var person = new Person('John');
console.log(person); // Person { name: "John" }
console.log(person.name); // "john"
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What's the difference between `.call()` and `.apply()`?
  - **Explanation:** They are both used to invoke functions the difference is in how they take arguments. `.call()` takes them as comma-separated values and `.apply()` takes them as an array.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] Explain `Function.prototype.bind`.
  - **Explanation:** Creates a new function that, when called, has its `this` keyword set to the provided value.
  - **Use:** For binding the value of `this` in methods of classes that you want to pass into other functions. This is frequently done in React components.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] When would you use `document.write()`?
  - **Explanation:** It is usually considered dangerous and prone to misuse. I would not use it in a modern day website.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:**
    - **Feature Detection:** Working out whether a browser supports a certain block of code, and running different code depending on whether it does, so that the browser can provide a working experience rather crashing/erroring in some browsers.
    - **Feature Inference:** Checks for a feature just like feature detection, but uses another function because it assumes it will also exist. Feature Detection is the better approach.
    - **UA String:** A browser-reported string that allows the network protocol peers to identify various properties of the system. It's tricky to parse and can be spoofed so it's best to avoid this method.
  - **Example:** Using feature detection:

```javascript
if ('geolocation' in navigator) {
  // Can use navigator.geolocation
} else {
  // Handle lack of feature
}
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] Explain Ajax in as much detail as possible.
  - **Explanation:** Ajax (asynchronous JavaScript and XML) is a set of web development techniques using many web technologies on the client side to create asynchronous web applications. With Ajax, web applications can send data to and retrieve from a server asynchronously (in the background) without interfering with the display and behavior of the existing page.
  - **Use:** By decoupling the data interchange layer from the presentation layer, Ajax allows for web pages, and by extension web applications, to change content dynamically without the need to reload the entire page. In practice, modern implementations commonly use JSON instead of XML, due to the advantages of JSON being native to JavaScript.
  - **Example:** The `fetch` API is typically used nowadays for asynchronous communication.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What are the advantages and disadvantages of using Ajax?
  - **Advantages:**
    - Better interactivity. New content from the server can be changed dynamically without the need to reload the entire page.
    - Reduce connections to the server since scripts and stylesheets only have to be requested once.
    - State can be maintained on a page. JavaScript variables and DOM state will persist because the main container page was not reloaded.
  - **Disadvantages:**
    - Dynamic webpages are harder to bookmark.
    - Does not work if JavaScript has been disabled in the browser.
    - Some webcrawlers do not execute JavaScript and would not see content that has been loaded by JavaScript.
    - JavaScript will have to be parsed and executed on the browser, and low-end mobile devices might struggle with this.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:** JSONP (JSON with Padding) is a method commonly used to bypass the cross-domain policies in web browsers because Ajax requests from the current page to a cross-origin domain is not allowed.
  - **Use:** JSONP can be unsafe as it can do everything else JavaScript can so you need to trust the provider of data. These days, CORS is the recommended approach and JSONP is seen as a hack.
  - **Example:**

```html
<!-- https://mydomain.com -->
<script>
  function printData(data) {
    console.log(`My name is ${data.name}!`);
  }
</script>

<script src="https://example.com?callback=printData"></script>
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions
- [x] Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:** The only one I've used is JSX in React, which I don't think it quite javascript templating.
  - **Use:** It's more of an extension to ECMAScript that allows you to easily structure components with familiar HTML syntax.
  - **Example:**

```javascript
const name = 'Josh Perez';
const element = <h1>Hello, {name}</h1>;
```

- **Source:** https://reactjs.org/docs/introducing-jsx.html
- [ ] Explain "hoisting".
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Describe event bubbling.
  - **Explanation & Use:** When an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestors. The most deeply nested element that caused the event is called a target element, accessible as event.target.
  - **Example:**

```html
<style>
  body * {
    margin: 10px;
    border: 1px solid blue;
  }
</style>
<form onclick="alert('form')">
  FORM
  <div onclick="alert('div')">
    DIV
    <p onclick="alert('p')">P</p>
  </div>
</form>
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What's the difference between an "attribute" and a "property"?
  - **Explanation & Use:** Attributes are defined on the HTML markup but properties are defined on the DOM. An attribute is the initial state when rendered in the DOM. A property is the current state.
  - **Example:**

```javascript
const input = document.querySelector('input');
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello
```

Notice how the property updates after adding "World" to the input.

```javascript
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello World!
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-an-attribute-and-a-property
- [ ] Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between document `load` event and document `DOMContentLoaded` event?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] What is the difference between `==` and `===`?
  - **Explanation:** == checks for value equality while === checks for value and data type equality
  - **Use:** == should generally be avoided unless for null or undefined
  - **Example:**

```javascript
1 == '1'; // true
1 == [1]; // true
1 == true; // true
0 == ''; // true
0 == '0'; // true
0 == false; // true
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [ ] Explain the same-origin policy with regards to JavaScript.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5] `
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:** "Ternary" means "composed of three parts", as the expression accepts 3 operands. First, a condition followed by a question mark (?), then an expression to execute if the condition is truthy followed by a colon (:), and finally the expression to execute if the condition is falsy.
  - **Use:** Can simplify code over if...else statements.
  - **Example:**

```javascript
const age = 26;
const beverage = age >= 21 ? 'Beer' : 'Juice';
```

- **Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator
- [ ] What is "use strict";? what are the advantages and disadvantages to using it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  - **Explanation:** Every script has access to the global scope, and if everyone uses the global namespace to define their variables, collisions will likely occur. Use the module pattern (IIFEs) to encapsulate your variables within a local namespace.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [ ] Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] What are the pros and cons of using Promises instead of callbacks?

  - **Pros:**
    - Avoid callback
    - Easy to write sequential asynchronous code that is readable with `.then()`.
    - Easy to write parallel asynchronous code with `Promise.all()`.
    - With promises, these scenarios which are present in callbacks-only coding, will not happen:
      - Call the callback too early
      - Call the callback too late (or never)
      - Call the callback too few or too many times
      - Fail to pass along any necessary environment/parameters
      - Swallow any errors/exceptions that may happen
  - **Cons:**
    - Slightly more complex code (debatable).
    - Older browsers may require a polyfill.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [ ] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What tools and techniques do you use debugging JavaScript code?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What language constructions do you use for iterating over object properties and array items?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Explain the difference between mutable and immutable objects.
  - **Explanation:** A mutable object is an object whose state can be modified after it is created. An immutable object is an object whose state cannot be modified after it is created.
  - **Use:** Immutable objects make it easier to detect changes, make programs less complicated to think about and sharing is easy with references. If immutable objects are setup incorrectly though it could lead to poor performance due to multiple copies being made.
  - **Example:** To make an object immutable you could `Object.freeze()` which prevents new properties from being added and existing properties from being altered or removed.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] Explain the difference between synchronous and asynchronous functions.
  - **Explanation:** Synchronous functions are blocking while asynchronous functions are not. In synchronous functions, statements complete before the next statement is run. In this case, the program is evaluated exactly in order of the statements and execution of the program is paused if one of the statements take a very long time.
  - **Use:** Note that JavaScript is synchronous and it's actually the browser and Node.js that's actually asynchronous (think callbacks and promises)
  - **Example:**

```javascript
function f1() {
  // Some code   //synchronous
}
function main() {
  console.log('main');
  setTimeout(f1, 0); // async, with a callback of f1 function
  f2();
}
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [ ] What is event loop? What is the difference between call stack and task queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Explain the differences on the usage of foo between `function foo() {}` and `var foo = function() {}`
  - **Explanation:** The former is a function declaration while the latter is a function expression.
  - **Use:** The function declaration is hoisted and can therefore be accessed from anywhere, whereas the function expression can only be accessed after it's been defined.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [x] What are the differences between variables created using `let`, `var` or `const`?
  - **Explanation:** Variables declared using the var keyword are scoped to the function in which they are created, or if created outside of any function, to the global object. let and const are block scoped, meaning they are only accessible within the nearest set of curly braces (function, if-else block, or for-loop).
  - **Use:** var is hoisted and can be redeclared, whereas let and const cannot be redeclared. let and var can be reassigned, but const cannot be.
  - **Example:**

```javascript
if (true) {
  var thing1 = 'bar';
  let thing2 = 'baz';
  const thing3 = 'qux';
}

// var declared variables are accessible anywhere in the function scope.
console.log(thing1); // bar
// let and const defined variables are not accessible outside of the block they were defined in.
console.log(thing2); // ReferenceError: baz is not defined
console.log(thing3); // ReferenceError: qux is not defined
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
- [ ] What are the differences between ES6 class and ES5 function constructors?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
  - **Explanation & Use:** It simplifies the syntax needed to create functions and `this` is lexically bound meaning it uses `this` from the code that contains the arrow function.
  - **Example:** Notice that you do not need to `.bind(this)` for the below to work.

```javascript
var obj = {
  id: 42,
  counter: function counter() {
    setTimeout(() => {
      console.log(this.id);
    }, 1000);
  },
};
```

- **Source:** https://www.freecodecamp.org/news/when-and-why-you-should-use-es6-arrow-functions-and-when-you-shouldnt-3d851d7f0b26/
- [ ] What advantage is there for using the arrow syntax for a method in a constructor?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the definition of a higher-order function?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example for destructuring an object or an array?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example of a curry function and why this syntax offers an advantage?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the benefits of using spread syntax and how is it different from rest syntax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How can you share code between files?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [x] Why might you want to create static class members?
  - **Explanation:** Static class members are properties and methods that do not change.
  - **Use:** You would use them for properties that stay the same throughout the application and every instance of the object needs to know that property. They could also be used for utility functions so they can be called without instantiating any object.
  - **Source:** https://stackoverflow.com/questions/21155438/when-to-use-static-variables-methods-and-when-to-use-instance-variables-methods

### Javascript General

- [x] Can you name two programming paradigms important for JavaScript app developers?
  - OOP and Functional Programming are the most often used. OOP allows inheritance via different "classes". Functional is pure-functions without side effects.
  - **Source:** https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95
- [x] What is functional programming?
  - **Explanation:** Using pure functions with no side effects to compose your program.
  - **Use:** You avoid mutable data and shared states and instead make use of simple functions. It makes the code more predictable.
  - **Example:** Instead of having a function with two parameters that does two tasks, you break it into two functions. Each function would have a single parameter and do a single task.
  - **Source:** https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95
- [ ] What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the pros and cons of functional programming vs object-oriented programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Node

- [x] What is Node.js? Where can you use it?
  - Node.js is a single-threaded, open-source, cross-platform runtime environment used to build server-side and networking applications. It uses event-driven, non-blocking I/O architecture, which makes it efficient and suitable for real-time applications.
  - **Source:** https://kinsta.com/knowledgebase/what-is-node-js/
- [x] Why use Node.js?
  - **Explanation:** It uses fewer resources and memory because it is single threaded, it has wide adoption with many open source pacakages available, it is multi-platform and it simplifies the full stack as you can use just one language: Javascript.
  - **Use:** It's best used for real time applications that aren't data intensive. For programs that require more data processing a multi-threaded language like Java is a better choice.
  - **Source:** https://kinsta.com/knowledgebase/what-is-node-js/
- [ ] What are the features of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you update NPM to a new version in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is Node.js Single-threaded?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain callback in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is callback hell in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you prevent/fix callback hell?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the role of REPL in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Name the types of API functions in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the functionalities of NPM in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Node.js and Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are “streams” in Node.js? Explain the different types of streams present in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain chaining in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are Globals in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event-driven programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event loop in Node.js work? And How does it work?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the purpose of `module.exports` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Asynchronous and Non-blocking?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Tracing in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How will you debug an application in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between `setImmediate()` and `setTimeout()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `process.nextTick()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is package.json? What is it used for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is libuv?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the most popular modules of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `EventEmitter` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CS Theory 

- [x] What is recursion and give an example using javascript?
  - **Explanation:** Recursion is when a function calls itself within its own body. Besides the recursive call, it should always have a base case which stops it from calling itself to prevent infinite loops.
  - **Use:** Recursion is made for solving problems that can be broken down into smaller, repetitive problems. It is especially good for working on things that have many possible branches and are too complex for an iterative approach.
  - **Example:** A classic example is computing a factorial given a number `num`:

```js
function factorial(num) {
  if (num === 1) {
    return num;
  }
  return num * factorial(num - 1);
}
```

**Source:** https://developer.mozilla.org/en-US/docs/Glossary/Recursion

- [x] What are types?
  - **Explanation:** Types, also called data types, each have a unique set of rules/instructions of what can and can't be done with it.
  - **Use:** Types are necessary so that the computer knows how to handle data when trying to do an operation with it.
  - **Example:** A few data types that are shared by most programming language are:
    - Boolean (ex. true or false)
    - String ("hello world")
    - Float (3.1415)
  - **Source:** https://www.youtube.com/watch?v=A37-3lflh8I
- [ ] What are data structures?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is an algorithm?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is scope / lexical scope in javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is polymorphism?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is encapsulation?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Doubly Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Stack?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Hash Table?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Heap?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Trie?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Binary Search Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Disjoint Set?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Bloom Filter?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Bubble Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Insertion Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Merge Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Quicksort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

## Questions to ask your interviewer

1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

## Whiteboard

When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time 😉)

- **Parameters**
  - Inputs
  - Ask questions
    - Will it always be a number?
    - Will it ever be negative?
    - Any gotchas?
- **Returns**
  - Ask questions
    - Do you want it returned or is a console.log better?
    - Should I pass a whole array of solutions back or just a single solution?
- **Examples**
  - Show a couple black box examples, aka test cases
    - I pass in these arguments and get these results, is that correct?
  - Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
  - Write pseudocode of each of the steps

## Resources:

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
