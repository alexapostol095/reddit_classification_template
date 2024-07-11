This repository contains the code that classifies political reddit posts utilizing the llama3 LLM model. The top 50 posts of the Republican and Democrat subreddits were extracted with respect to the total number of comments on the post. The code outputs a numerical rating generated by the LLM from 1 to 5, with lower scores corresponding to posts more in line with the republican party and vice versa. The -1 score represents a post that was deemed too violent and/or divisive for the LLM to interact with. The code outputs a JSON file, with the first 50 rows corrspondings to the Republican subreddit posts and the last 50 posts corresponding to the Democrat subreddit posts.
