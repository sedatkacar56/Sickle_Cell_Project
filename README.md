# 🩸 Sickle Cell Project  

This repository contains scripts and functions for processing and analyzing **Sickle Cell Anemia** data using **Seurat** in R.  
The project focuses on integrating multiple datasets, performing **quality control**, **normalization**, **clustering**, and **differential gene expression (DEG) analysis**.

---

## 🔬 **Project Overview**  
- **Dataset:** Single-cell RNA sequencing (scRNA-seq) data for **wild-type (WT) and sickle cell (ScAnemia) mice**.
- **Samples:**
  - **VPC1** → WT Male  
  - **VPC2** → Sickle Male  
  - **VPC3** → WT Female  
  - **VPC4** → Sickle Female  

- **Methods Used:**  
  ✅ **Data Processing:** Reading `.h5` files, creating Seurat objects  
  ✅ **Quality Control:** Feature count thresholds, mitochondrial content filtering  
  ✅ **Data Normalization:** Log normalization, variable feature selection  
  ✅ **Dimensionality Reduction:** PCA, UMAP  
  ✅ **Clustering:** Graph-based clustering (`FindNeighbors`, `FindClusters`)  
  ✅ **Differential Expression (DEG) Analysis:** Identifying key genes  
  ✅ **Integration Analysis:** Combining multiple datasets  
  ✅ **Visualization:** UMAP, Heatmaps, DotPlots, Bar charts  

---

## 📂 **Repository Structure**
