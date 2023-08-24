---
title: 'DMP'
teaching: 10
exercises: 2
editor_options: 
  markdown: 
    wrap: 72
---

::: questions
-   What is a Data Management Plan (DMP)?
-   When should a researcher make a DMP?
-   What information should a DMP contain?
:::

::: objectives
-   Name the components covered in a DMP
-   Articulate the purpose(s) of a DMP
:::

## What is Data Management?

Data management is a broad term that encompasses collecting, storing,
sorting, organizing and sharing data. We all use some form of data
management in our lives: making lists, saving photos in a folder with
the name of the trip, or even scrapbooking. For researchers, data
management is important to make sense of the often vast amounts of data
they collect. Good data management makes it easy to find a specific
piece of information again, enhances reproducibility by making it clear
what data were used to support which conclusion, and increases security
by keeping track of sensitive information.

This is a lesson created via The Carpentries Workbench. It is written in
[Pandoc-flavored Markdown][pandoc] for static files (with extension
`.md`) and [R Markdown][r-markdown] for dynamic files that can render
code into output (with extension `.Rmd`). Please refer to the
[Introduction to The Carpentries Workbench][carpentries-workbench] for
full documentation.

What you need to know is that there are three sections required for a
valid Carpentries lesson template:

1.  `questions` are displayed at the beginning of the episode to prime
    the learner for the content.
2.  `objectives` are the learning objectives for an episode displayed
    with the questions.
3.  `keypoints` are displayed at the end of the episode to reinforce the
    objectives.

::: instructor
Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"
:::

::: challenge
## Challenge 1: Can you do it?

What is the output of this command?

``` r
paste("This", "new", "lesson", "looks", "good")
```

::: solution
## Output

``` output
[1] "This new lesson looks good"
```
:::

## Challenge 2: how do you nest solutions within challenge blocks?

::: solution
You can add a line with at least three colons and a `solution` tag.
:::
:::

## Figures

You can use pandoc markdown for static figures with the following
syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for accessibility purposes'}`

![Blue Carpentries hex person logo with no
text.](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg)

## Math

One of our episodes contains $\LaTeX$ equations when describing how to
create dynamic reports with {knitr}, so we now use mathjax to describe
this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes:
$\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::: keypoints
-   Use `.md` files for episodes when you want static content
-   Use `.Rmd` files for episodes when you need to generate output
-   Run `sandpaper::check_lesson()` to identify any issues with your
    lesson
-   Run `sandpaper::build_lesson()` to preview your lesson locally
:::
