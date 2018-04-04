# Project Introduction to Big Data (SE and ISCE groups).
THIS PROJECT DESCRIPTION CONCERNS ONLY THE FOLLOWING GROUPS:

* BI1 (P.Marini)
* ISCE (D. Lebedev)
* SE (D.Lebedev)
OTHER GROUPS GET SEPARATE INSTRUCTIONS

# Helping to evaluate vacation renting sites
Short description: This project is concentrated on the evaluating renting advertisements by studying the electricity consumption in towns where the property is advertised. In the context of users choosing different destinations for vacations, provide them an additional information on those places in terms of environmental conditions. The environmental condition in our limited example is based on the electrical consumption in the destination town.

Further details: In France, several house rental web sites have RSS XML flow that can be parsed into a data set containing the list of available rentals. You will find the names of the towns inside the text.

At the same time you have the CSV file from ENEDIS (https://data.enedis.fr/explore/dataset/consommation-electrique-par-secteur-dactivite-commune/) containing the history of electricity consumption allowing you to estimation how much and for which purpose the energy is consumed. Thus you can provide every community with the “electrical” description, where you will calculate different indicators, such as for example, 
* part/amount of non-resident consumption, which might indicate the importance of the industrial installations in the town.
* evolution of the residencial consumption for several years, which might indicate the growth factor of the town
* evolution of the non-residential consumption
* other indicators left to you

Putting both data sources together allows you to sort/filter the rental advertisements by the “energy” indicators, as, for example, “zero industry” advertisements - quiet locations. To find an exact usage is left to you as a part of the exercise.

# Deliverables

Jupyter Python notebook with the code (or a Python code).
Graphs and numbers presenting different ‘energy indicators’ and the towns we find in the ads (can be inside the notebook or in PPTX).
Final use cases, presenting how your work helps to choose a “nice” vacation rent.
# Hints on structuring your project : your project will probably include

Put on paper some ideas what you will be doing
Get the data (verify with the professor its relevancy during the practical work sessions)
Check that your ideas can be implemented with the data available
Parse and structure your data
Connect the data sets
Calculate the indicators and plot them to present their values
loop through the steps
You will be graded on the basis of the following axis

Variety of the data sources used (you are free to expand your data sources to other datasets).
Usage of the tecnhiques presented during the practical work and their difficulty level.
Usage of Python functionalities not seen during the practical works (e.g. plots/bokeh).
The topic is artificial, but business logic is important, so the interest of the indicators you show will also be taken into account.
