# Neuroscience Notebook Templates

This repository contains Jupyter notebooks I wrote in the [SND lab](https://nin.nl/research-groups/lohmann/). Here, you will find basic templates for processing and analyzing neuroscience data that you may find useful. 

If you **clone the repository**, you should be able to run all the cells of each notebook using the corresponding example data in the **Data_examples** folder. Feel free to modify the notebooks for your own analysis.

**Note**: All external libraries used in these notebooks are credited to their respective authors and contributors, subject to their licenses and terms.

# List of Jupyter Notebooks

To simplify the folder structure of this GitHub repository, I have placed all the example files into the **Data_examples** folder. If you **clone the repository**, you should be able to run all the cells of each notebook.

### [caiman_motion_correction](Notebooks/caiman_motion_correction.ipynb)
- How to use the package [CaImAn](https://github.com/flatironinstitute/CaImAn) for motion correction of time-series confocal recordings.
- Data_examples: dendrite_ch1.tif, dendrite_ch2.tif

### [cellpose_estimation_2p](Notebooks/cellpose_segmentation_2p.ipynb)
- Uses [cellpose](https://github.com/MouseLand/cellpose) to segment neurons from two-photon calcium imaging, then extracts and plots deltaF/F traces from each neuron.
- Data_examples: 2P_GCaMP8m.tif, 2P_somaFRCaMPi.tif

### [dataframes_plots](Notebooks/dataframes_plots.ipynb)
- Examples for navigating DataFrames with [Pandas](https://pandas.pydata.org/), plotting with [Matplotlib](https://matplotlib.org/stable/gallery/index.html) and [Seaborn](https://seaborn.pydata.org/examples/index.html), and performing statistics with [SciPy](https://docs.scipy.org/doc/scipy/reference/stats.html).  
- Data example: cell_types_specimen_details.csv.

### [estimation_stats_dabest](Notebooks/estimation_stats_dabest.ipynb)
- Estimation statistics using the library [DABEST](https://acclab.github.io/DABEST-python/) by [Ho et al., 2019](https://doi.org/10.1038/s41592-019-0470-3).
- Data_examples: cell_types_specimen_details.csv.

### [lif_to_tif](Notebooks/lif_to_tif.ipynb) 
- Reads Leica Image Files (LIFs) using [AICSImage](https://allencellmodeling.github.io/aicsimageio/) and converts them to TIFF files, either as stacks or single files.
- Data_examples: LIF01.lif, LIF02.lif, LIF03.lif.

### [nd2_to_tif](Notebooks/nd2_to_tif.ipynb)
- Reads Nikon ND2 files using the [ND2](https://github.com/tlambert03/nd2) library and converts them to TIFF files. It also includes an example for downsampling stacks.
- Data_examples: **NIK01a01_seq.nd2**, **NIK01b01.nd2**, **NIK02a01.nd2**.

### [spectra_viewer](Notebooks/spectra_viewer.ipynb)
- A basic fluorescence spectra viewer.
- Data_examples: filter_spectrum_479-585.txt, filter_spectrum_524_628.txt, fp_spectra_egfp.csv, fp_spectra_mapple.csv, led_spectrum_M470L5.xlsx, led_spectrum_M565L3.xlsx.

### [superplots](Notebooks/superplots.ipynb) 
- Creates SuperPlots in Python using Matplotlib and Seaborn. This notebook adapts the tutorial by [Lord et al., 2020](https://doi.org/10.1083/jcb.202001064).
- Data_examples: cell_types_specimen_details.csv, jcb_202001064_datas1.txt.

### [time_series_preprocessing](Notebooks/time_series_preprocessing.ipynb)
- Examples for detrending, filtering, and smoothing time series.
- Data_examples: WF01a.csv, WF02b.csv.

### [video_to_tif](Notebooks/video_to_tif.ipynb)
- Reads video files (e.g., AVI, MP4) with [OpenCV](https://docs.opencv.org/2.4/index.html) and converts them to TIFF files, with options for downsampling.
- Data_examples: FCM01.avi, FCM02a.mp4.


# Python Resources

## Jupyter Notebooks

- Barba et al., 2019. [Teaching and Learning with Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/).
- Codecademy. [Basics of Jupyter Notebooks](https://www.codecademy.com/articles/how-to-use-jupyter-notebooks).
- Data Carpentry. [Reproducible Research Using Jupyter Notebooks](https://reproducible-science-curriculum.github.io/workshop-RR-Jupyter/).
- Rule et al., 2019. [Ten Simple Rules for Writing and Sharing Computational Analyses in Jupyter Notebooks](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007007). [GitHub](https://github.com/jupyter-guide/ten-rules-jupyter?tab=readme-ov-file).
- VanderPlas, 2017. [Reproducible Data Analysis in Jupyter](https://jakevdp.github.io/blog/2017/03/03/reproducible-data-analysis-in-jupyter/).

## Tutorials and Courses for Beginners

- Blomqvist et al., 2020. [Python for Scientific Computing](https://aaltoscicomp.github.io/python-for-scicomp/).
- Code Refinery. [Data Visualization with Python](https://coderefinery.github.io/data-visualization-python/).
- [Pandas Cookbook](https://github.com/jvns/pandas-cookbook) by Julia Evans.
- Downey, 2023. [Elements of Data Science](https://allendowney.github.io/ElementsOfDataScience/index.html).
- Shafer. [Python Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU). 150+ video tutorials.
- Software Carpentry. [Basics](https://swcarpentry.github.io/python-novice-inflammation/) and [Plotting](https://swcarpentry.github.io/python-novice-gapminder/) in Python.

## Scientific Computing

- Carey and Papin, 2018. [Ten Simple Rules for Biologists Learning to Program](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005871).
- FAIR Principles. [Findability, Accessibility, Interoperability, and Reusability](https://www.go-fair.org/fair-principles/).
- Hart et al., 2016. [Ten Simple Rules for Digital Data Storage](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005097).
- Noble, 2009. [A Quick Guide to Organizing Computational Biology Projects](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424).
- [pyOpenSci Python Package Guide](https://www.pyopensci.org/python-package-guide/index.html).
- [Python Packages Workflow](https://py-pkgs.org/welcome). Workflows for creating Python packages.
- Sandve et al., 2013. [Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285).
- Wilson et al., 2017. [Good Enough Practices in Scientific Computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510).

## Data visualization

- Friends Don't Let Friends Make Bad Graphs. [GitHub](https://github.com/cxli233/FriendsDontLetFriends). Good examples (in R) about good and bad practices in data visualization
- [From Data to Viz](https://www.data-to-viz.com/). Great website on choosing the right graph with examples in [Python](https://python-graph-gallery.com/).
- [Python Color Palette Finder](https://python-graph-gallery.com/color-palette-finder/): A collection of 2500+ palettes to use directly in Matplotlib.
- [Seaborn](https://seaborn.pydata.org/tutorial.html). Superb data visualization library based on matplotlib.

## Statistics
- James et al., 2023. [An Introduction to Statistical Learning](https://www.statlearning.com/).
- Lindeløv, 2019. [Common statistical tests are linear models](https://www.georgeho.org/tests-as-linear/). Port to Python by George Ho.
- Navarro and Weed, 2021. [Learning Statistics with Python](https://ethanweed.github.io/pythonbook/landingpage.html).
- Poldrack R, 2024. Statistical Thinking for the 21st Century. [Book](https://statsthinking21.github.io/statsthinking21-core-site/index.html), [Python code](https://statsthinking21.github.io/statsthinking21-python/).
- Weed, 2021. [Learning Statistics with Python](https://ethanweed.github.io/pythonbook/landingpage.html).

## Neuroscience

- Data Carpentry. [Image Processing with Python](https://datacarpentry.org/image-processing/).
- DeepLabCut. [GitHub](https://github.com/DeepLabCut). Widely used toolbox for pose estimation. 
- Kramer and Eden. [Case Studies in Neural Data Analysis](https://mark-kramer.github.io/Case-Studies-Python/intro.html). LFP and EEG examples.
- Juavinett A. [Signal Processing](https://github.com/BILD62/Materials/blob/main/12-SignalProcessing.ipynb).
- Neuromatch. [Computational Neuroscience](https://compneuro.neuromatch.io/tutorials/intro.html).
- Newman A. [Data Science for Psychology and Neuroscience](https://neuraldatascience.io/intro.html). Examples of single-unit, EEG, and MRI data.
- Spikes and Bursts Blog. [Patch-Clamp Data Analysis in Python](https://spikesandbursts.wordpress.com/patch-clamp/). Tutorials for analyzing action potentials, synaptic events, etc., from my [Spikes and Bursts](https://spikesandbursts.wordpress.com/about/) neuroscience blog.

## Books

- VanderPlas J, 2016. [A Whirlwind Tour of Python](https://nbviewer.org/github/jakevdp/WhirlwindTourOfPython/tree/master/). [GitHub](https://github.com/jakevdp/WhirlwindTourOfPython/).
- VanderPlas, 2016. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/). [Notebooks on GitHub](https://github.com/jakevdp/PythonDataScienceHandbook).

