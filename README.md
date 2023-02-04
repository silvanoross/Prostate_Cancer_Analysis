# Prostate Cancer Analysis in Mice
Innovative grid plotting with hvPlot and dataframe manipulation using Pandas to create an analog for pancreatic cancer pathogenesis in Gna15 control and knockout groups.

In collaboration with Tom Wilkie, Sarthak Reddy et al at the Wilkie Lab in UT Southwestern, Dallas TX.

### Currently in progress...

### Technology

Language: Python 3.7

Libraries used:

[Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - For the creation and visualization of Data Frames in Python

[Jupyter Labs](https://jupyter.org/) - An ipython kernel for interactive computing in Python

[PyViz hvPlot](https://hvplot.holoviz.org/index.html) - A high level Python library for interactive data visualization 

[Matplotlib](https://matplotlib.org/) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python

### We have developed a framework for visualizing prostate cancer pathogenesis in the Gna15 control and knockout cohorts. KCG mice are the Gna15 knockout groups and KC are the control mice with functional Gna15
**Source**
>> Innamorati, G., Wilkie, T.M., Malpeli, G. et al. Gα15 in early onset of pancreatic ductal adenocarcinoma. Sci Rep 11, 14922 (2021). https://doi.org/10.1038/s41598-021-94150-3

> <https://www.nature.com/articles/s41598-021-94150-3#:~:text=The%20GNA15%20gene%20is%20ectopically,toward%20pathways%20with%20oncogenic%20potential.>


### Here are some of the plots comparing lesion scores and their totals:

<img src="./project_files\P40_complete\re_analyzed_plot_images\KC_Lesion_Pie.png" alt="alt text" width="300"/> <img src="./project_files\P40_complete\re_analyzed_plot_images\KCG_Lesion_Pie.png" alt="alt text" width="300"/> 

### A score of 4 indicates there are many lesions in a slice of pancreas being analyzed and a score of 1 indicates around 1 lesion is present in the slice. Eventually we will put together a plot showing the percent lesion of the entire field. This is important because a lesion with a score of 1 can end up taking up the entire field of view, whereas a score of 4 could be many tiny lesions that do not take up a lot of space. 


<img src="./project_files\P40_complete\re_analyzed_plot_images\lesion_kc_plot.png" alt="alt text" width="200"/> <img src="./project_files\P40_complete\re_analyzed_plot_images\lesion_kcg_score.png" alt="alt text" width="200"/>


### Here are is the innovative visualization for pathogenesis that analogs sections in the pancreas:

<img src='./project_files\P40_complete\plot_images\no_adm_combo.png' alt='alt text' width='1000'>

### Tom Wilkie et al are trying to show that Gna15 is important for early lesion development in mice. This early lesion development is indicative of a healthy pancreas. 
