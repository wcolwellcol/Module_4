# Module_4

# Mod4Chall
Repo for Week 4 Challenge of Fintech Course in which I conduct quantitative analysis on 4 different portfolios compared to the S&P 500. This is retroactive calculation and not actionable insight, but is still interesting to look at.

---
## Technologies
This code was written using Python 3.7.13. I found it very helpful to work in jupyter notebooks as it is nearly a necessity to be able to run segmented parts of the code. However, one could accomplish this goal using other technologies or choose to not even do so whatsoever.

My OS is Ventura 13.2.1 though it should be fine on most others. Note that the CLI in any screenshots may look different on different OSs.
I used conda to manage all of my packages.
Packages used:

csv 1.0
pandas 1.3.5
numpy 1.21.5
matplotlib-inline 0.1.6

---
## Installation
The user may not have to install any packages, but if one finds that they do I would recommend using` pip install`
For example,
`pip install <package name>`

If you are unsure of what python version (if any) you have, here is a handy link to troubleshoot those issues. 
[Installing python](https://realpython.com/installing-python/)



---
### Usage
The goal of this project is to identify how various portfolios perform over a near 10 year period starting in late 2014

Code can be found in the following notebook [risk_return_analysis.ipynb](https://github.com/wcolwellcol/Module_4/blob/main/risk_return_analysis.ipynb).

Data for this project is sourced from the csv held in resources folder: [bitstamp.csv](https://github.com/wcolwellcol/Module_4/tree/main/Resources).

In general, the code can be summarized as various calculations of basic financial statistics in ratios. Standard deviation, variance, covariance, means, etc. of portfolio returns are all calculated and visualized in this notebook. In addition, rolling windows are utilized as well to smooth out these calculations.




## Contributors

This code was written by me, but the framework was provided by the Columbia Fintech Bootcamp

## License

MIT License

Copyright (c) [2023] [willcolwell]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.