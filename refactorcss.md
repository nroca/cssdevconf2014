#Refactoring CSS
##Programming principles you can apply to your CSS
- #refactorcss
- @johnwlong
- thesassway.com

##Why refactor your css?
- bit.ly/css-for-grownups
- CSS is programming, needs to learn from programming before it

##What is refactoring
- a disciplined approach to changing code to make it easy to understand and cheaper to modify in the future withotu changing it's observed behavior.
  - based on Martin Fowler's definition
- make your code self evident

##Goals of refactoring
- clean and maintainable code
- easy to understand
- composable parts
- reusable without modification
- parts behave the same in all contexts
- hard to break

##This is Modular CSS
- SMACSS smacss.com
- BEM bem.info
- OOCSS oocss.org

##What is Modular CSS
- thesassway.com/modular-css
- Objects / .button
- Child Objects / .button-icon
- Subclasses / .primary-button
- Modifiers / .is-selected
- bit.ly/menu-1
- bit.ly/menu-2
- bit.ly/menu-3

##Refactoring Categories
- Techniques for abstraction
- Techniques for breaking up code
- Techniques for improving names

##Abstraction Patterns
- Extracting Objects
- Extracting Child Objects
- Extracting Subclasses
- Extracting Modifiers

##Breaking up code
- Decomposing objects
- Assembling larger components from several objects
- Extracting mixins and functions
- Removing duplication (DRY)

#Improving Names
- Simplify a selector
  - remove ID or element selectors
  - renaming objects, mixins, functions, variables
- Move into subclass/superclass
- Refactor comment to mixin

> "If you have to turn off styles, you're probably doing it wrong."
