# CSS-Tricks
A project where I am covering CSS

## Learning outcomes
* Understand how to use parent and sibling selectors
* Recognize the difference between pseudo classes and pseudo elements
* Learn about some of the most useful and common pseudo elements and pseudo classes
* Learn about the different ways to select an attribute or its parts

## Attribute Selectors
* [attribute] - This general selector will select anything where the given attribute exists. Its value doesn’t matter.
* selector[attribute] - Optionally we can combine our attribute selectors with other types of selectors, such as class or element selectors.
* [attribute="value"] - To get really specific, we can use = to match a specific attribute with a specific value.
![Attribute Selectors](https://user-images.githubusercontent.com/48117356/188313858-2aca9323-a998-42c6-88ca-d1e11fc26c0b.png)
# Using Custom Properties
The syntax for declaring and accessing a custom property is really simple and not too different from how we write normal rule declarations:
![Custom Properties](https://user-images.githubusercontent.com/48117356/188313851-ea0780ca-b7b4-4944-b2d6-d2afa1e87fe1.png)
That’s it! First, we declare our custom property with a double hyphen followed by a case-sensitive, hyphen-separated property name (color-error-text wouldn’t be the same as Color-Error-Text). The use of single hyphens to separate words is very important here because spaces are not valid (--color error text would not work). Then we can store any valid CSS value in our newly declared custom property, whether it be a simple color value, shorthand values, or even a more complex function, just to give you a few examples.

When we want to access a custom property, we use the var() function as the value of a CSS property, and then place our custom property inside of the parenthesis (including the double hyphen at the beginning).

