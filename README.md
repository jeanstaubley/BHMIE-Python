Purpose: MiePlot, made by Philip Laven, is a useful program that uses Mie Scattering Theory to produce a variety of plots given a set of parameters about how light scatters off of a surface (mainly homogeneous spheres). However, MiePlot is not entirely open source, so it is difficult to shape the program to work how one would like, such as running multiple parameters values at a time. MiePlot mentions it uses code direcly from the Absorption and Scattering of Light by Small Particles by Bohren, so I decided to translate the BHMIE code from the book into python to eventually make the program open source. This code is useful in many applications, notably its current use in CLidar research as well as optical systems in general. 

BHMIE Compiling Instructions.pdf - Details how to take the code from the Bohren textbook and convert it to python

BHMIE_translation.py - The python translation

test_phase_function.py - An update to the python translation code that outputs a phase function of three overlapping plots: the perpendicular polarized phase, the parallel polarized phase, and unpolarized phase. These plots can be directly compared to the output from the MiePlot program (as intented). There are commented lines in the code that specify what values can be changed (such as wavelength, refrctive indexes, radi, etc.) and what should be left untouched

Note from Jean: I'm currently working on more plot types that I will share to this github! Let me know any suggestions :)
