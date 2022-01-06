# Slopegraphs-and-R-A-pleasant-diversion-May-26-2018

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
======================

This repository holds some working code for creating "slopegraphs" in R.This is very much a work in progress. Once it's more stable, I will release the package to CRAN.

The package currently includes one mainfunction, slopegraph(), which produces a slopegraph from an observation-by-period data frame. Everything is more or less drawn automatically, but is highly customizable in terms of line and text colors, font sizes and styles, axes, titles, and plotting behind and in front of the slopegraph lines. An underlying function, segmentize() produces the data structure used for the actual plotting. And a new function, ggslopegraph() does the same as slopegraph() but using ggplot2 graphics.

The related scripts for Slopegraph package is attached with this repository as .ZIP file to follow.
