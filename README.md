# STMHCPan
## Running Environment
pip install pytorch_gpu==1.10.0  
pip install python==3.7    
pip install scikit-learn==1.0.2   
pip install numpy==1.19.5  
pip install pandas==1.3.5    

hardware: GPU  

## Train and Test  
cd ./code  
You can use STMHCPan_netmhcpan.ipynb for train.  
You can use predict_ensemble.py for predict.   

### For example:  
#### python predict_ensemble.py  
You can change the input file in this .py file

## Data  
Training data sets and independence Test data sets are stored in the data file.

## Result  
The test result data was saved in ./data/test_set  
The picture of test data was saved in ./pic 

## MIT License

Copyright (c) 2025 Charlesyip2016

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
