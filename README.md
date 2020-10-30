# The Spread of Economic Crisis in an Interconnected Financial Network

The goal of this project was to implement a specific compartmental model, the SIR (Susceptible- Infected-Recovered), on a network to better understand systemic risk and the spread of debt default. We leveraged bilateral foreign claims data of 23 countries from the Bank of International Settlements as well as credit ratings as two measures of systemic risk to model default spreading from one national banking system to another. Our aim was to identify factors that influence the speed and spread of a financial crisis by simulating default cascades originating from each of the 23 countries, and spreading through the edges.


We approached the problem in the following steps:
1) built the network,

2) defined the transmission rate (𝛽, based on foreign claims) and recovery rate (𝛾, based on
credit rating),

3) ran simulations with each nation as the originator of default to compare the evolution of the
resulting financial crises, and

4) drew conclusions about policy initiatives to limit the spread of crises.
