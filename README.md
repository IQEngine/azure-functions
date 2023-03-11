Code deployed as Azure Functions to run the detector backend and thumbnail generator (blob storage triggered)

To run FastAPI functions locally for testing:

```
uvicorn __init__:app --reload
```

Remember you have to go into the function apps Configuration and under Application Settings there needs to be one for AzureWebJobsStorage which is the storage account connection string, as well as MongoDBConnString