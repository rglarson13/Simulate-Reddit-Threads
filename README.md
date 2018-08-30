# Simulate-Reddit-Threads
Look at the top 1000 posts in a given subreddit and use a markov-ish chain to generate a thread title

This originally started as an idea for a party game -- take satirical headlines from The Onion and real-but-strange headlines collected on Reddit's subreddit r/NotTheOnion, then try to decide which one was real and which was satire.

Then I decided it'd be funny to add simulated headlines to the mix.

I use a Markov-inspired process to choose the next word based on the previous (but my corpus isn't particularly comprehensive, so each subsequent word is chosen at random from words that _have_ followed the previous word, without concern for frequency/likelihood that it'll come next)

Since I had the data, I also took a look at when top threads are likely to be posted and plotted that as a heatmap.
