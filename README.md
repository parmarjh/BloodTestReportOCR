# OCR recognition, deep learning and analysis of against blood regular inspection report

* Identify the age, gender and various data of the blood routine test report from the picture of the blood routine test report
    * Image upload page, the submitted result is that the image is stored in the mongodb database and gets an OID or to the specified directory to a path
    * Image recognition gets a json data and stores it in the mongodb database to get an OID, [json data][json data](https://coding.net/u/mengning/p/np2016/git/blob/master/BloodTestReportOCR/bloodtestdata.json)
       * Automatically capture the target area. Images with different rotation angles can be automatically prepared to capture the target area. However, the processing effect on oblique perspective images is not good. [Specific usage](https://coding.net/u/mengning/p/np2016/git/blob/master/BloodTestReportOCR/README.md)
       * Preprocessing, such as increasing contrast and sharpening
       * identify
           
    * The recognition results page, the upper part is the original picture, and the lower part is a table showing the recognition data for comparison of the recognition results.
* Learn the various data of routine blood tests and the corresponding age and gender
* Predict age and gender based on various data from blood routine tests

## Links

* [my blog](http://www.csxiaoyao.com/blog/2017/01/01/ustc-np2016%E8%AF%BE%E7%A8%8B%E5%AD%A6%E4%B9%A0%E6%80%BB%E7%BB%93/)
