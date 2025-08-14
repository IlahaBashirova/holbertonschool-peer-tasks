# What is Flexbox? 
- Flexbox is a layout system in CSS for arranging the positions of items (for example in a row or in center and also in a column). 
- Flexbox is used for the aligning items. 
- Flexbox is better than traditional float positioning or inline-block items because have a natural height, gap. Also there are functions like align-items, justify-content, flex-direction ....
# Aligning Elements
- For using Flexbox first you should write ( display: flex; ). After that __justify-content__. Justify-content positions elements in main axes.
- Justify content( horizontally )
- - justify-content: flex-start; (elements positions from left to right)
- - justify-content: flex-end; (elements positions from right to left (items dont change their position) )
- - justify-content: center;
- - justify-content: space-between; ( spce-around and space-evenly )
- Align items positions elements in a csross axes. ( vertically )
- - align-items: center;
- - align-items: flex-start ( from top to bottom )
- - align-items: flex-end ( from bottom to top)
# Flex Axes and Properties
- Main axes means changings in a horizontal.
- Cross axes means changings in vertical.
- Changings by __flex-direction__:
- - flex-direction: row ( means that items are positioned from left to right) - horizontally changings
- - flex-direction: row-reverse ( means the same as a roe but items are from right to left ) - horizontally changings
- - flex-direction: column ( means that items are positioned from top to bottom ) -vertical changings
- - flex-direction: column (means the same but from bottom to top)- vertical changings
#  Flex Container vs. Flex Items
- Flex-container properties:
- - justify-content:
- - align-items: 
- - flex-direction: 
- Flex-items properties:
- - flex-shrink:
- - align-self:
- - flex-basis:
#  Flexbox Shorthands
- Flex shorthand - flex-basis, flex-shrink, flex-grow
- - flex: auto; 1 1 0
- - flex: 1; 1 1 auto
- - flex: 0; 0 0 auto