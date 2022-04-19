# DCS-Futbol-Analysis 
## Final project for DCS 375 on France's Players in the 2018 World Cup Semi-Final and Final 

1. The scholarly question that you are exploring:

What players are central to the directed networks of the France-Croatia final and France-Belgium semi-final? What positions do they play? How are the number of passes allocated across players on each team? 

2. Sufficient background to make the significance of your question legible for non-expert readers:
Soccer background, motivation for question and why our question/hypotheses are significant

3, A discussion of methodology:

Filter for specific games, color code nodes using vectors for player positions, graph network objects on field
Calculate centrality and betweenness 
Calculate number of passes received and "given/sent" per player per team to construct pass distrubution histogram
Null model of power-law distribution, calculate p-value associated with fit of pass distribution histogram to preferential attachment

4. Code snippets:

Filtering code for specific games, code to color nodes by position played, code to overlay on soccer field, code for pass distribution histogram

5. References to at least four pieces of scholarly writing (these should include readings from the disciplinary or domain space that your question is in, as well as network theory readings from the course)

1. Football passing networks using R (https://www.datofutbol.cl/passing-networks-r/)
2. Using Network Science to Analyse Football Passing Networks: Dynamics, Space, Time, and the Multilayer Nature of the Game (https://www.frontiersin.org/articles/10.3389/fpsyg.2018.01900/full)
3. A network theory analysis of football strategies (https://arxiv.org/pdf/1206.6904.pdf)
4. Play-by-Play Network Analysis in Football (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6669815/)
5. Player position relationships with centrality in the passing network of world cup soccer teams: Win/loss match comparisons (https://reader.elsevier.com/reader/sd/pii/S0960077920300242?token=8E57B44BFF232C5A65695EB10963EC50F09AA44F926BA77E421EA97D4C50493E29D978F1D360149CC7A674D5CF2994E8&originRegion=us-east-1&originCreation=20220405191913)

6. Your data (original github repository and .csv files)

Original github repository (https://github.com/Dato-Futbol/passing-networks)
