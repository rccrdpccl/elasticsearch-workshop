### Mapping

We have inserted a document without declaring a mapping, therefore Elasticsearch has created one for us. But how good is it?

```GET /movies/_mappings```

How can the [mapping](https://www.elastic.co/guide/en/elasticsearch/reference/current/mapping.html) be improved? Modify the file ```mapping.json``` and
redefine the new mapping. If you are unsure, do not worry, we can always change it later (although we will need to re-index the data).
