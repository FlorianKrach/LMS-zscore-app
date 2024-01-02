# WebApp
A web application for Z-Score computation with LEAD LMS reference values for body composition parameters (adults and children) is available at: [https://floriankrach.github.io/pyscripts/zscore-app-pyscript/](https://floriankrach.github.io/pyscripts/zscore-app-pyscript/index.html).

# LMS-zscore-app
standalone macOS and Windows application for Z-Score computation with LEAD LMS reference values

## Reference
The applications can be used to compute Z-scores of body composition parameters with the reference values for:

- adults published in:  
__Article Title__: Reference values of body composition parameters and visceral adipose tissue (VAT) by DXA in adults aged 18–81 years—results from the LEAD cohort  
__DOI__: 10.1038/s41430-020-0596-5, 2019EJCN0971  
__Link__: https://www.nature.com/articles/s41430-020-0596-5  
__Citation__: Ofenheimer, A., Breyer-Kohansal, R., Hartl, S. et al. Reference values of body composition parameters and visceral adipose tissue (VAT) by DXA in adults aged 18–81 years—results from the LEAD cohort. Eur J Clin Nutr (2020).

- children published in:  
__Article Title__: Reference charts for body composition parameters by dual‐energy X‐ray absorptiometry in European children and adolescents aged 6 to 18 years—Results from the Austrian LEAD (Lung, hEart , sociAl , boDy ) cohort  
__Link__: http://dx.doi.org/10.1111/ijpo.12695  
__Citation__: Ofenheimer, A, Breyer‐Kohansal, R, Hartl, S, et al. Reference charts for body composition parameters by dual‐energy X‐ray absorptiometry in European children and adolescents aged 6 to 18 years—Results from the Austrian LEAD (Lung, hEart , sociAl , boDy ) cohort. Pediatric Obesity. 2020;e12695. https://doi.org/10.1111/ijpo.12695


## Installation

- donwload the ZIP file for your operating system from the following links:
  * [MacOS](https://drive.google.com/file/d/1yFeIRkFhvuneLiUll2ODbSsUWG-1iPTz/view?usp=sharing). Requirements: MacOS 10.15.x or higher.
  * [Windows](https://drive.google.com/file/d/1gehlHpsnJLuei5Q5_50DpdGRgs3DvRLQ/view?usp=sharing). Requirements: Windows 10.

- unpack it
- the unpacked application can be used right away without additional installation


## Usage
- provide all information: 
  * birthdate and the day of the DXA measurement in following format: DD-MM-YY, e.g. for 1st of May 2001 write 01-05-2001
  * the sex: for male write 0, for female write 1
  * the value of the measurements that you have values for:   
    FM android/gynoid, FM trunk/limbs and weight in kg  
    height in cm  
    VAT mass in g  
    LMI, FMI, BMI and appendicular LMI in kg/m^2  
    fitted BMI and fitted LMI in kg/m^3  
    fitted FMI in kg/m^2.5  
    fitted appendicular LMI (ALMI) in kg/m^3.5  

- how to calculate the indices (FMI, LMI, BMI, appendicular LMI): 
  * take the value of the total body lean mass/fat mass/body mass or the sum of the lean mass of the limbs in kg
  * divide it by the body height^2 (cm)

- if you want to compare the fitted indices:
  * divide it by height^exponent

Note: some of the variables are only available for children (aged < 18 years) and some only for adults (≥ 18 years).

## Known Issues

* both operating systems:
  - it might take some minutes for the application to start
  - you migh have to aggree to open the application under system preferences

* MacOS:
  - an operating system of 10.15.x or higher should be used
  - using the operating system 10.14.x will cause the user to be logged out when starting the application


## Citation
If you find these applications useful or if you use it for your own work, please cite the papers referenced above.

## Further information
For further questions write an e-mail to a.ofenheimer@gmx.net.   
The reference charts published in the articles, can be provided on request in a larger format.

