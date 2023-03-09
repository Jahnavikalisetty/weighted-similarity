# weighted-similarity
Get the most similar tags/categories which are weighted

data is included where each userid is given certain categories and then weights corresponding to those categories

When weights are given cosine similarity is not suitable as weights gets cancelled, so we use the eucledian distance for the same.
for example
a user "A" buys 100 guavas 100 apples 100 oranges and another user "B" buys 10 apples , 10 guavas, 10 oranges and another user "C" buys 100 apples, 100 guavas and 100 oranges
In cosine similarity we get all of them as similar where as using eucledian similarity we get "A", "C" as more similar than "A", "B"

Application : to recommend better similar e-commerce products, similar users, etc.,
