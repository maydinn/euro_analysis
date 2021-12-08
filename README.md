# euro_analysis

DESCRIPTION:

In this repository, you will find the analyzes of Euro and Europeanen Central Bank press releases

DATA:

Euro : yahoo finance 

Press releases : https://www.ecb.europa.eu/press/pr/html/index.en.html


Some insights:

*  the value for Euro for days with press releases and without press releases is different

* there is a significant negative correlation between not only the number of press releases and Euro but also press release, as a dummy variable, and Euro

* for SARIMAX, the impact of the number of press releases did not have a significant impact, but it did not make the results for test data worse either

* for LSTM, so that the number of press releases made the results slightly better

*  the relation between Euro and compound score was positive and significant. 

*  for sentiment analysis, it predicted very poorly for the test data, it worked pretty well with train data. Nevertheless, for classification map, and for example, while the taxation was affiliated with negative impact, the growth had a positive one. 
