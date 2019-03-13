# Flexbox

## Flexbox Container and Items
Flexbox is the container, items are the immediate children of the container.
* display: flex || display: inline-flex
    * Everything that is in an immediate child is an item and can take flex properties.
    * Container properties:
        * flex-wrap
        * flex-direction
        * flex-flow
        * justify-content
            * defines lines on primary axis (appies to column if flex set to column)
            * flex-start, flex-end, center, space-between, space-around
        * align-items
            * works on the cross-axis.
            * flex-start, flex-end, center, stretch, baseline
        * align-content
            * for all the content at once.
            * works on the cross-axis.
            * flex-start, flex-end, center, space-between, space-around
    * Item properties
        * align-self
            * override align-items, change align of individual item.
            * flex-start, flex-end, center, stretch, baseline
        * order
            * positive or negative int
            * if order is specified, they are evaluated and place before items with no order.
        * flex-grow
            * ability for a flex itme to grow if necessary.  accepts value that serves as a proportion.
        * flex-shrink
            * ability for a flex itme to grow if necessary.
        * flex-basis
            * sets the initial size of a flex item
            * can think of as width, but can be used with grow / shrink
            * if set to auto, uses width.
            * the grow / shrink pivot.
        * flex
            * shorthand for flex-grow, flex shrink, flex-basis
            * flex: 1 1 auto;
            * flex: 0 1 auto;  no growth after width, but shrink.
See: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

