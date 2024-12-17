Contained within this folder is the SpectroFloParser.qmd file. A rendered html version can be found on Quarto-Pub at the [following link](https://stepupcytometry.quarto.pub/spectrofloparser/). You will need to provide your own SpectroFlo.EXPT file from your local instrument.

Run the code-blocks to locally create the functions that you will need to retrieve the signatures contained within the SpectroFlo .EXPT file. Then process your experiment file to retrieve the data. 

I have added a ggplot2/plotly example as an example for visualization. Note that the "fluorophore signature" generated by the gate placements for this particular experiment vary quite wildly from what they should be. Gentle reminder proper unmixing controls and gate setting are needed for good results :D