## Misc
### first frame of gif:
`convert animation.gif target.png`
```
for num in (seq 4); convert  bair_action_free_$num.gif -coalesce -chop 256x0+65+0 -delay 80  vid_pred_$num.gif; end; and xdg-open vid_pred_$num.gif;
for num in (seq 4); convert  vid_pred_$num.gif[0] vid_pred_$num.png; end

#reset
rm main.{fls,out,nav,log,fdb_latexmk,aux,toc,snm,sta}
```


# stanford_beamer_presentation
This is an unofficial LaTeX Beamer presentation template with Stanford University theme.

Feel free to use this template for your project presentations, conference talks, etc.

The repository includes [a simple example file](./example_slides.pdf) (with the [`.tex`](./example_slides.tex) source code) and [a full, example presentation slides](full_talk.pdf) of my own (no `.tex` source code provided).

## Example Slides

![Example Slide 1](example_slides_img/example_slides-1.jpg "Example Slide 1")
![Example Slide 2](example_slides_img/example_slides-2.jpg "Example Slide 2")
![Example Slide 3](example_slides_img/example_slides-3.jpg "Example Slide 3")
![Example Slide 4](example_slides_img/example_slides-4.jpg "Example Slide 4")

# TODO
<!-- - conclusion slide for each aim -->
- experiment diagram
- horizontal video ?
- check each title to make sure a statement
- Print out slides!

- read https://www.sciencedirect.com/science/article/pii/S0896627305004666
- tie in mauthner circuit more centrally
- schematic for experiment design
- clear statements of where I am (in presentation...)
