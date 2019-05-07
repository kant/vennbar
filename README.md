[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/raynamharris/vennbar/master?urlpath=rstudio)
Click the button to launch a Binder R session and tinker with all the
bar plots or explore the code in the cloud. Navigate to the `examples`
directory where there is a subdirectory for each of the four examples,
all identified by the first or last author.

![](./vennbar-1.png)

![](./vennbar2-1.png)

[Venn diagrams](https://en.wikipedia.org/wiki/Venn_diagram) are a type
of figure that I see a lot in the literature. While Venn diagrams are a
great way to *conceptualize* the goal of looking for shared or unique
transcriptional responses to experimental manipulations, I don’t think
they are the best way to *vizualize empirical data*.

Here, I compare four Venn diagrams from published research articles to
four bar plots that I made with `tidyverse` and `cowplot`. I think these
bar plots can be made more simplicity, flexibility, reliability, and
reproducibility than a Venn diagram. These Venn diagrams all come from
labs that I admire and respect. I really value their research
contributions, but I do hope to see more alternatives for Venn diagrams
in future publications.

![](./examples/toth2017/toth-original-alt-1.png)

**Example 1** is inspired by “Cognitive specialization for learning
faces is associated with shifts in the brain transcriptome of a social
wasp”" by [Berens *et al*.
2017](http://jeb.biologists.org/content/220/12/2149).

-   [Source .Rmd code](./examples/toth2017/toth-venn.Rmd)
-   [Markdown output](./examples/toth2017/toth-venn.md)

![](./examples/geffre2017/geffre-original-alt-1.png)

**Example 2** is from “Transcriptomics of an extended phenotype:
parasite manipulation of wasp social behaviour shifts expression of
caste-related genes”" by [Geffre *et
al*](https://royalsocietypublishing.org/doi/full/10.1098/rspb.2017.0029?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%3dpubmed).

-   [Source .Rmd code](./examples/geffre2017/geffre-venn.Rmd)
-   [Markdown output](./examples/geffre2017/geffre-venn.md)

![](./examples/calisi2017/calisi-original-alt-1.png)

**Example 3** is from “Sex-biased transcriptomic response of the
reproductive axis to stress”" by [Calisi *et al*
2017](https://www.sciencedirect.com/science/article/pii/S0018506X17302696?via%3Dihub).

-   [Source .Rmd code](./examples/geffre2017/calisi-venn.Rmd)
-   [Markdown output](./examples/calisi2017/calisi-venn.md)

![](./examples/pena2019/pena-original-alt-1.png)

**Example 4** is from “Early life stress alters transcriptomic
patterning across reward circuitry in male and female mice”" by [Peña
*et al.* 2017](https://www.biorxiv.org/content/10.1101/624353v1).

-   [Source .Rmd code](./examples/pena2017/pena-venn.Rmd)
-   [Markdown output](./examples/pena2017/pena-venn.md)

So, that’s my comparison of four Venn diagrams and four possible bar
plot alternatives. What do you think? Do you see the advantages? What
other alternatives do you suggest? Comments welcome!
