# The Comic Book Library Project - Design Briefing

The Comic Book Library Project aims to create a modern interface to display comic book information. It is an open source and community based projects at a very early stage. This call for design repository aims to get design varations to create a working prototype.

## Background and Goal

There are a number of fantastic comic book related sites out there that collects an invaluable amount of data. Projects such as http://comicbookdb.com/, https://inducks.org/ or https://www.comics.org/ have acquired a tremedous amount of inforamtion, but all lack an easy to browse, and user friendly presentation of data, especially for people new to comic books. 

This project aims to create an easy to brows as visually appealing website that leverages the data from the projects mentioned above, while also incorporating data from sites as https://www.amazon.com/, https://www.goodreads.com/, https://www.bookfinder.com/, https://en.wikipedia.org and others. 

This repository is merely a call for designs, not the actual project. It serves as a design briefing for interested people to submit their designs.

The target audience are people new to comic books and the casual collector. We do not aim to replace resources like http://comics.org, who appeal more to the profession (or obsessed) collector. While being an obsessed collector myself, I do find myself browsing several resources to research a comic before buying it. I also find it difficult to send one URL when recommending a comic. Hence, the Comic Book Library Project aims to create the missing link.

### Who should submit

The project looks for designers that have a good understanding of the comic book industry and understand the difference between a comic book issue, a colleced edition, a series and what a graphic novel is. 

### Design Requirements

* Plain html/css files, optimized for desktop only (for now)
* No javascript
* Self-contained assets, e.g. all css and images need to be part of your submissions
* There are no pre-defined color-schemes, but an easy to read version is preferred (light or dark mode) 
* The design should focus on the content, there is no need for an extensive menu, footer or other navigational elements

# The Wireframes

Please check the wireframes folder to see wireframes for the individual pages. The wireframes are for information design only and are not meant to be a blueprint for the visual design. So you are free to create your own visual design, as long as the majority of the information displayed on the wireframes are kept.

## Wireframe: Series Group Page

<img src="https://github.com/bk-one/clib-briefing/blob/master/wireframes/series_group_page.png" width="100" align="left" title="Series Group Page"  style="padding-right: 3em; padding-bottom: 1em; float: left;">

A `Series Group` in this project is a collection of all `Series` of a specific comic, e.g. *Spider-Man*, which consists of several `Series`, e.g. *The Amazing Spider-Man, Vol. 1*, *The Amzing Spider-Man, Vol. 2* or *Ultimate Spider-Man, Vol 1*.

A `Series Group` shows general, top-level information, lists all `Series Groups` and might highlight some `Collected Editions`.


<p style="clear: both;" />

## Wireframe: Series Page

<img src="https://github.com/bk-one/clib-briefing/blob/master/wireframes/series_page.png" width="100" title="Series Page" align="left" style="padding-right: 3em; padding-bottom: 1em; float: left;">

A `Series` is an individual series of a `Series Group`. A typical `Series` is *The Amazing Spider-Man, Vol. 1*, *Batman, Vol. 2 (The New 52)* or *Locke & Key: Welcome to Lovecraft*.

It gives detailed information about the series and will list all issues or `Comics`, as well as colleced editions of the `Series`. The page itself will never list all issues, additional sub-pages will be developed to show a list of all issues. 

<p style="clear: both;" />


### Wireframe: Comic Page

<img src="https://github.com/bk-one/clib-briefing/blob/master/wireframes/comic_page.png" width="100" title="Comic Page"  align="left" style="padding-right: 3em; padding-bottom: 1em; float: left;">

The `Comic` is an indivial issue of a `Series`. It belongs to exactly one `Series` but can be in multiple `CollectedEditions`. It focuses on technical aspects of the issue (format, people involved, etc.) and is not meant to be a often visted page.


<p style="clear: both;" />

### Wireframe: Collected Edition

<img src="https://github.com/bk-one/clib-briefing/blob/master/wireframes/collected_edition.png" width="100" title="Collected Edition Page"  align="left" style="padding-right: 3em; padding-bottom: 1em; float: left;">

A `Collected Editiom` collects several `Comics` from one or many `Series`. A `Collected Edition` comes in one or several editions, e.g. a Trade Paperback, a Hardcover or an Absolute Edition.



<p style="clear: both;" />

## Submission Rules


### CSS Style

Please use flowbox based CSS with small, atomic and expressive class names. See https://css-tricks.com/growing-popularity-atomic-css/ for reference.


### How to submit

Fork this repository (see https://help.github.com/en/articles/fork-a-repo), create a subfolder with your handle and submit a pull request with your designs. The design itself should be in plain html/css with all images and assets reatively linked from your repo. Please use the same names for your html files as the wirefraems. 

Please see this sample structure:

```
  clib-briefing/<your github name>/
  clib-briefing/<your github name>/collected_edition.html
  clib-briefing/<your github name>/series.html
  clib-briefing/<your github name>/styles/detault.css
  clib-briefing//<your github name>/assets/image1.png
  clib-briefing//<your github name>/assets/image2.png
   
```

### Recommendations on submition

* Iterative work is encouraged, submit early and incremental
* The wireframes are created via moqups.com and are using their standard stencils. The stencils are not meant to be design guidelines
* Incorporate other community work (e.g. from deviantart)
* You are free to incorporate your own ideas and information, e.g. reviews, podcasts or videos
* You don't have to submit all pages, just one or two example pages that you're most comforatble with is a great start
* Readablity is more important than information overload

