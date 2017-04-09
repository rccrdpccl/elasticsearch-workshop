### Bulk Data

Creating documents one by one it's an expensive and boring operation. In order to load a lot of data at once, Elasticsearch provide us with a nice [Bulk API](https://www.elastic.co/guide/en/elasticsearch/reference/current/docs-bulk.html).

For the following exercises, we are going to get a [Movie Lens](https://movielens.org/) dataset (movies).

Unfortunately the dataset is not in a Elasticsearch-friendly, so we need to parse the data before being able to load it. In order to get the dataset, run the ```getDataset``` script. Then, to generate the needed ```bulk.json``` file, use the utility script ```bulkData```.

Use the Bulk Api to load a nice dataset in memory, so that we can start playing.
