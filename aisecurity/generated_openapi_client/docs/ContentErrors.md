# ContentErrors

Errors information for prompt and response detection services

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content_type** | [**ContentErrorType**](ContentErrorType.md) |  | [optional] 
**feature** | [**DetectionServiceName**](DetectionServiceName.md) |  | [optional] 
**status** | [**ErrorStatus**](ErrorStatus.md) |  | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.content_errors import ContentErrors

# TODO update the JSON string below
json = "{}"
# create an instance of ContentErrors from a JSON string
content_errors_instance = ContentErrors.from_json(json)
# print the JSON string representation of the object
print(ContentErrors.to_json())

# convert the object into a dict
content_errors_dict = content_errors_instance.to_dict()
# create an instance of ContentErrors from a dict
content_errors_from_dict = ContentErrors.from_dict(content_errors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


