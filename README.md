# International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach

Contents summary:
- [1-graph_construction](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/1-graph_construction): code for raw data pre-processing and construction of directed weighted graphs (trade, technology ver. 1 and technology ver. 2) -- to be updated 

- [2-centralities_computation](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/2-centralities_computation): code for measurement of node centralities based on [pre-computed graphs](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/1-graph_construction)
  - [computed_centralities](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/2-centralities_computation/computed_centralities): .csv files with precomputed node centralities (trade, technology1, technology2)
    - [technology1](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/2-centralities_computation/computed_centralities/technology1)
    - [technology2](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/2-centralities_computation/computed_centralities/technology2)
    - [trade](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/2-centralities_computation/computed_centralities/trade)
  - [1-trade_centralities.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/2-centralities_computation/1-trade_centralities.ipynb): code for trade network centrality computation
  - [2-technology_1_centralities.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/2-centralities_computation/2-technology_1_centralities.ipynb): code for technology (ver. 1) network centrality computation
  - [3-technology_2_centralities.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/2-centralities_computation/3-technology_2_centralities.ipynb): code for technology (ver. 2) network centrality computation
  - [4-centrality_comparison.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/2-centralities_computation/4-centrality_comparison.ipynb): code for the comparison of centrality measures

- [3-graph_description](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/3-graph_description): calculation of network topology statistics based on [pre-computed graphs](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/1-graph_construction)
  - [graph_descriptions](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/3-graph_description/graph_descriptions): .csv files with network topology statistics
    - [technology1.csv](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/3-graph_description/graph_descriptions/technology1.csv)
    - [technology2.csv](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/3-graph_description/graph_descriptions/technology2.csv)
    - [trade.csv](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/3-graph_description/graph_descriptions/trade.csv)
  - [1-graph_description_trade.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/3-graph_description/1-graph_description_trade.ipynb): code
  - [2-graph_description_technology1.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/3-graph_description/2-graph_description_technology1.ipynb): code
  - [3-graph_description_technology2.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/3-graph_description/3-graph_description_technology2.ipynb): code

- [4-topology_analysis](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/4-topology_analysis): visualization of graph topology dynamics and centrality ranking dynamics of "core" countries
  - [centrality_ranking_visual](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/4-topology_analysis/centrality_ranking_visual): visualization of centrality ranking dynamics
    - [technology1](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/4-topology_analysis/centrality_ranking_visual/technology1)
    - [technology2](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/4-topology_analysis/centrality_ranking_visual/technology2)
    - [trade](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/4-topology_analysis/centrality_ranking_visual/trade)
  - [topology_dynamics_visual](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/4-topology_analysis/topology_dynamics_visual): graph topology statistics dynamics visualization
    - [technology1.pdf](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/4-topology_analysis/topology_dynamics_visual/technology1.pdf)
    - [technology2.pdf](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/4-topology_analysis/topology_dynamics_visual/technology2.pdf)
    - [trade.pdf](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/4-topology_analysis/topology_dynamics_visual/trade.pdf) 
  - [1_topology_analysis_trade.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/4-topology_analysis/1_topology_analysis_trade.ipynb): code
  - [2_topology_analysis_technology1.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/4-topology_analysis/2_topology_analysis_technology1.ipynb): code
  - [3_topology_analysis_technology2.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/4-topology_analysis/3_topology_analysis_technology2.ipynb): code


- [5-centrality_correlations](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/5-centrality_correlations): code for the calculation of correlation coefficients between network centralities (technology 1&2 and trade) and output.
  - [data](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/5-centrality_correlations/data): additional dataset with macroeconomic data
  - [1-centrality_correlations.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/5-centrality_correlations/1-centrality_correlations.ipynb): code
  - [2-centrality_ranks_correlations.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/5-centrality_correlations/2-centrality_ranks_correlations.ipynb): code
  - [3-centrality_output_correlations_all_countries.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/5-centrality_correlations/3-centrality_output_correlations_all_countries.ipynb): code
  - [4-centrality_output_correlations_OECD.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/5-centrality_correlations/4-centrality_output_correlations_OECD.ipynb): code
  - [5-tech_trade_correlations_summary.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/5-centrality_correlations/5-tech_trade_correlations_summary.ipynb): code
  - [6-tech_gdp_correlations_summary.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/5-centrality_correlations/6-tech_gdp_correlations_summary.ipynb): code


- [6-hypothesis_testing](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/tree/main/6-hypothesis_testing): code for the OLS regressions.
  - [1-OLS-trade.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/6-hypothesis_testing/1-OLS-trade.ipynb): technology graph centrality and trade graph centrality
  - [2-OLS-GDPpc.ipynb](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/6-hypothesis_testing/2-OLS-GDPpc.ipynb): technology graph centrality and GDP per capita growth

![centrality comparison](https://github.com/anton-koshelev/International-Interlinkages-and-Long-Run-Growth-A-Graph-Approach/blob/main/2-centralities_computation/centrality_comparison2.pdf)
