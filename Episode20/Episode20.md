[video source](https://www.youtube.com/watch?v=tN12g5QUIqg)
##FLEXBOX
    1. 1-D Layout method

(###Flexbox layout)[./images/flexbox.png]
(###Flex-direction)[./images/flex-direction.png]

justify-content: positions elements along main-axis
align items: positions elements along cross-axis
align-content: to handle the space between items

flex-Items attributes:
1. order: the sequence
2. flex-shrink: shrink factor
3. flex-grow: grow factor
4. flex-basis: set dimension
5. Align-self: positions elements along cross axis

flex items shorthand notation
flex: flex-grow flex-shrink flex-basis


##H/W
1. Shorthand notation for flexflow
    The flex-flow property is a shorthand property for setting both the flex-direction and flex-wrap properties.

        Example:
        .flex-container {
        display: flex;
        flex-flow: row wrap;
        }

    flex: flex-grow flex-shrink flex-basis