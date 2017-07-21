---
layout: page
title: riboxswitch
tagline: The Oxford Biomod Team Wiki
description: Keep up with the team's progress as we develop our co-operative riboswitches!
---

Give me a chance and I'll bring you our real website! 

Sam's text (this could really use a bit more fun...): 
Synthetic biology promises the rational redesign of biological processes by controlling gene expression for applications throughout the pharmaceutical, brewing, and medical industries. This has largely been achieved through synthetic biology by repurposing natural mechanisms affecting translation, such as transcription factors and promoter sequences. However, these systems are not trivial to design and cannot be retargeted to arbitrary DNA sequences limiting their potential to be easily configured for new functions. 

RNA switches have great potential for the design of synthetic genetic circuits. In comparison with protein-based transcriptional regulation, it may be more simple to design RNA switches through the relative simplicity of nucleotide interactions, which could have less stochasticity due to the larger pool of cytoplasmic RNA compared with smaller pool of transcription factors, and may have better kinetics due to the relatively fast turnover of RNA.

However, designs for synthetic riboswitches lack the inherent cooperativity of some protein-based regulators and natural riboswitches, leading to a broad dose-response rather than a ‘switch-like’ response to changes in concentration. 

We aim to design cooperative riboswitches permitting rational control of gene expression.

We take inspiration from the design of DNA aptamers and DNA molecular beacons, where it has been demonstrated that doubling the number of ‘receptor’ sites within a DNA switch increased cooperativity. By applying the same principle to an RNA hairpin within an mRNA transcript, we could selectively open and close the switch to reveal or hide a ribosome-binding site (RBS) and thus control protein translation. Importantly, the rate of translation from this RBS will be regulated cooperatively by the concentration of a ‘trigger’ RNA strand. This RNA strand, given that its sequence is not greatly constricted, could be an aptamer with specificity for the output of the system allowing the expression of a gene be related to the concentration of the product or another molecule.

In this project we intend to design and test a cooperative riboswitch, first demonstrating the unfolding of the RNA hairpin in vitro using PAGE and FRET. We then intend to show the same cooperative behaviour in vivo in a variety of constructs using E. coli cells and the expression of a fluorescent reporter as a model system. Future work would be to incorporate the cooperative riboswitch into more advanced genetic circuits such as positive and negative feedback systems. 

[Lab work] 
Sam, you'll have to give me a little time to work out how to add images in MarkDown. Please don't modify the repository again! It took me hours to merge the damn thing!

<iframe width="560" height="315" src="https://www.youtube.com/embed/Jea6CCv23nQ" frameborder="0" allowfullscreen></iframe>

<div class="x-frame video" data-video="http://player.vimeo.com/video/52302939"> </div>

[Github Pages](https://pages.github.com) provide a simple way to make a
website using
[Markdown](https://daringfireball.net/projects/markdown/) and
[git](https://git-scm.com).

For me, the painful aspects of making a website are

- Working with html and css
- Finding a hosting site
- Transferring stuff to the hosting site

With [GitHub Pages](https://pages.github.com), you just write things in
[Markdown](https://daringfireball.net/projects/markdown/),
[GitHub](https://github.com) hosts the site for you, and you just push
material to your GitHub repository with `git add`, `git commit`, and
`git push`.

If you love [git](https://git-scm.com/) and
[GitHub](https://github.com), you'll love
[GitHub Pages](https://pages.github.com), too.

The sites use [Jekyll](https://jekyllrb.com/), a
[ruby](https://www.ruby-lang.org/en/) [gem](https://rubygems.org/), to
convert Markdown files to html, and this part is done
automatically when you push the materials to the `gh-pages` branch
of a GitHub repository.

The [GitHub](https://pages.github.com) and
[Jekyll](https://jekyllrb.com) documentation is great, but I thought it
would be useful to have a minimal tutorial, for those who just want to
get going immediately with a simple site. To some readers, what GitHub
has might be simpler and more direct.  But if you just want to create
a site like the one you're looking at now, read on.

Start by reading the [Overview page](pages/overview.html), which
explains the basic structure of these sites. Then read
[how to make an independent website](pages/independent_site.html). Then
read any of the other things, such as
[how to test your site locally](pages/local_test.html).

- [Overview](pages/overview.html)
- [Making an independent website](pages/independent_site.html)
- [Making a personal site](pages/user_site.html)
- [Making a site for a project](pages/project_site.html)
- [Making a jekyll-free site](pages/nojekyll.html)
- [Testing your site locally](pages/local_test.html)
- [Resources](pages/resources.html)

If anything here is confusing (or _wrong_!), or if I've missed
important details, please
[submit an issue](https://github.com/kbroman/simple_site/issues), or (even
better) fork [the GitHub repository for this website](https://github.com/kbroman/simple_site),
make modifications, and submit a pull request.

---

The source for this minimal tutorial is [on github](https://github.com/kbroman/simple_site).

Also see my [tutorials](http://kbroman.org/pages/tutorials) on
[git/github](http://kbroman.org/github_tutorial),
[GNU make](http://kbroman.org/minimal_make),
[knitr](http://kbroman.org/knitr_knutshell),
[R packages](http://kbroman.org/pkg_primer),
[data organization](http://kbroman.org/dataorg),
and [reproducible research](http://kbroman.org/steps2rr).
