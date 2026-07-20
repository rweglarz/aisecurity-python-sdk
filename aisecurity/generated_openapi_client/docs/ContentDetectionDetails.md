# ContentDetectionDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**topic_guardrails_details** | [**TopicGuardRails**](TopicGuardRails.md) |  | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.content_detection_details import ContentDetectionDetails

# TODO update the JSON string below
json = "{}"
# create an instance of ContentDetectionDetails from a JSON string
content_detection_details_instance = ContentDetectionDetails.from_json(json)
# print the JSON string representation of the object
print(ContentDetectionDetails.to_json())

# convert the object into a dict
content_detection_details_dict = content_detection_details_instance.to_dict()
# create an instance of ContentDetectionDetails from a dict
content_detection_details_from_dict = ContentDetectionDetails.from_dict(content_detection_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


