# TruncationInfoObject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**payload_truncated** | **bool** | Whether the payload was truncated before code extraction | [optional] 
**original_payload_length** | **int** | Original payload length in characters before truncation | [optional] 
**truncated_payload_length** | **int** | Payload length in characters after truncation | [optional] 
**truncation_mode** | **str** | Truncation mode applied | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.truncation_info_object import TruncationInfoObject

# TODO update the JSON string below
json = "{}"
# create an instance of TruncationInfoObject from a JSON string
truncation_info_object_instance = TruncationInfoObject.from_json(json)
# print the JSON string representation of the object
print(TruncationInfoObject.to_json())

# convert the object into a dict
truncation_info_object_dict = truncation_info_object_instance.to_dict()
# create an instance of TruncationInfoObject from a dict
truncation_info_object_from_dict = TruncationInfoObject.from_dict(truncation_info_object_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


