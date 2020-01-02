# wieghted_hybrid_technique_for_recommender_system

A very basic recommender system to recommend movie to the user.
I have CSV file so movies in which rating of movies and how many time movie is rated ig given.
On the basic of no of ratings given and rating we will recommend movie to the user.
For recommendation we are using weighted hybrid techniue in which we take 50% participation of both the parameter.

FORMULA:-

W = Rv + Cm / v + m
where
W = Weighted Rating
R = average for the movie as a number from 0 to 10 (mean) = (rating)
v = number of votes for the movie = (votes)
m = minimum votes required to be listed in the Top 250 (currently 3000)
C = the mean vote across the whole report (currently 6.9)

RUN THIS PROJECT:-
1. download this project or clone it.
2. open in jupyter notebook.
3. run each cell sequenclly to see result.

ENVR:-
1. Anaconda distribution with jupyter notebook.
2. macos/linux/windows.
