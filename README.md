# Data Visualization Project

## Data

The data I propose to visualize for my project is the [top 50 songs in the US from 2010 to 2019](https://gist.github.com/bbbbrianna/e74082354cbdfe18d42c7b66ecdefa76). This dataset includes the most popular songs played in the US in 2010-2019, which was originally from Spotify, each attribute's meaning can be retrieved from [Spotify for Developers](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/).

## Prototypes

I’ve created a proof of concept visualization of this data. It's a line chart, and it shows the change of the signatures of the 10 most popular songs from 2010.

![image](https://user-images.githubusercontent.com/42927474/94642438-1aae5900-02b2-11eb-8ffc-92cd4200eda9.png)(https://vizhub.com/bbbbrianna/ecd35efcf8f7432e9e3e92f7d52c2680)

The data was preprocessed to calculate [the means of features from the top 10 music every year](https://gist.github.com/bbbbrianna/7472f5bf8f2bbab14a3e4411cf8869e0).

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How does people's taste of music change since 2010?
 * Is there a trend of music can be evaluated by their factors?(e.g. bpm, dance)
 * Which artists are becoming more or less popular?
 * Is there any interaction of the music features?

## Schedule of Deliverables
### Tasks
* Yearly Genre Trend Change
- Preprocess to reduct the data, such as calculate the percentage of the top genres (Oct 15)
- Visualize as the bar chart by the top genre, add menu to select the year (Oct 20)
- Tweak the attributes such as colors, size, fonts (Oct 27)
- emphasize the most popular genre by using high-contrast color (Oct 30)

* Signature Change of the Hit Songs
- Preprocess to select the top 10 songs and calculate the mean and standard deviation (Done)
- Realize the sketch showing the line chart of music features change (Done)
- Add the shade as the standard deviation to show the vairations (Oct 15)
- Add the tooltips on each line to show which is the catagory

* Dynamic Bar chart of the change of the most popular artists
- Proprocess to calculate the "popular score of each artist(Oct 27)
- Select the top 15 singers each year and their score to make the dataset(Oct 29)
- Make the barchart with menu showing the year (Nov 4)
- Use Flourish to realize the same function and compare which one is better (Nov 6)


## Sketches
The following are my sketches of how the project will look like.
* the composition of top genres overtime
* the dynamic visualization of the most popular singers from 2010
* the line chart shows the trend of popular music features
![image](https://user-images.githubusercontent.com/42927474/94643299-7b3e9580-02b4-11eb-8f24-aa5bc775d949.png)
![image](https://user-images.githubusercontent.com/42927474/94643309-81347680-02b4-11eb-9dfb-b6748d158309.png)

## Open Questions
We can also explore the specific preference of artists that making such genres of music, or music features.
