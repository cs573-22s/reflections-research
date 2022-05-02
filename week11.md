([Source](https://www.hindawi.com/journals/cin/2011/879716/))

# Brainstorm: A user-friendly application for MEG/EEG analysis
# Francois Tadel, Sylvain Baillet, John Mosher, Dimitrios Pantazis, Richard Leahy

## Summary
Brainstorm is a visual interface for data exploration of neuroimaging data, specifically MEG, EEG, and fMRI. The UI and desired visualizations were chosen first _and then_ underlying functions to generate that type of analysis or data processing were connected. This is a new order of methodology for designing data visualization platforms, as most tools will first create functions that produce a certain type of data, then choose the best method to visualize that data. Brainstorm is also interactive; many of the visualizations it produces can be maneuvered and adjusted depending on what the user is interested in exploring. 

## Take aways
While a common principal is to generate data first then choose the best way to analyze it, this may not expose visualizations that are valuable but don't fit within the data's structure. By thinking of what visualizations were most important to researchers, the creators of Brainstorm could prioritize how the user views the data instead of the functions that create the data. This provides a new way for researchers to approach their data analysis but should be paired with more traditional methods to validate that nothing important is missed or skipped in the visualization pipeline (i.e. does the output of the raw data match that of traditional analytical methods or are the underlying functions not performing as well as standard due to not being prioritize in development.)