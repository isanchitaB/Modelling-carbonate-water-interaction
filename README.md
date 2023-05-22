# Modelling-carbonate-water-interaction

This chunk of code can help in loading the required packages and computing the post depositional water-rock interaction of carbonates based on the endmember composition.
It will first select a hypothetical range of depositional temperature and d18O of carbonate based on the measured clumped isotope-based temperature andisotopic composition.
Later a function is applied to calculate the amount of interaction using the above mentioned parameters with dolomite fractionation equation by Muller et al. (2019) with assigned end member composition. This dependent parameter is used for constructing contour lines and fill tiles. 
Lastly, the measured data is plotted on top of the contoured base plot for estimation of interaction.
