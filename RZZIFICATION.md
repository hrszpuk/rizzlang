# Rizzification
A specification for the rizz programming language.

## Table of Contents
- [Variables](#variables)
- [Values](#values)
- [If statements](#if-if-else-and-else-statements)
- [Switch statements](#switch-statement)
- [Loops](#loops)
- [Lists](#lists)
- [Functions](#functions)
- [Sum types](#sum-types)
- [Product types](#product-types)
- [Traits](#traits)
- [Error handling](#error-handling)
- [Namespaces](#namespace)
- [Packages](#packages)
- [Standard library](#standard-library)
  - [String](#string)
  - [IO](#io)
  - [Maths](#maths)
  - [Collections](#collections)
  - [Random](#random)
  - [Datetime](#datetime)
- [Complete example](#complete-example)
 
## Variables
## Values
## If statement
## Pattern matching
## Loops
## Lists
## Functions
## Sum types
## Product types
## Traits
## Error handling
## Namespace
## Package
## Standard library
### Prelude
### String
### IO
### Maths
### Collections
### Random

## Complete Example
```
// Variables and values
sigma x is 100 + 200 - 300 * 400 / 500
sigma y is cringe and based or not cringe
sigma z is "Hello, World!"

// If statement
vibe check x is less than 100 then yap "x < 100"
ratio x is 100 then yap "x == 100"
ratio x is greater than 100 then tap "x > 100"
ratio then yap "idek"

// Pattern matching
goofy x 
  ahh 100 then yap "x == 100"
  ahh <100 then yap "x < 100"
  ahh >100 then yap "x > 100" fall
  ahh -100..0 then fall
ahh then yap "oh no" then sigma x is 10

// Loops
cooking y 
  then x is x - 1
  then yap x
  then vibe check x is 0 then big yikes
cooked

cooking from x to 0
  then sigma i is x's index
  then yap i
cooked

// Lists
sigma squad is [based, cringe, based, based]
sigma squad2 is [..squad, based, based]

cooking through squad with item
  yap item
cooked

// Functions
slay double with sigma a then rizz a * 2
slay string_to_list with sigma s
  then sigma l is []
  then cooking through s with c then append c to l cooked
  then rizz l

/// Main function
main character with sigma argc argv
  then yap z
rizz 

// Sum types
zesty Game is Win or Loss

sigma g is Win
sigma g is Game Win // the same

// Product types
combo Point is sigma int x int y

sigma p is Point 10 10

// Traits
looksmaxxing Barkable where
  slay bark then yap "Bark"
over

glow up Barkable for Point where
  slay bark then yap "Bark"

// Error handling
slay some_func with sigma a 
  then vibe check a is not 100 then clapback "a is not 100" r
       ratio then rizz a

yap (yeet some_func)

// Namespace
era Code where
// ...
era over

// Packages
grab SomePackage from "../.."
grab IO
grab Maths
grab Random
```
 






