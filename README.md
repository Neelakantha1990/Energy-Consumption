# Energy-Consumption

Background   and   Introduction:   -

Analysis of heating load and cooling load is paramount to check the energy consumption of a building. We attempt to determine and establish relationship between the heating and cooling load and the building parameters. We use 12 different building shapes simulation in Ecotect (a feature of Autodesk). Most importantly, the buildings differ with respect to the glazing area distribution, and the orientation, amongst other parameters. We will simulate various settings as functions of the aforementioned characteristics to obtain 768 building   shapes.
Origin   of   Data: -

The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer. The data set was created in November 2012 and to proceed with this we would prefer to use Machine Learning methods to perform the analysis.   Our   main   aim   was   to   select   an   industrial   machine   analysis   data.
Problems:   -
● Assessing   heating   load   and   cooling   load   requirements   of   buildings   (i.e.   energy
efficiency)   as   a   function   of   building   parameters.
● Studying   the   effect   of   eight   input   variables   (relative   compactness,   surface   area,   wall
area,   roof   area,   overall   height,   orientation,   glazing   area,   glazing   area   distribution)   on two   output   variables,   namely   heating   load   (HL)   and   cooling   load   (CL),   of   residential buildings.
● Identifying   the   most   strongly   related   input   variables.
● Comparing   a   classical   linear   regression   approach   against   a   powerful   state   of   the   art
nonlinear   nonparametric   method.
● Predict   HL   and   CL   with   low   mean   absolute   error   deviations   from   the   ground   truth.
● Results   of   this   study   support   the   feasibility   of   using   machine   learning   tools   to
estimate   building   parameters   as   a   convenient   and   accurate   approach.
Goals   of   the   study:-
● For efficiency, heating load (HL) and the cooling load (CL) is required to determine
the   specifications   of   the   heating   and   cooling   equipment.
● Develop        a   model   to   conserve   energy   .
● Develop   an   efficient   energy   system

# Steps Followed

★Evaluated relationship between 768 different building shapes considering 8 parameters by visualizing using linear plot, correlation plot and heat maps
★Enacted model validation, developed diagnostic tables and graphs to exhibit how model can be used to improve the efficiency of the selection process
★Implemented Principal Component Analysis and Linear Discriminant Analysis to reduce 8 independent variables to 2, effectively analyze in predicting dependent variable 
★Developed 91% energy efficient model to conserve energy by adopting Logistic Regression on training set 
