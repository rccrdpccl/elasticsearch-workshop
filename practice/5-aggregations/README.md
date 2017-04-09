### Aggregations

Now we can do some interesting things with the data we have just explored: [aggregations](https://www.elastic.co/guide/en/elasticsearch/reference/current/search-aggregations.html).

Some interesting aggregations could be:
- Get how many movies have been released each year.
- How many movies per genre?
- What are the main other genres for Sci-Fi movies?
- When searching for "Rocky", what is the genre distribution of the results? And what years?

Aggregations can be very powerful: think for example of a "filter" feature in search results. When we search for "Rocky", we could display how many results will be left if we additionally filter by year, or by genre.
