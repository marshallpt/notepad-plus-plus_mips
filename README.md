# Notepad++ MIPS Syntax Highlighting
MIPS Assembly Notepad++ syntax highlighting, based on the [MARS (MIPS Assembly 
and  Runtime Simulator)](http://courses.missouristate.edu/KenVollmar/MARS/index.htm)
 colors.

<p align="center">
  <img src="assets/comparison.png" alt="Comparison Image"/>
</p>

The differences I'm currently aware of:

1. Labels are not _italicized_ in N++. This is because I couldn't figure out 
how to do it [with UDL](https://ivan-radic.github.io/udl-documentation/), and
it doesn't bother me too much.
2. Strings wrapped in "" and '' are **purple** in N++ instead of **green.** 
This was a conscious choice, as comments being an exclusive color is
desirable. There's probably a better option than purple, but that's 
just what made sense in the moment.
