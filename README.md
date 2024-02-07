# Top-1000-Youtube-channels
EDA in Excel

Dataset link : https://www.kaggle.com/datasets/shiivvvaam/top-youtuber-worldwide

The steps I took to generate the results are:
1. Downloaded the data in .csv format.
2. Cleaned the dataset.
   2.1 Checked the datatype in each column, if it was appropriate.
   2.2 Looked for the empty data points and replaced them with None/Null appropriately.
   2.3 Converted the data into proper format. For instance, the subscribers were formated as 285M which I converted into numbers.
3. For analysis, I started out by first studying the geographical distribution of these highest subscribing channels.
   3.1 Removed the rows for which country name was unspecified.
   3.2 Created a pivot table, taking the country names as pivot and calculated the metrics around it.
   3.3 Plotted a map graph.
4. For the next step, I analysed the top 5 highest subscription channels.
   4.1 I started out by first sorting the entire dataset on the basis of subscribers column.
   4.1 Selected the first fiver enteries and created a funnel graph to visualise it.
5. Finally, I went to analyse the trends across various categories for these top 1000 highest subscribing channels.
   5.1 Created a pivot table taking the category as the pivot and calculating all the metrics around it.
   5.2 Created pie charts to understand the distribution of various categories among these channels.
