# A small repository for LaTeX templates

The .tex files in this repository are simple templates you can download or clone locally. Nothing complex here, but
sometimes having a ready-to-go preamble is nice. If you are using new packages you made need to adjust the preamble. Finally, 
the Beamer template is specific to Texas A&M Universtiy [colors](https://brandguide.tamu.edu/web/web-color-palette.html). If you
are from a different organization that hates maroon ([ahem](https://www.utexas.edu/)), find the following lines of code:
```markdown
    \definecolor{TAMmarron}{HTML}{500000}
    \definecolor{TAMtan}{HTML}{D6D3C4}
```
And change `{TAMmarron}` (spelling is obvi not my strength) to `{your_org_name}` and `{500000}` to the HEX number of the color you desire. Similar process for the secondary tan color.