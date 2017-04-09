### Insert document

To insert a document, we can perform a PUT HTTP request against the coordinator node, with the document as payload.

```
PUT /<index>/<type>/<id>
{
   "foo": "bar"
}
```

Insert the document contained in ```document.json``` in an index ```movies``` with type ```movie```. Remember to use the ID contained in the document as ID, for easy retrieval.

Now check that the document has been stored correctly with the [GET Api](https://www.elastic.co/guide/en/elasticsearch/reference/current/docs-get.html).

