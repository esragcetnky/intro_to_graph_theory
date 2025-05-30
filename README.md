# Intro to Graph Theory with Movies

This repository includes a Jupyter notebook: [`intro-to-graph-theory-with-movies.ipynb`](intro-to-graph-theory-with-movies.ipynb).  
The notebook demonstrates practical applications of graph theory using a real-world movie ratings dataset.

## Notebook Overview

- **Data Loading and Exploration:** Loads `movies.csv` and `ratings.csv` from the `Data/` directory and provides summary statistics.
- **Data Preprocessing:** Samples and cleans the ratings data for manageable graph analysis.
- **Graph Construction:** Builds a bipartite graph of users and movies using NetworkX.
- **Centrality Analysis:** Calculates and visualizes degree centrality and bipartite degree centrality.
- **Subgraph Extraction:** Focuses on specific users and their movie connections.
- **Path Existence Checks:** Determines if a path exists between two nodes.
- **User Similarity & Recommendations:** Measures user similarity and recommends movies based on graph structure.
- **Graph Projections:** Creates user-user and movie-movie projections.
- **Temporal Analysis:** Examines how the graph evolves over time, including edge changes and centrality trends.
- **Visualization:** Uses matplotlib and nxviz for various graph visualizations.

## Running the Notebook

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Ensure data files are present:**
   - Place `movies.csv` and `ratings.csv` inside the `Data/` directory.

3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook intro-to-graph-theory-with-movies.ipynb
   ```

4. **Run the cells in order for a complete walkthrough of the analysis.**

---

## Project Structure

```
.
├── .gitignore
├── README.md
├── requirements.txt
├── intro-to-graph-theory-with-movies.ipynb
├── Data/
│   ├── movies.csv
│   └── ratings.csv
└── environment/
    ├── pyvenv.cfg
    ├── Include/
    ├── Lib/
    ├── Scripts/
    └── share/
```

---

## Notes

- The notebook is self-contained and can be run independently for educational or exploratory purposes.
- Data files are required in the `Data/` directory.
- The virtual environment folder `environment/` is included in `.gitignore` and should not be committed.

---


## Contributing
If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or suggestions, feel free to reach out:

  - Email: esragcetinkaya@gmail.com
  - Linkedin : [esragcetinkaya](https://www.linkedin.com/in/esra-gul-cetinkaya/?locale=en_US)
