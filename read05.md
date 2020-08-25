# How Css Rules Cascade
*Our Code in HTML will be as a structure even If we run it to see the 
result. CSS will make it colorful and well organized.*
Here is some example of HTML codes:
> <h1>Potatoes</h1>
> <p id="intro">There are <i>dozens</i> of different
> <b>potato</b> varieties.</p>
> <p>They are usually described as early, second early
 and maincrop potatoes.</p>
**The above examples will appear as just written things, and you
 can its code, we can say it is just what I need, But what about 
 how it looks**

**What we can do using CSS Language:**

**LAST RULE**
If the two selectors are identical,the latter of the two will take
precedence. Here you can see the second i selector takes precedence 
over the first.

**SPECIFICITY**
If one selector is more specific than the others, the more specific
 rule will take precedence over more general ones. In this
example:
h1 is more specific than * p b is more specific than p p # intro is 
more specific than p

**IMPORTANT**
You can add !important after any property value to indicatethat it 
should be considered more important than other rulesthat apply to
 the same element

**When you use CSS you can do the formating codes in a separate sheet
 Why use External Style Sheets?**
 *When building a website there are several advantages to placing your
CSS rules in a separate style sheet.*

*Sometimes you might consider placing CSS rules in the same page as
your HTML code*

**Different versions of CSS & Browser Quirks**
*CSS1 was released in 1996 and CSS2 followed two years later. Work on
CSS3 has been ongoing but the major browsers have already started to
implement it.*

# Summary of chapter 10:
**INTRODUCING CSS**
> CSS treats each HTML element as if it appears insideits own box
 and uses rules to indicate how that element should look. that means 
 using CSS keep in mind every element in your website is a box.

> Rules are made up of selectors (that specify the elements the rule 
  applies to) and declarations (that indicate what these elements should
  look like).

> Different types of selectors allow you to target your rules at
  different elements.

> Declarations are made up of two parts: the properties of the element
  that you want to change, and the values of those properties. 
  For example, the font-family property sets the choice of font, and the
  value arial specifies Arial as the preferred typeface.

> CSS rules usually appear in a separate document, although they may 
  appear within an HTML page.


#Summary of chapter 11:
**COLOR**
> Color not only brings your site to life, but also helps convey the
 mood and evokes reactions.

> There are three ways to specify colors in CSS: RGB values, hex codes,
 and color names.

> Color pickers can help you find the color you want.

> It is important to ensure that there is enough contrast between any 
text and the background color (otherwise people will not be able to read
 your content).

> CSS3 has introduced an extra value for RGB colors to indicate
 opacity. It is known as RGBA.

> CSS3 also allows you to specify colors as HSL values,with an optional
 opacity value. It is known as HSLA.