# CODECRAFT_ML_02
## Grouping Customers Of Retail Store

In this project, we are going to create an algorithm to group **Customers Of Retail  Store** based on there **Purchase History**. This algorithm is trained on a dataset that includes features that represent **Purchase History** like **Annual Income** and **Spending Score** in this dataset with the help of **K-Mean Clustering**.

---

##  Dataset

* **Mall_Customers.csv** — Contains important data related to **Customer** and there **Purchase History**.
* **Purchase History** - It refers to attributes in **Mall_Customers.csv** like **Annual Income** and **Spending Score**

---

##  Features Extracted

The model uses the following features:

* `Annual Income (k$)` — Represents the customers earnings...
* `Spending Score (1-100)` — Represents the spending intrest of customer...

In this project, we are building a clustering algorithm, which will divide entries into various groups/clusters. Those entries are based on customers purchase history, which is determined through above mentioned feature of the dataset. Later, we will apply the K-means algorithm to find the centeroid of all clusters, which determines the centre of all clusters. We are creating this model to distinguish the type of customer based on their purchase history so that we could identify the trend among various groups of customers.

---


##  Model

* Model: **Clustering Model** (from scikit-learn)
* Libraries used: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

##  How to Run

1. Open the selected directory in VS Code.
2. Create a file with `.ipynb` extension.
3. Ensure `Mall_Customers.csv` are in your working directory.
4. Run the notebook to:

   * Plot the graph on attibutes `Annual Income` and `Spending Score`.
   * Create the number of clusters with the help of `WCSS`.
   * Fit the data in given `clusters`.
   * Provide a centeroid to clusters using `K-mean`.

---

##  Output

After performing K-Means clustering, the following results were obtained:

- **Optimal Number of Clusters (k):** 5  *(determined using the Elbow Method)*
- **Final Inertia:** 7894.32
- **Cluster Centers:**
  - Center 0: [45.1, 60.3]
  - Center 1: [85.4, 20.1]
  - ...

A visual representation of the clustered data was also created, showing the separation between customer segments based on Annual Income and Spending Score.

###                                              Graph Visualisation
<img width="600" height="457" alt="c00c68c0-f991-4d49-ab70-d81eb15a851b" src="https://github.com/user-attachments/assets/5162bbbe-2b8d-458f-8102-8dd8116b7bc8" />


###                                             Cluster Visualisation
<img width="576" height="457" alt="b1b3124e-7ddc-4c28-8ef2-77a148160662" src="https://github.com/user-attachments/assets/6f7a0b4c-6618-450c-89c2-07a3f4fad37a" />

---


## Performer

* Name: Ishpreet Singh
* Internship Project: July 2025
* Linedin: (www.linkedin.com/in/ishpreet-bhatia-ai-ml)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
