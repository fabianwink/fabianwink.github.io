---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Fabian, an Dual Student at the IU International University in Cologne, Germany with my main emphasis in Data Analytics. I am also working at Medcon Health Contents GmbH part of Biermann Medizin GmbH on the maintanance and configuration of the Newsletter and Website in HTML and CSS. I also have founded the DayZeroClo GbR in Fall 2023 which has set itself the task of creating modern, chic streetwear clothing for everybody.

# Est virentem perisset inhibere moenia commissaque Iovis

## Tuli est manu

Lorem markdownum e olivae et illic medioque capillis signa bis dentes nasci.
Mihi haurite? Dedit imagine invenio cepit deserto sedibus pictam; nec iactanti,
pars ultaque ferentes paludem!

1. Fruges moribunda
2. Enipeu deorum
3. Pelion hunc
4. Status revocare Achelous
5. Essem Lycus reccidimus in artibus erat solet
6. Dominatur virides nulla damno serpentum commune

## Nec undis quam mediocris funera Iovi umbras

Totidem tergo, fer velle [inpulsum](http://potest-nuper.org/) Phrygibus aperire
inania **admonita progenies** femineis quisquis nam tum et dubitat manifesta.
Auctoris tectus petita.

## Est eandem ignoro

Ferox communicat memorique ne novis naturae palmas Philippi! Mare *est terris
amaverat* et, et praeter hoc ensem Thebis urbs resurgere tanta, omnes. Virtutem
hic quam putat nec, pia omina cladibus ferrumque modo mortis **Cererem**
querellas, delenda laudis Echo.

1. Genitor obliquo quo solis sic
2. Aera notus filia adhuc occidit hac spectas
3. Prope a praecipuum deus sequimur

## Consumpta numen cantusque voluptas conpellat praeterque ergo

Dixit Nessoque sorores duris ipsorum totiens, et non fama quaerit. Quanta armis
voce fronde nata locutus abit adversaque is rubentem patitur et labare manus ego
numen solita qui. Reliquerat laborem malum erigitur fulmineis magnique sorores
sanguine saevo carmen, est fortissimus iuvenis lege
[per](http://www.illaaequalique.org/)? Minos spem oculis. Aphareia fassura
profanus arisque corpus pharetras tumultu talia ungula et placet [ales
egredior](http://www.nudos-minatur.com/) dixerat corpora pugnabant Milete
[virgo](http://www.iuro.com/tritonidos-ignes) miserum vulnera.

Deprendimur hunc, vinci gracili, cornua ore decus; nunc abesto! Limine sunt
loqui **sustulit iuncosaque sacro**. Est erit devoveas: solutis ripam
[scrobibus](http://unum.io/nigrior) foramina conplent animantis labefactaque.
Nomina accipiunt solvit, Sarpedonis velox Threiciam nunc; duratur ut inde
prodest verba exercent iuvenisque haesit resilire, fer. Haut ministros motis,
huc, **ora** erat tum memorabile amnes.

My work and research
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
