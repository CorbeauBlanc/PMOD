# PMOD
A simplistic interface to use the FMOD library with ponylang


## What the hell is this?
This is a small pony package that's meant to simplify the use of the FMOD library in any pony application you want to make. I did not recreate the lib, nor did I make new pony classes for each FMOD element, I simply wrapped all the FFI calls into one primitive and adapted them for ponylang types and functions. You can see this as a simple translation between two languages. Not all the functions are implemented currently, only the basics, but I will add more in the future

## Why does it exist?
Because FFI calls are ugly and a lot of C concepts are a real pain in the a** to translate into pony. Like pointers for example, and FMOD uses pointers _everywhere_.

## K. How does it work?
The installation is pretty easy:
	1) Copy the "PMOD" folder at the root of your project
	2) Include it in your code with `use` like any other pony package.
	3) That's it, you're done!

(currently no docs or wiki cuz I don't have time to do them so you'll have to look at the sources from here, sry. The primitive is named `FMOD` and is declared in "FMOD.pony")

## Additional notes
Please keep in mind that this is one of my very first projects in ponylang, so things might not be very well done. They should improve over time though as I learn more about the language. This is just a way to have a basic interface to work with and make the learning easier.
