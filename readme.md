# CSS -  Cascading Style Sheets (Style)

## 3 ways to style with CSS

-Inline -> putting the style attribute on the element itself
  -not recommended (last resort)
  -old way
  -only used if you cannot use the other two ways

-Internal -> using a style tag inside the HTML file
  -styles one page
  -not recommended

-External -> seperate file with a link in the head of the HTML
  -can be used on multiple HTML pages

-CSS Selectors - waht elements do you want to style?
-Rule -> How do you want to style the elements you grabbed?
  -key -> style application
  -value -> what do you want the style application to be equal to

  -Specificity -> more specific a CSS selector is, the more priority is given
    -inline is the most specific
    -id
    -classes
    -elements
    -order matters

  -Box Model -> EVERYTHING is a box
    -content - everthing inside
    -border - the edge of what is shown for the element
    -padding - space between the border and the content
    -margin - space between elements

  -Optional
    -size units
      -px - pixels
      -percentages
    -Block vs Inline-Block
    -Float
    -Tables