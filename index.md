# Completed Data Science Projects to Date
## [Project One: KNN applied to Wisconsin Diagnostic Breast Cancer Data Set](https://github.com/munsonbrian/Tumor_Classification)
**Skills Utilized**
- Scikit Learn: train test split, accuracy evaluation, KNN model training
- Pandas, Numpy: Data visualization, cleaning and manipulation
- Matplot Lib: Result presentation

**Application**
- Creation of a generalized model applicable to catagorical data sets in csv format

**Results**
![Minimization of Beta](images/acc_plot.png 'Model Accuracy in response to number of nearest neighbors') 


## [Project Two: 2D Gaussian Fit for use in Image Detail Enhancement](https://github.com/munsonbrian/2D_Gaussian_Fit)
**Skills Utilized**
- Numpy: Data manipulation
- lmFit: Function fititng to data set
- Matplot Lib: Presentation and Data Visualization

**Application**
- Enhance image detail and reduce unwanted background 'noise' from the data. 

**Result and Next Steps**
![Comparison of Original Image to Processed Image](images/2d_guass_fit.png 'Comparison of Original Image to Processed Image') 


- Further assesment of performance may include comparison of 'image histograms', utilization of different fitment protocols and the use of 'Fast Fourier Tranfmorm' further reduce unwanted signal. 



## [Project Three: Fitting sigle variate gaussian distrubution to toy data](https://github.com/munsonbrian/Gaussian_Peak_Fititng)
**Skills Utilized**
- Python
- Numpy, PIL: Data visualization, cleaning and manipulation
- Matplot Lib: Result presentation

**Application**
- Noise reduction of image collected by laser microscopy

**Results**
- Function was successfully fit to toy data resembling single variate gaussian distrubution with single or multiple peaks
![Single Peak Gaussian Fit](images/fitGaussian.png 'Approximation of Gaussian Distrubution to toy data with single peak') 
![Multi Peak Gaussian Fit](images/fit2Gaussian_peaks.png 'Approximation of Gaussian Distrubution to toy data with multiple peaks ') 




## [Project Four: Fitting Quadratic Function Using Chi Squared Statistical Metric](https://github.com/munsonbrian/Chi_Squared_Fit)
**Skills Utilized**
- LmFit Library: Fits user defined function to data
- Pandas, Numpy: Data visualization, cleaning and manipulation
- Matplot Lib: Result presentation
- Statistical methods including Chi Squared metric

**Application**
- Validation of analytical model to aid in the design of a particle detectior for UTA High Energy Partical Physics Research

**Results**
- Model parameters were determined by utilizing Lmfit methods to fit quadratic function to empirically collected data.
![Minimization of Beta](images/min_beta.png 'Finding value of Beta; coeficient that generalizes quadratic function to fit all collected data') 
![Deflection Fit](images/defl_fit.png 'Fitting of quadratic function to data subsets')


