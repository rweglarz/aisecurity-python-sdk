# ToxicContentDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**toxic_categories** | **List[str]** | Indicates the list of topics that is detected | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.toxic_content_details import ToxicContentDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ToxicContentDetails from a JSON string
toxic_content_details_instance = ToxicContentDetails.from_json(json)
# print the JSON string representation of the object
print(ToxicContentDetails.to_json())

# convert the object into a dict
toxic_content_details_dict = toxic_content_details_instance.to_dict()
# create an instance of ToxicContentDetails from a dict
toxic_content_details_from_dict = ToxicContentDetails.from_dict(toxic_content_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


