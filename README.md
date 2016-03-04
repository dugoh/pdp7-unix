# pdp7-unix
This is a project to resurrect Unix on the PDP-7 from scans of the original assembly
code done by Norman Wilson. The scans of PDP-7 Unix are in the Unix Archive at
http://www.tuhs.org/Archive/PDP-11/Distributions/research/McIlroy_v0/
as the files 0*.pdf.

Update early March 2016: We've written an assembler, most of a user-mode
simulator and commented several source files. We now have these utilities
running: cat, cp, chmod, chown, chrm and ls.

Things to do: write a filesystem creation tool, write a shell, write the
missing utilities, try to bring the system up on a PDP-7 system. We have
a real PDP-7 and SimH as target platforms.

The code in the original scans are (c) Novell who own the rights to the Unix
source code. Everything that didn't come from the scanned files is GPLv3.

scans	  holds the unmodified OCR versions of the scanned files

src/cmd   holds the modified source code of the user-mode programs

src/sys   holds the modified source code of the kernel

src/other holds PDP-7 source code which did not come from the scanned files

tools	  holds the source for the tools written to assist the project

misc	  holds miscellaneous notes and information
