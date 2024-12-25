# PFF FC Project

This project includes several Jupyter notebook files, a blog post (in PDF format), and AI prompts. Below is an overview of the files and their purposes.

---

## **Files Overview**

### **1. Data Cleaning**
- **`clean_data.ipynb`**:  
  Cleans metadata, rosters, players, and events data and converts them into pandas DataFrames for further analysis.

### **2. Tracking Data Cleaning**
- **`clean_tracking.ipynb`**:  
  Processes tracking data to generate a DataFrame where each frame includes 22 rows (one for each player) with their respective coordinates on the field.  

  > **Note:** For this project, only tracking data from possession events when Argentina had the ball was used, due to memory and crash issues.  
  > Running this notebook can be time-intensive, but a pre-cleaned CSV file is included and is used directly in other notebooks.

### **3. Custom Plotting Function**
- **`pitch_plot_fun.ipynb`**:  
  Contains a custom function for plotting a football pitch, used across other analyses.

### **4. Analysis Notebooks**
- **`messi_analysis.ipynb`** and **`pass_prob.ipynb`**:  
  Perform the core analysis of the project, focusing on Messi's actions and pass probability modeling.

### **5. Miscellaneous**
- **`misc.ipynb`**:  
  Used for exploring additional ideas and concepts that were not included in the final project.


---

## **Included Data**
- A cleaned CSV file for tracking data is provided

---
