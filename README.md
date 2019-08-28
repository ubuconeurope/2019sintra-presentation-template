# 2019sintra-presentation-template
Repository for Ubucon Europe 2019 presentation template related files

Live preview: https://tcarreira.github.io/ubucon-europe-2019/presentation-templates/remark/#1

## Presentation slides
Check the templates for the presentations.

Formats available (order of preference):
1. Markdown/HTML (with [remark](https://remarkjs.com)) |  **prefered** dependency: browser<br>
1. ODP (Open Document Presentation) | dependency: LibreOffice / OpenOffice
1. Google Slides ([presentation link](https://docs.google.com/presentation/d/1CMGgc3AYt62IExihr3l_ksS9GEZyWUnoJIVHZeGeZhA/edit?usp=sharing)) | dependency: browser
1. PPTX (MS Powerpoint Presentation) | dependency: Windows + MS Office (PowerPoint)
1. KEY (Keynote) | dependency: MacOS + Keynote 
1. LaTeX

See below the usage instructions for each format, or the color schemes and instructions to build the ubucon theme (wip).


## Usage Instructions

### Markdown/HTML (remark) **prefered**

**requirements:** browser

1. Copy the source from `presentation-templates/remark`. 
1. Just open the `index.html` and edit the presentation slides inside the `<textarea id="source">` ... `</textarea>`
1. This is just markdown syntax with some css. Pretty easy.
1. Images should go to `img/some_image.jpg` folder and referenced in the presentation as `<img src="img/some_image.jpg" width="200">`. Recommended formats are `.jpg`, `.png` and `.svg`, but you could use [other formats](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Img#Supported_image_formats)  
1. The template should provide enough examples for most use cases. If you want to explore more funcionality, head to https://remarkjs.com, or ask for help in the speakers channel.

* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides.
  * Just copy and replace the `style.css` file and the `img/template/` dir.

### ODP (Open Document Presentation)

**requirements:** libreoffice | openoffice (or other presentation sofware that can read ODP)

* Open the template file, and edit from there.
* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides.

### Google Slides 

**requirements:** browser

**presentation link:** https://docs.google.com/presentation/d/1CMGgc3AYt62IExihr3l_ksS9GEZyWUnoJIVHZeGeZhA/edit?usp=sharing

### PPTX (MS Powerpoint Presentation) 

**requirements:** Windows + MS Office (PowerPoint)

* Open the template file, and edit from there.
* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides.

### KEY (Keynote) 
**requirements:** MacOS + Keynote 

* Open the template file, and edit from there.
* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides:
  * open the `ubucon.europe.2019-keynote.theme.kth`
  * choose "Add to Theme Chooser"
  * then open your presentation
  * go to File > Change Theme
  * validate all slides

### LaTeX
**requirements:** LaTeX compiler

## Ubucon theme

This ubucon theme follows the [Ubuntu Brand Guidelines](https://design.ubuntu.com/). Here are some theme specific guidelines.

### Fonts
Download them here (Resources): https://design.ubuntu.com/font/ 

* **Ubuntu Condensed**: 2nd+ order subtitles
* **Ubuntu Mono**: code
* **Ubuntu**: Title, Body, everything else

### Colors 
https://design.ubuntu.com/brand/colour-palette/

* Title: ![#E95420](https://placehold.it/15/E95420/000000?text=+) `#E95420`
* 2nd sub-title: ![#ED764D](https://placehold.it/15/ED764D/000000?text=+) `#ED764D`
* 3rd sub-title: ![#AEA79F](https://placehold.it/15/AEA79F/000000?text=+) `#AEA79F`
* Body: ![#000000](https://placehold.it/15/000000/000000?text=+) `#000000`
* Slide number: ![#FBDDD2](https://placehold.it/15/FBDDD2/000000?text=+) `#FBDDD2`
* Code background: ![#E2E0DD](https://placehold.it/15/E2E0DD/000000?text=+) `#E2E0DD`
* Code text: ![#111111](https://placehold.it/15/111111/000000?text=+) `#111111`
* Highlighted code backgroung: ![#6B4C61](https://placehold.it/15/6B4C61/000000?text=+) `#6B4C61`
* Highlighted code text: ![#EAE9E7](https://placehold.it/15/EAE9E7/000000?text=+) `#EAE9E7`
* Impact/Quote slide background: ![#5E2750](https://placehold.it/15/5E2750/000000?text=+) `#5E2750`
* Impact/Quote slide text: ![#EEEEEE](https://placehold.it/15/EEEEEE/000000?text=+) `#EEEEEE`
