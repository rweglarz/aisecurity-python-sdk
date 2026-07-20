# DlpSnippetMeta


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data_pattern** | **str** | pattern_id (DLP response snippets map key) | 
**confidence_level** | **str** |  | 
**data_pattern_type** | **str** | proximity keyword (first one if any) | [optional] 
**occurrence** | **int** |  | 

## Example

```python
from aisecurity.generated_openapi_client.models.dlp_snippet_meta import DlpSnippetMeta

# TODO update the JSON string below
json = "{}"
# create an instance of DlpSnippetMeta from a JSON string
dlp_snippet_meta_instance = DlpSnippetMeta.from_json(json)
# print the JSON string representation of the object
print(DlpSnippetMeta.to_json())

# convert the object into a dict
dlp_snippet_meta_dict = dlp_snippet_meta_instance.to_dict()
# create an instance of DlpSnippetMeta from a dict
dlp_snippet_meta_from_dict = DlpSnippetMeta.from_dict(dlp_snippet_meta_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


