# Phylogenetic Biology - Final Project

## Guidelines - you can delete this section before submission

This repository is a stub for your final project. Fork it, develop your project, and submit it as a pull request. Edit/ delete the text in this readme as needed.

Some guidelines and tips:

- Use the stubs below to write up your final project. Alternatively, if you would like the writeup to be an executable document (with [knitr](http://yihui.name/knitr/), [jupytr](http://jupyter.org/), or other tools), you can create it as a separate file and put a link to it here in the readme.

- For information on formatting text files with markdown, see https://guides.github.com/features/mastering-markdown/ . You can use markdown to include images in this document by linking to files in the repository, eg `![GitHub Logo](/images/logo.png)`.

- The project must be entirely reproducible. In addition to the results, the repository must include all the data (or links to data) and code needed to reproduce the results.

- If you are working with unpublished data that you would prefer not to publicly share at this time, please contact me to discuss options. In most cases, the data can be anonymized in a way that putting them in a public repo does not compromise your other goals.

- Paste references (including urls) into the reference section, and cite them with the general format (Smith at al. 2003).

- Commit and push often as you work.

OK, here we go.

# Potential of Litter Size as a Predictor of Menstruation in Rodentia 

### Gladys Fang (since my github name is unrelated) 
## Introduction and Goals

  Menstruation is the periodic shedding of endometrium decidua in the absence of pregnancy. The endometrium goes through a complex process of decidualization triggered by sequential hormone fluctuations to prepare for pregnancy. However, in most mammals, decidualization is triggered by embryonic signals, and the decidua is reabsorbed in the case of pseudopregnancy. Among the 5000+ eutherian mammals, only a small number of species have been shown to have menstruation. These include most primates, three species of bats, the spiny mouse and the elephant shrew (Catalini and Fedder 2020). 
  
  Upon closer inspection, some species might have evolved spontaneous decidualization and menstruation independently as suggested by their dispersed distribution on the phylogenetic tree. The fact that menstruation is not necessary for reproduction (most species don’t have it), yet it has evolved multiple times prompts us to investigate the evolutionary significance of spontaneous decidualization and menstruation (Wagner 2020). 
  
  Multiple hypotheses have been proposed. One argues that spontaneous decidualization allows the female to test the quality of the embryo, which helps the mother to avoid unnecessary investment into defective conceptus and achieves successful pregnancy sooner (Macklon and Brosens 2014). This idea is supported by the fact that known menstruating species all have litter sizes of one or two, with the exception of the spiny mouse (Bellofiore, Ellery et al. 2017, Catalini and Fedder 2020). Smaller litter size might correspond to higher investment into each offspring, and thus the demand for early screening of conceptus quality.  
  
  Here I hypothesize that small litter size might be predictive of spontaneous decidualization and menstruation. In order to test the hypothesis, I will conduct a thorough literature search, use existing databases and compile a dataset of rodent litter size. The aim is to map litter size over the phylogeny of rodents, observe litter size patterns, and find rodent species of small litter size (less than two), as it might give us hints to undiscovered menstruating rodent species.
  
Tentative Method:
  1. I will collect average litter size data from PanTheria life history database (Jones, Bielby et al. 2009) and extensive literature searches. The expected dataset will comprise about 1000 species out of 2200 in Rodentia. I will exclude the speicies with incomplete data and make a character state matrix. 
  2. Since Jetz lab provides a very credible and relatively complete Mammal tree, I will start by download a Rodentia tree from VertLife.org (Upham, Esselstyn et al. 2019). Ideally this tree comprises of all the species that I have data for from step 1, but if not I will adjust local topology /add/ minus certain species by inferring the tree myself. This will require inferring certain clade using DNA data from NCBI taxonomy database, align the DNA sequences for genes and using iqtree to construct the clade. Then I will compare this clade with the tree from VertLife.org and make adjustments. 
  3. Map character state for each species onto the tree, and infer ancestral state / sister states. (I don't know the specifics of comparative methods yet, but I will learn about ancestral state reconstruction in Week 10 and comparative methods in Week 11. Before that, I will focus on collecting the data and acquiring a satisfying tree) 
  4. Visual presentation, make adjustment to the tree presentation, highlight species/clades of interests, write up discussion and conclusions. 

## Methods

The tools I used were... See analysis files at (links to analysis files).

## Results

The tree in Figure 1...

## Discussion

These results indicate...

The biggest difficulty in implementing these analyses was...

If I did these analyses again, I would...

## References

Bellofiore, N., et al. (2017). "First evidence of a menstruating rodent: the spiny mouse (Acomys cahirinus)." American Journal of Obstetrics and Gynecology 216(1): 40. e41-40. e11.
	
Catalini, L. and J. Fedder (2020). "Characteristics of the endometrium in menstruating species: lessons learned from the animal kingdom." Biology of Reproduction 102(6): 1160-1169.
	
Jones, K. E., et al. (2009). "PanTHERIA: a species‐level database of life history, ecology, and geography of extant and recently extinct mammals: Ecological Archives E090‐184." Ecology 90(9): 2648-2648.
	
Macklon, N. S. and J. J. Brosens (2014). "The human endometrium as a sensor of embryo quality." Biology of Reproduction 91(4): 98, 91-98.

Upham, N. S., J. A. Esselstyn, and W. Jetz. (2019). Inferring the mammal tree: species-level sets of phylogenies for questions in ecology, evolution, and conservation. PLOS Biology. https://doi.org/10.1371/journal.pbio.3000494

Wagner, G (2020). “The Evolutionary History of Menstruation.” American Journal of Obstetrics and Gynecology (in press).



