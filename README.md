# web-crawler

### 🚀 Project Overview
This repository demonstrates a comprehensive web crawling solution for exploring and indexing the vast expanse of the internet. The goal is to visit every page on the web, based on their indexing and ranking.

### 🧠 Problem-Solving Approach
The Challenge：
- Indexing the Internet: Efficiently visiting and cataloging webpages.
- Ranking Webpages: Determining the importance of pages.
- Finding Shortest Paths: Navigating from one page to another in the least steps.

The Solution implements a breadth-first search (BFS) algorithm to methodically explore the web, starting from a given URL and visiting each linked page. This approach uses an "implicit" graph representation of the web.

### 🛠️ Algorithm Implementation
1. PageRank and Dijkstra's Algorithms
- PageRank: Evaluates the significance of each webpage.
- Dijkstra's Algorithm: Finds the shortest paths between pages.
2. Data Structures
- Graph ADT: Represents the web structure.
- List ADT: Manages the list of URLs efficiently.
