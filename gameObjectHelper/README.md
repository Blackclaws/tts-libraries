This is a little helper for handling Game Objects. It allows the retrieval of game objects by name if their GUIDs are in any of the configured data stores.

You configure the data stores by simply doing
```
gameObjectGuidStores.storeName = { tableContent }
or
gameObjectGuidStores.storeName = someTableWithNameGuidMapping
```

the expected mappings are of the sort

```
guidStore = {
  objectName = "objectGuid",
  secondName = "secondGuid",
  ...
}
```
