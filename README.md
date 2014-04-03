## Introduction

The Manjaro Linux Beginner's User Guide typeset in LaTeX (using LyX).

The style in use is tutfe-book (http://wiki.lyx.org/Layouts/Tufte-book). This provides a very professional layout with minimal fuss.

## Installation

To enable the tutfe-book layout within LyX on Manjaro you will need to install the following packages:

    sudo pacman -S lyx texlive-pictures texlive-latexextra

Installing LyX should pick up the base dependencies; tutfe-book requires the extra libraries. Remember to reconfigure LyX after installing the new libraries!

## Cover art

Current cover art is created in Inkscape. You will also need comfortaa from AUR for the Manjaro logo text:

    yaourt -S ttf-comfortaa

LyX will neatly insert/append PDF files; to make things easy cover art should therefore be exported as a PDF document.

![Manjaro User Guide cover](raw/master/cover.jpg)
