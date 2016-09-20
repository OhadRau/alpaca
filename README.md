# Alpaca

This repository is for the Alpaca fork of the OCaml compiler, implementing an alternate dialect of OCaml with a different feature set/syntax.

Alpaca's goals are:
* Breaking compatability for historic choices that have been left in
  + No need to keep old OCaml code compiling, so old features can still be changed
* Improved syntax
  + Syntax should be less ambiguous (`match ... with ... end`)
  + Syntax should make intent more clear
* Better standard library
  + OCaml's standard library has long been a matter of criticism for the language
  + Because of missing features, new alternative libraries (Batteries, Core, Base, Containers) have cropped up
    - Why not make a language that takes all these positives into the core in the first place?
* Providing better language extensions, especially in terms of syntactic sugar and type system features
  + Things like modular implicits and effect systems can be added
