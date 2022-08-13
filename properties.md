## flex-container

1. flex-direction: row | row-reverse | column | column-reverse

2. flex-wrap:nowrap
   wrap items on new-line if there is no much space to fit in

3. justify-content: flex-start
   how flex items will be aligned along the main(horizontal) axis

4.align-items: stretch | flex-start
how flex items will be aligned along the cross(vertical) axis

5. align-content: stretch | flex-start
   applies when there is more than one row of flex items
   Controls how the rows are aligned along the cross axis if there some empty space

## Item

1. align-self: auto | stretch
   works the same as align-items but with only one individual item

2. order: defines the order in which one specific flex item should appear inside the container

3. All of these 3, help flexbox decide the width of flex item

   - flex-grow: 0; : how much an item can grow
   - flex-shrink: 1; : how much an item can shrink
   - flex-basis: auto : defining the base width of an item

   => Shorthand for all those 3 : flex: 0 1 auto;