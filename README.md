This is a project about Transparency in Public Procurement. We used the KNIME workflow. Our team found a dataset about TED Contract Award Notices 2017 – 2021. 
We begin with importing the raw dataset “TED Contract Award Notices 2017 – 2021”. The first thing we wanted to do, was to clean our data by removing N/A values and change the data type from ‘number’ to ‘string’. In the main dataset, we noticed that the ‘Industry’ column was being presented by certain codes. Our next step was to import an external dataset which was actually explaining what the code of the main dataset was referring to. The values ‘91’ and ‘93’ were missing, so we manually added them to the latter table and then merged it with the data-cleaned TED dataset.

Market Analysis Field
For the first part of the project, which has been to prepare a market analysis for the European area, we used techniques including filtering and various designs including tables and charts to visualize the data.

Transparency Application Field
The entire idea about the Transparency Application was to use 3 pivots, which would help us numericize the transparency per country.

The first pivot is about Single Bidders. Here, we are trying to browse our data in order to find how many awards were given to 1 single enterprise by country. Focusing on the biggest amount of awards given to an enterprise, we extract the actual percentage of the total awards given to this specific country. Then we reverse this percentage so that we can have an idea about the ‘amount’ of transparency of each country, according to the first pivot.

The second pivot is about percentage of no calls for bids, which filtered the data and extracted only the award without prior publication of a contract notice (AWP) and negotiated without a call for competition (NOC/NOP).

The third pivot is about awards given to SME Contractors. We are interested in seeing how many awards were given to actual small-medium sized enterprises. Once again, we take this number and comparing it to the total amount of awards given, we extract another percentage. A big amount of Percent of SME Contractors is a good indication for the country’s transparency.

After finishing with these 3 pivots, we merge them together in our table. The next step is to find an average score per country, using all the information that we manage to extract in the last 3 steps. We use our 3 pivot results to find the average ‘Score’ for the transparency of each country.

Then we import 2 external excel files. First one is the Corruption Perceptions Index and then the Standard and Poor’s (S&P) Sovereign Risk Indicators. The main idea was to compare our results for transparency, to the official ratings.
Later we provide some graphs using Power BI and several statistics as our conclusions. 
