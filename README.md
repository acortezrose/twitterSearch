# si 206 twitter homework
working with Twitter data.

assignment directions:
Write code that uses the tweepy library to search for tweets with three different phrases of the user's choice (should use the Python input function), and prints out the Tweet text and the created_at value (note that this will be in GMT time) of the first FIVE tweets with at least 1 blank line in between each of them, e.g.

You should cache all of the data from this exercise in a file, and submit the cache file along with your assignment.  So, for example, if you submit your assignment files, and you have already searched for tweets about "rock climbing", when we run your code, the code should use the CACHED data, and should not need to make any new request to the Twitter API.  But if, for instance, you have never searched for "bicycles" before you submitted your final files, then if we enter "bicycles" when we run your code, it _should_ make a request to the Twitter API.

Because it is dependent on user input, there are no unit tests for this -- we will run your assignments in a batch to grade them!

