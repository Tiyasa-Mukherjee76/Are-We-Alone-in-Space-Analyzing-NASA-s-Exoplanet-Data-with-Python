# Are-We-Alone-in-Space-Analyzing-NASA-s-Exoplanet-Data-with-Python
In this project, we’ll explore relationships in real scientific data from NASA’s Exoplanet Archive.  Our goal is to practice exploratory data analysis (EDA): visualizing data, computing basic metrics, and interpreting patterns carefully.
Goals
1. Load the Data

2. Practice Pure Python Skills

3. Plot Relationships

4. Compute Descriptive Statistics

Questions
These are some of the questions we will tackle:

1. Planet Size vs. Planet Mass
Common sense would suggest that larger planets also have more mass, but this might not be the case for gas planets. We will explore this relationship.

2. Discovery Year vs. Planet Size
Sometimes relationships between 2 variables are more complex. There appears to be a correlation between discovery year and planets size (as better instruments might enable the discovery of smaller planets). We will analyze whether this is true.

3. Discovery Methods
Different discovery methods have been used over the years. We will assess which one of them has found the most planets.

Column descriptions
Below are the columns we use in the notebook and what they represent.

pl_name: Planet name (string)
pl_rade: Planet radius in Earth radii (float)
pl_bmasse: Planet mass in Earth masses (float)
discoverymethod: Discovery method (categorical — e.g., Transit, Radial Velocity)
hostname: Host star name (string)
disc_year: Discovery year (datetime)
