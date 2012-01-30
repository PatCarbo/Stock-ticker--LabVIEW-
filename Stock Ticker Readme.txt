Greetings!


Just a few notes...


Blog
- A blog has been written about this project. See http://patricecarbo.wordpress.com/2012/01/30/of-portfolio-labview-and-stock-ticker/


Src
- This application is the result of an exercise. It is not meant to be an application ready for general usage.
- LabVIEW 2011 for Windows and Mac OS X have been used to create this project.
- Keep in mind that the application doesn't use a list of stock ticker and that each character you enter or delete in the symbol field sends a GET command to either Google or Yahoo.
- Another abstraction layer could have been inserted between "Main - Stock Ticker.vi" and "Yahoo/Google - Get Data (for stock ticker).vi". This would have slightly simplified implementation. I will do this if I ever increase the number of data source (currently 2, Yahoo and Google).


Test
- TDD and JKI's VI Tester for LabVIEW have been used while refactoring the code.
- Unfortunately, TDD is not much use for testing "Main - Stock Ticker.vi". This would need to be tested with a test automation tool like Ranorex.


Copywright @ 2012 Patrice Carbonneau