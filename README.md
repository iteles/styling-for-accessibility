# Styling for Accessibility [Work in progress]

>"The power of the Web is in its universality. Access by everyone regardless of disability is an essential aspect."    - Sir Tim Berners-Lee


This is a living collection of accessibility tips for the most common situations we have come across when building web apps.

## Content Guide
+ [What is Web Accessibility?](#what-is-web-accessibility)
+ [Why do it?](#why-do-it)
+ [The HTML basics of Accessibility](#html-basics)
+ [CSS styling for Accessibility](#css-styling)
+ [**Styling for Accessibility Checklist**](#styling-for-a11y-checklist)
+ [Further Reading - HTML Accessibility](#further-reading--HTML-Accessibility)

## What is web accessibility?
> Web accessibility means that people with disabilities can use the Web <sup>1</sup>

Accessibility is often equated with making sure your site works well with screen readers, but there are [4 different kinds of accessibility](http://a11yproject.com/posts/myth-accessibility-is-blind-people/). It's useful to know how each of these groups of people navigate the Internet:    


| Impairment |Examples of how the Internet is used |
|---|---|
| Visual | Screen readers and increased text size in browsers|
| Auditory | Often standard browsers but require subtitles and visual cues for audio content |
| Motor | Largest range: keyboard-only navigation, eye tracking technology, mouth sticks, head pointers |
| [Cognitive](http://ncdae.org/resources/articles/cognitive/) | Sometimes screenreaders for those with difficulty in understanding the written language but often standard browsers, requiring websites to be simple, intuitive, concise and have a exceedingly clear navigational structure |


## Why do it?
We don't feel the need to make the argument for [why your site should be accessible to users with disabilities](http://24ways.org/2013/why-bother-with-accessibility/), you should know that instinctively.      
But we _do_ want to remind you that **making your site accessible benefits _everyone_ who comes to your site, not only those with disabilities** (and gives you a warm fuzzy feeling).     
Think of how increasing the contrast of certain things is great for people with visual impairments (including older people), but also makes your call to action 'pop' for those with 20-20 eye sight, or how great keyboard access is not only used by people with tremors who can't use a mouse but also by power users or those with repetitive strain injuries (RSIs) who navigate the web without ever taking their fingers off the keyboard.
  
## HTML basics
_Most_ [a11y](https://en.wiktionary.org/wiki/a11y) issues I've come across are fixed in the HTML so there are _lots_ of [resources on HTML for accessibility](#further-reading--HTML-Accessibility); that's not the subject of this repo.
However, here is a short list of the _main_ issues you'll come across so that they are referenced in the same place.
    
### Logical order
Make sure your HTML makes sense if you read through it from top to bottom - this is the order that people with screen readers will digest your content.

### Accessible Forms
TBC

## CSS Styling

### Text size
Any text that is **less than 10px** will usually be flagged up as _too small_ by accessibility checkers.   
Note that most browsers default to 16px text so if you're working with `em`s, `rem`s or `%`, you need to size accordingly.


## Further Reading - HTML Accessibility
[resources to be added here]


<sup>1</sup> https://www.w3.org/WAI/intro/accessibility.php
