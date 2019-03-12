# Fonts
## Font-Size
* px for Pixels, not very scalable
* rem (root em) based on users browser settings
* vm (Viweport width) 100 vw available, set to a fraction of vw to scale as screen resizes.
* vh (Viewport height) 1/100th of height of viewport
* % percentage (relatice to parent elemen font size)

## Font-Weight
* normal
* bold
* lighter
* darker

## Font-Style
* italics
* underline

## Font-Variant
* small-caps

## Text-transform
* uppercase (all uppercase)
* capitalize
* lowercase
* etc...

## line-height
space between lines: letting
* normal
* number value
* length data type (rem, vw)
* setting line-height to div height is a way to vertically center.

## letter-spacing
space between letters: kerning
* normal
* number
* length

## word-spacing
space between words
* normal
* number
* length

## color
Set text color
* hex, RGB, HSL values

## text-align
* left, center, right

## text-shadow
Add shadow to text
* offset-x, offset-y, blur-radius, color
* text-shadow: 1px 1px 2px black;

## text-indent
indentation amount to indent text in a block.

# Semantic HTML

## Elements
* header
    * introductory content or navigational aids
    * can't be descendent of header, footer, or address.
* nav
    * section with navigation links
    * intended for major block of navigation links
    * not necessary for use in footer
* main
    * main content of the body of a document or application
    * should be unique to the document
    * not a descendent of article, aside, footer, or nav
* article
    * Can stand on their own.  Self-contained
        * forum post
        * Magazine article
        * blog post
        * user review
* section
    * thematic group of content
    * article - section - article nesting related elements.
    * not a generic container, use div for that
    * if section can stand on its own, use article.
* aside
    * content related to something
    * examples
        * side bars
        * inserts
        * adertisements
        * author bio
        * other related info
* footer
    * examples
        * author info
        * copyright data
* h1-h6
    * heading
    * outlining, 1-6, organize content.
* figure
    * Picture or an Image.
    * image and figcaption inside.
* figcaption
    * Caption of a figure, child of figure tag
* address
    * context information for nearest article.

