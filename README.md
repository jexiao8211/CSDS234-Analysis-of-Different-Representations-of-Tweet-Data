# Analysis-of-Different-Representations-of-Tweet-Data
CSDS 234 Final Project: Jerry Xiao, Quoc Trung Nguyen, Akansh Devandra

(from report)
The main objective of this paper is to analyze the space and time complexity of storing and querying
different text-data representations. Twitter data is particularly interesting as it has a large user base of 450
million monthly users [1], leading to around 500 million daily tweets [1]. This data comprises information
that can play an important role in diagnostic and descriptive analysis, such as sentiment analysis about
political leaders, sports teams, and stocks. It could also detect crimes, bots, or world events.
Since each tweet is limited to 280 characters, processing tweets is much more optimized, making it more
efficient to search and query a dataset.[2] Our results will illustrate the efficiency of each representation
compared to each other, allowing us to make conclusions about the risks/rewards of each implementation.
Our tests would generally apply to any vectorized text representation of data. While accuracy is essential,
so is the ease of storage and access of this data. Therefore, because twitter data is massive, it is of great
importance for researchers to use it for further research. Thus, we need to be able to store and query such
large amounts of information efficiently.[2]
