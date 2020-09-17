# Aggregation-App
Improved on the code written during my PhD and made a simple interface to produce aggregate distribution plots.

- - -
This is one of the models produced during my PhD on Sonic Hedgehog (Shh). Shh is a protein that coordinates tissue growth and patterning in a wide variety of species. It is fundamentally important during early embryonic development as, in Shh mutants (Shh gene inactivated), offspring do not survive after birth (Chiang_1996). Shh functions by activating responses in cells that receive Shh signals. Often, Shh will travel to a cell from another, sometimes requiring long-range travelling (300 micromemters/30 cell diameters). The pattern by which Shh travels to cells over an area is often referred to its signalling gradient.
- - -
If the pattern by which Shh travels is abnormal it can lead to developmental abnormalities. In instances where Shh is able to extend its usual pattern during the formation of the limb bud, it has been found that additional digits may form (Li_2006). For this reason, it is very important that Shh travels effectively and accurately.

Unusually however, Shh is hydrophobic. It will not travel effectively between the aqueous extracellular mileu. How it therefore does, and with considerable efficiency, is yet to be fully understood. Recently, we have come to understand that Shh may form multimers (clump together to form clusters), and that it can associate with circulating lipoproteins (insert hydrophobic adducts into the surface), and it is known to associate with heparan sulfate proteoglycans (HSPGS)  ( these are cell surface particles that act as structures to "collect" Shh in clusters). 
- - -
In this work we modelled how Shh is likely to form aggregates with these mechanisms. Shh enters the model as single proteins (monomers) and is able to; 1: bind with itself or other multimers to form greater sizes multimers; 2: bind with lipoproteins that may or may not be previously bound by other Shh monomers. HSPGs are able to recruit multimers, but are limited to the size they can bind with (this can be changed). Monomers do not associate with HSPGs, as was indicated by Vyas et al. (Vyas_2008).
- - -
