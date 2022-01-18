# DVE-Sample

Copy of the original release post at QJ.net:

<blockquote>
DAX's "Hello World" app: Fullscreen TV out for Homebrew
Posted Oct 15, 2007 at 3:03AM by QJ Staff Listed in: Homebrew Applications, Homebrew Development Tags: component cables, Dark AleX, Sony

DAX's Homebrew coder Art dropped by the QJ.NET PSP Development Forum and shared an application created by Dark AleX that allows programmers to access the PSP Slim & Lite's TV out capabilities using component, composite, and d-terminal cables. More than a full program, this one is more of a "Hello World" proof that the hack can be done.

Art added that the resolution for composite cables is 720x503 while using component cables will yield a resolution of 720x480. The program has not been tested formally with D-terminal cables but it basically uses the same code as that of the component's. Art added:


To use it in your code, you just have to replace the call to sceDisplaySetMode with the call to my custom function pspDveMgrSetVideoOut (which calls sceImposeSetVideoOutMode, which at the end calls sceDisplaySetMode), and be aware of the bigger resolution.

This really is an exciting development especially that Sony has reiterated time and again that certain cables can only be used for certain functions. Keep checking back here at QJ.NET to know if this work-in-progress application has been made into a fully functional homebrew application.
</blockquote>
