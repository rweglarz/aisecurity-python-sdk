# DlpSnippetObject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meta** | [**DlpSnippetMeta**](DlpSnippetMeta.md) |  | 
**snippets** | **List[str]** | Up to 10 content snippets; each item must be &lt;&#x3D; 1000 characters. | 

## Example

```python
from aisecurity.generated_openapi_client.models.dlp_snippet_object import DlpSnippetObject

# TODO update the JSON string below
json = "{}"
# create an instance of DlpSnippetObject from a JSON string
dlp_snippet_object_instance = DlpSnippetObject.from_json(json)
# print the JSON string representation of the object
print(DlpSnippetObject.to_json())

# convert the object into a dict
dlp_snippet_object_dict = dlp_snippet_object_instance.to_dict()
# create an instance of DlpSnippetObject from a dict
dlp_snippet_object_from_dict = DlpSnippetObject.from_dict(dlp_snippet_object_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


