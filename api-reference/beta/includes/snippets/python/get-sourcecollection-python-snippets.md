---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = SourceCollectionRequestBuilder.SourceCollectionRequestBuilderGetQueryParameters(
		expand = ["addToReviewSetOperation","custodianSources","lastEstimateStatisticsOperation"],
)

request_configuration = SourceCollectionRequestBuilder.SourceCollectionRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.compliance.ediscovery.cases.by_case_id('case-id').source_collections.by_source_collection_id('sourceCollection-id').get(request_configuration = request_configuration)


```