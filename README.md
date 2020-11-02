# Are Election Years the Best Time to Invest?

## Overview: 
  

## Motivation:

  I have always had a very deep rooted interest in finance and I thought it would be worth applying my techincal background skills from engineering to data science to approach this problem. With the help of my instructors at Galvanize Inc. I was able to get good guidance in how I should begin to approach this problem.

## Data Collection:
  Three open source datasets were collected from [Yahoo Finance](https://finance.yahoo.com/), in order to explore my question listed in the abstract section.
  
  * **Dow Jones dataset contains:**
    * 9000+ entries, 7 columns 
    * Adjustable back to 1985 to 2020
    * 748.3 kB file size
  
  * **Nasdaq dataset contains:**
    * 12000+ entries, 7 columns 
    * Adjustable back to 1971 to 2020
    * 957.8 kB file size
  
  * **S&P 500 dataset contains:**
    * 23000+ entries, 7 columns 
    * Adjustable back to 1927 to 2020
    * 1.7 MB file size

## Tech Stack:

  ![alt text](https://github.com/yamasjose11/index-elections/blob/main/images/Screenshot%20from%202020-11-01%2013-37-15.png?raw=true) 

## Statistical Approach:
I chose to go with a very strict significance level of 0.01, given the fact that there is various external factors not being taken into considered for this project. For the proposed hypothesis I will be conducting a Welch's t-test to test for the sample mean a period* before election and after.

  **Null Hypothesis:** The adjusted closing price mean after presidential elections is different than before elections.
  
  **Alt. Hypothesis:** The adjusted closing price mean after presidential elections is **not** different than before elections.

## What Does the Data Say?
  After conduction my tests before and after election years for all presidents after 1995. I have come to the conclusion that more data is required and additional statistical tests are required. The following table will show my results for each president across the Dow, Nasdaq and S&P500. 
  
  <p align="center">
  <img width="460" height="300" src="https://github.com/yamasjose11/index-elections/blob/main/images/Screenshot%20from%202020-11-01%2015-53-14.png?raw=true">
  <img width="460" height="300" src="https://github.com/yamasjose11/index-elections/blob/main/images/Screenshot%20from%202020-10-30%2011-50-58.png?raw=true">
  </p>
  
## Future Development:
  For future development points it would be very cool to test for corrolation across markets such as other major indices, cryptocurrencies, bonds and more. It would also be very cool to implement machine learning techniques to measure volatility and read market structure. 

## Awknowledgements:
  Thank you to the instructors at Galvanize Inc., Dan Rupp, Juliana Duncan, Justin Wallander and Zach Schuiz for their help and guidance during this project. Also, thank you to my classmates especially Hilmi Kilickaya and Vinay Vakharia for their comprehensive suggestions.
  
## References:
**Dow Jones Database:**

  [Yahoo Finance. *Dow Jones Industrial Average (^DJI)*. Accessed 26 October 2020.](https://finance.yahoo.com/quote/%5EDJI/history?p=%5EDJI)
    
**NASDAQ Database:**

  [Yahoo Finance. *NASDAQ Composite (^IXIC)*. Accessed 26 October 2020.](https://finance.yahoo.com/quote/%5EIXIC/history?p=%5EIXIC)
    
**S&P 500 Database:**

  [Yahoo Finance. *S&P 500 (^GSPC)*. Accessed 26 October 2020.](https://finance.yahoo.com/quote/%5EGSPC/history?p=%5EGSPC)

## Contact Info:

[Send Email](mailto:yamasjose11@gmail.com)

[LinkedIn](https://www.linkedin.com/in/jose-yamas/)

________________________________

