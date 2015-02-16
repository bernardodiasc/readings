# HTML Selectors

- http://www.w3.org/html/wg/drafts/html/master/index.html
- http://html5doctor.com/element-index/

_(below have cherry-picked most useful selectors -- for a very specific need)_

## Article

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-article-element
- http://html5doctor.com/the-article-element/

> Represents a section of a page that consists of a composition that forms an independent part of a document, page, or site. This could be a forum post, a magazine or newspaper article, a Web log entry, a user-submitted comment, or any other independent item of content.

## Aside

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-aside-element
- http://html5doctor.com/aside-revisited/

> Represents a section of a page consisting of content that is tangentially related to the content around the aside element, and which could be considered separate from that content. Such sections are often represented as sidebars in printed typography.

## Section

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-section-element
- http://html5doctor.com/the-section-element/

> Represents a generic document or application section. In this context, a section is a thematic grouping of content, typically with a header, possibly with a footer. Examples include chapters in a book, the various tabbed pages in a tabbed dialog box, or the numbered sections of a thesis. A web site's home page could be split into sections for an introduction, news items, contact information.

## Nav

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-nav-element
- http://html5doctor.com/nav-element/

> Represents navigation for a document. The nav element is a section containing links to other documents or to parts within the current document.
> Not all groups of links on a page need to be in a nav element — only groups of primary navigation links. In particular, it is common for footers to have a list of links to various key parts of a site, but the footer element is more appropriate in such cases.

## Main

- http://www.w3.org/html/wg/drafts/html/master/grouping-content.html#the-main-element

> The main element is an exact analogue of ARIA's role="main", and is designed to show screenreaders and assistive technologies exactly where main content begins, so it can be a target for a "skip links" keyboard command, for example. It could also be used for content syndication (Instapaper-ish things); mobile browsers could zoom in on main when encountering non-responsive websites. It should therefore be used once per page. If you use something like `<div id="main">` (or similar, such as `<div id="content">`), simply replace that with `<main role="main">`.

## Header

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-header-element
- http://html5doctor.com/the-header-element/

> Represents the "header" of a document or section of a document. The header element is typically used to group a set of h1–h6 elements to mark up a page's title with its subtitle or tagline. header elements may, however, contain more than just the section's headings and subheadings — e.g., version history information or publication date.

## h1-h6

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements

> Represent headings and subheadings. These elements rank in importance according to the number in their name. The h1 element is said to have the highest rank, the h6 element has the lowest rank, and two elements with the same name have equal rank.

## Footer

- http://www.w3.org/html/wg/drafts/html/master/sections.html#the-footer-element
- http://html5doctor.com/the-footer-element-update/

> Represents the "footer" of a document or section of a document. The footer element typically contains metadata about its enclosing section, such as who wrote it, links to related documents, copyright data, etc. Contact information for the section given in a footer should be marked up using the address element.

## Blockquote

- http://www.w3.org/html/wg/drafts/html/master/grouping-content.html#the-blockquote-element
- http://html5doctor.com/blockquote-q-cite/

> The blockquote element represents a section that is quoted from another source.
Content inside a blockquote must be quoted from another source, whose address, if it has one, may be cited in the cite attribute.

## Cite

- http://www.w3.org/html/wg/drafts/html/master/text-level-semantics.html#the-cite-element

> The cite element represents the title of a work (e.g. a book, a paper, an essay, a poem, a score, a song, a script, a film, a TV show, a game, a sculpture, a painting, a theatre production, a play, an opera, a musical, an exhibition, a legal case report, etc). This can be a work that is being quoted or referenced in detail (i.e. a citation), or it can just be a work that is mentioned in passing.
> A person's name is not the title of a work — even if people call that person a piece of work — and the element must therefore not be used to mark up people's names. (In some cases, the b element might be appropriate for names; e.g. in a gossip article where the names of famous people are keywords rendered with a different style to draw attention to them. In other cases, if an element is really needed, the span element can be used.)

## Pre

- http://www.w3.org/html/wg/drafts/html/master/grouping-content.html#the-pre-element

> The pre element represents a block of preformatted text, in which structure is represented by typographic conventions rather than by elements.

## Code

- http://www.w3.org/html/wg/drafts/html/master/text-level-semantics.html#the-code-element

> The code element represents a fragment of computer code. This could be an XML element name, a filename, a computer program, or any other string that a computer would recognize.