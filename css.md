**What CSS does?**
CSS allows you to create rules that specify how the content of
an element should appear

**BLOCK & INLINE ELEMENTS :** 

* Block level elements look
like they start on a new line.
Examples include the <h1>-
<h6>, <p> and <div> elements.

* Inline elements flow within the
text and do not start on a new
line. Examples include <b>, <i>,
<img>, <em> and <span>.

*CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented *


#**CSS Properties Affect How Elements Are Displayed**

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon

This rule indicates that all <h1>,
<h2> and <h3> elements
should be shown in the Arial
typeface, in a yellow color.
Properties indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.
Values specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be.

#**Using External CSS**

**<link>**
The <link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the <head> element.
It should use three attributes

**href**
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
type
This attribute specifies the type
of document being linked to. The
value should be text/css.

**rel**
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.

**How Css Rules Cascade**

If there are two or more rules
that apply to the same element,
it is important to understand
which will take precedence.
LAST RULE
If the two selectors are identical,
the latter of the two will take
precedence. Here you can see
the second i selector takes
precedence over the first.
SPECIFICITY
If one selector is more specific
than the others, the more
specific rule will take precedence
over more general ones. In this
example:
h1 is more specific than *
p b is more specific than p
p#intro is more specific than p
IMPORTANT
You can add !important after
any property value to indicate
that it should be considered
more important than other rules
that apply to the same element.

# **Inheritance**

If you specify the font-family
or color properties on the
<body> element, they will apply
to most child elements. This is
because the value of the
font-family property is
inherited by child elements. It
saves you from having to apply
these properties to as many
elements (and results in simpler
style sheets).
You can compare this with
the background-color or
border properties; they are not
inherited by child elements. If
these were inherited by all child
elements then the page could
look quite messy.

