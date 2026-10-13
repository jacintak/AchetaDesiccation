# README

This projects consists of four experiments measuring various physiological traits of *Acheta domesticus* (In no particular order):

* Guts and Gonads: Measuring tissue-specific water content
* Haemolymph volume: Measuring haemolymph volume using FITC-Dextran dilutions
* Ions: Measuring haemolymph potassium and sodium ion concentration using ion selective microelectrodes
* Tissue water content: Measuring combined tissue water content and macromolecular composition (protein, lipid, glycogen (carbohydrate)).

Each folder contains raw data (xlsx or csv), and R code and HTML output of the analysis.  
The R code includes data cleaning, calculating of variables, and data visualisation. Note not all analyses are reported for publication.

Water_loss.qmd is the analysis of mass loss and water loss of all individuals collated across experiments. 

## Key variables
Variable names are kept consistent as much as possible across experiment. Cricket whole body or tissue mass was weighed either in a "container" or "beadmill" tube.

* Start mass: Initial mass of cricket (mg).
* End mass: Post-desiccation mass of cricket (mg).
* Rehydration mass: Post-recovery mass of cricket (mg).
* Time: Desiccation time of cricket - 0, 3, 6, 18.
* Time_treatment: Desiccation group of cricket - 0, 3, 6, 18, 24_starved, 24_fed. 24 h crickets are the two recovery groups with 18 h of desiccation and 6 h of recovery with or without food.
* Sex: Sex of cricket.
* Cricket_ID: Unique identifier of the cricket within the experimental cohort.
* Experiment: Name of experimental cohort.
* Dry mass: Oven dried whole body or tissue mass (mg) of the cricket.
* Percent_change: Change (loss) of wet mass during desiccation (%).
* Total_water_content: Amount of water in whole body expressed as weight difference between starting wet mass and dried whole body mass (mg).
* Relative_water_loss: Change (loss) of water mass during desiccation (%).
