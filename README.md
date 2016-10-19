## Using the sectionHeading column 

The sectionHeading becomes the heading for rows before the next populated sectionHeading. 


|sectionHeading||
|----|----|
|Heading 1||
||Row A|
||Row B|
|Heading 2||
||Row C|
||Row D|

Is rendered as:

```
## Heading 1

Row A

Row B

## Heading 2

Row C

Row D
```

## Schedule closures

Any row with a 'location' will be displayed.

## Traffic incidents

Any row with a 'location' will be displayed.

## Weekend impacts

Any row with an 'event' will be displayed 

## The javascript library that renders the HTML

Is part of the [Lexington Drupal theme](https://github.com/lfucg/lexingtonky.gov/blob/master/themes/custom/lex/js/lex-traffic-ticker.js)
