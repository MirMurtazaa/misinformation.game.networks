# Graph-Based Iterated Game Model for Limiting the Spread of Unverified News on Social Networks

This repository contains the code and resources used in our study, **"A Graph-based Iterated Game Model for Limiting the Spread of Unverified News on Social Networks."** The project is implemented in two Jupyter notebooks that demonstrate the simulation of our model and the generation of results from the simulation output.

## Overview

Our work proposes a proactive, game-theoretic framework that leverages mutual news verification among users to reduce the spread of unverified news on social networks. We evaluate the model on synthetic network models—such as Erdős-Rényi, scale-free, and regular random graphs—to analyze the impact of key parameters on cooperation dynamics.

## Repository Structure

- **coop.game.net.minfo-R.ipynb:**  
  This notebook conducts the simulations of the game-theoretic model. It generates synthetic networks, simulates interactions among nodes based on the iterated game, and saves the output data for further analysis.

- **plotsR-Parameters.ipynb:**  
  This notebook processes the simulation output data to generate results, including graphs and tables that illustrate the effect of varying parameters (e.g., benefit-to-cost ratio) on the spread of unverified news.
