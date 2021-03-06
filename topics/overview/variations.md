---
layout: article
breadcrumbs: ["Overview", "With variables…"]
sidebar: "Enhancing typographic experience"
title: "Enhancing typographic experience"
---

## The SFNT does it again

To give a brief history of OpenType 1.8 with variable fonts: the 1989 <a href="https://en.wikipedia.org/wiki/SFNT">SFNT</a> font format Apple defined for TrueType allowed more than 256 characters per font style, and was able to rely on Unicode. This led to the ability to make font styles including Apple’s system user-interface fonts, containing the many scripts required for the growing linguistic breadth of Apple’s personal-computer market.

And that, in turn, led to easily imagining “international font families,” sometimes of six to ten styles, containing four to eleven thousand characters each, kerning, glyph substitution, hints, and more—becoming large files to move around and store. So before Apple TrueType 1.0 was even out the door, as part of the first commercial operating system that could ship all over the world (Mac OS 7), TrueType GX variations were under development to tame the file sizes of font families. 

In the process of experimenting with variations for font compression, Apple became interested in other uses, like multiple font families in a variable font, optical font sizes, animations, design experiments, and typographic effects. But during the period of 1992–96, there wasn’t enough computing power, screen resolution, audience size, or stability at Apple, and it was not the time for Microsoft or Adobe to adopt TrueType GX variations, or any of its parts.

## Sooner or later, something had to happen

Not until years later, after Microsoft had undertaken (and Adobe and Google were starting to undertake) international font-family development, did the thinking and conversation about what would become OpenType 1.8 begin, leading to the <a href="https://medium.com/variable-fonts/https-medium-com-tiro-introducing-opentype-variable-fonts-12ba6cd2369">2016 release</a> of a specification that included variable fonts. This initial pursuit of font-family file compression, besides having a new aspect relevant to performance of international font families on the web, rekindled interest in variations for extended, old, new, and different uses.

<figure style='margin-top:-0.666rem;'>
{% include specimen.html layout="compact" font="Amstelvar-Alpha" size="fit" text="AMSTELVAR ALPHA" link="https://github.com/TypeNetwork/Amstelvar" %}
{% include specimen.html layout="compact" font="Amstelvar-Alpha" size="fit" text="An Experimental 17-Axis Variable" link="https://github.com/TypeNetwork/Amstelvar" %}
  <figcaption><a href="https://github.com/TypeNetwork/Amstelvar">Amstelvar</a>, the first “extreme font challenge” Font Bureau worked on for Google.</figcaption>
</figure>

Font Bureau began public variable development in late 2016, when we started alpha designs of <a href="https://github.com/TypeNetwork/Amstelvar">Amstelvar</a> and <a href="https://github.com/TypeNetwork/Decovar">Decovar</a>  for Google, which, along with other companies, had done significant work on a variable-font generator. Microsoft and Apple had developed variable-font system extensions for their upcoming operating systems. Microsoft had also developed huge amounts of documentation and provided wise specification management. And Adobe had gone to work on what would become the PostScript extension for variable fonts in CFF2. WebKit rapidly updated to the spec, which Apple quickly put into a version of Safari.

<figure style='margin-top:-1.5rem;'>
{% include specimen.html layout="compact" font="Decovar" size="fit" text="DECOVAR ALPHA" TRMF="114" SKLD="100" BLDA="204" link="https://github.com/TypeNetwork/Decovar" %}
{% include specimen.html layout="compact" font="Decovar" size="fit" text="An Experimental 15-Axis Variable" link="https://github.com/TypeNetwork/Decovar" %}
  <figcaption>Font Bureau’s second project for Google: <a href="https://www.github.com/typenetwork/fb-decovar">Decovar</a>, a modular parametric display font.</figcaption>
</figure>

## Thinking (and designing) ahead

We at Font Bureau, when trying to demonstrate much of what was possible in our alpha designs, quickly realized, thanks both to our partners developing fonts and web content at Type Network and to our clients at Google, that there were still performance and/or presentation difficulties with variable fonts. A world with only one or two desktop browsers that could handle variations forced our site to fall back to large movie files, lots of font styles for not-yet-compliant browsers, and ultimately users being directed to variations-compatible browsers. 

We demonstrated what we could do then, and started thinking, designing, and planning forward to what is a now a world where all of the latest browsers support variable fonts. While this version of our demonstrations does not obviate the need on the part of web typographers to account for fallback to whatever presentation a web user chooses, now at least many aspects of variable fonts can be demonstrated to a much broader audience, most of whom are likely using browsers that lean forward to variable fonts.

With that in mind, this site takes the examples of each topic from what was possible, or impossible before OpenType 1.8, into what’s possible with variable fonts, among and beyond the registered axes, but having proper values where demonstrable for extended, old, new, and different uses. Along with that, of course, we’ll also demonstrate some variable-font compression issues, which, over time, and given the international font-family march of SFNT, has become more than one topic.
