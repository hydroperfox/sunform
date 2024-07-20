# Sunform

Sunform is a multi-media framework that supports ActionScript 3 as the main scripting language.

The Sunform SDK contains a MXML compiler that compiles ActionScript 3 and MXML. MXML files describe GUI components tied to an ActionScript 3 package.

* ASDoc is a tool used for generating HTML documentation from ActionScript 3 code.

The Sunform SDK contains a flexible package manager which the MXML compiler is oriented to, which is able to create new projects through easy commands, build, debug, test units, share, generate ASDoc, and more.

An online service may auto generate ASDoc for Sunform packages that have been shared online.

The Sunform API supports bitmaps with alpha channel, shapes, effects, transforms, and more, in a display list tree. The display list is normally 2D; for a GPU sublayer, use the Display 3D API.

The Sunform Builder app enables creation of multi-media applications through an incorporated code editor and provides several interfaces such as for debugging and publishing an app.

## MXML compiler

The MXML compiler generates a WebAssembly module.

## Sunform implementation

Most ofthe Sunform SDK components are implemented in the Rust language, including the MXML compiler.
