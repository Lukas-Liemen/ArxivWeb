# ArxivWeb: Visualizing Citation Networks

## Overview
ArxivWeb is a small side project of mine that aims to create an interactive graph to visualize citation networks between research papers on arXiv. It aims to provide a straightforward way to explore the connections between papers and their references.

## Setup
- Install required libraries: requests, fitz, arxiv, concurrent.futures, and pyvis
- Run the script to generate the citation network graph

## Features
- Searches for papers on arXiv using the python wrapper for arXiv api
- Extracts referenced papers from PDFs using fitz
- Creates an interactive graph to visualize citation networks using pyvis
- Supports recursive searching of referenced papers up to a specified depth

## Limitations
- Limited to searching papers on arXiv
- May not work correctly for papers with non-standard reference formats
- Performance may degrade for very large citation networks

## Usage
- Run the script with a paper ID as an argument to generate the citation network graph
- Adjust the max_depth parameter to control the depth of the recursive search
- Use the interactive graph to explore the citation network and discover new papers and authors

## Example
![Image of the network displayed by Papers.html](https://github.com/Lukas-Liemen/ArxivWeb/blob/main/Example/Network.PNG)
![Zoomed in](https://github.com/Lukas-Liemen/ArxivWeb/blob/main/Example/Network_Zoomed_In.PNG)
