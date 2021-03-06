***READ ME***

COMP STAT 4601/5601, Winter 2020
Professor: Shirley Mills

Team members: 
Alexei Tipenko, 100995947
Agata Logvin, 101164720

Instructions on how to run:

1) Upload “ResearchProj.ipynb” into google colab
2) Upload the "mbti_1.csv" data file to the same directory (this may take a minute or two)
3) Uncomment the following lines at the end of the imports section in order to install the proper text cleaning packages used by the nltk library:

		#nltk.download('punkt')
		#nltk.download('stopwords')
		#nltk.download('wordnet')

	You can comment them back after running the program once.

4) Click the “Runtime” tab at the top header
5) Click “Run All” to execute all the code (1-2 mins to execute)



Other options:

You can run ResearchProj.ipynb as a Jupiter notebook. Just make sure
that the csv file is in the same directory. 



Output:

The output will show some general visualizations at the beginning, as well the training and testing accuracy results for the optimal method (Logistic Regression using PCA).


Notes:

1) Some code has been commented out due to a long runtime (k-fold). If you would like to test this code, feel free to uncomment it and run the python file in it's entirety. However, the runtime will increase by about 20-30 mins. All results have been noted in the report. 