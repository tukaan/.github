# Tukaan
![logo](https://user-images.githubusercontent.com/95927277/165413444-0eed52ae-b870-4379-9714-977599a76c01.png)

## Tukaan is a modern, cross-platform GUI framework for Python, which aims to replace Tkiner.
Why not Tkinter?
Tkinter is just a wrapper around Tk, that is so thin, that you can see through it, and even has holes on it. If you have ever used Tkinter, you know, it's kinda dumb. There are a lot of things not implemented in Tkinter, that you can only access with Tcl calls. Tukaan has everything you could need, and maybe even more :)

In Tcl almost everything is represented as strings, and Tkinter doesn't always convert them to Python objects, so you have to do that yourself. If you mess something up, it won't raise a Python exception, but Tcl a error instead, which you don't understand, even if you know the Tcl language.

Tkinter also looks awful by default. You can change this, if you use the the Ttk extensions. But why should you use extensions to make your GUI not look like it came from the 90's? With Tukaan this is completely different. The apps look native by default on Windows and on MacOS as well. Unfortunately this isn't possible on Linux, but it still uses a better theme than the Tk default.
