## Global Ph.D.s Gender Gap Visualizer (2010)

Explore an interactive visualization of the global gender gap in Ph.D. degrees across disciplines and regions.  
Built with **Python**, **Matplotlib**, and **ipywidgets**, this tool lets you:

- ✅ Filter by discipline  
- ✅ Compare male, female, and overall Ph.D. stats  
- ✅ Sort by region or female percentage  
- ✅ Highlight the largest and smallest gender gaps  
- ✅ View trends in an intuitive, visual format

---

## Try It Live (Interactive!)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/znahamama/Data-Visualization-7/HEAD?labpath=gender_gap_visualization.ipynb)

>  Click the **"Launch Binder"** button to open a live, interactive notebook in your browser — no installation needed!

---

## Preview

![Screenshot 2025-03-25 at 7 00 39 PM](https://github.com/user-attachments/assets/66ee8590-55f2-49fa-a6b4-5ffb1245aca1)
*A quick peek at the interactive scatter plot (color-coded by gender, sized by count)*

---

## Files

- `assignment7.ipynb`: Main interactive notebook
- `phds_country.csv`: Dataset used

---

## How to Run Locally

If you'd rather run it on your own machine:

```bash
git clone https://github.com/znahamama/Data-Visualization-7.git
cd Data-Visualization-7
pip install -r requirements.txt  # includes ipywidgets, matplotlib, pandas
jupyter notebook
