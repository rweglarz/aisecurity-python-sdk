# ScanContent


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prompt** | **str** | The prompt content that you want to scan | [optional] 
**response** | **str** | The response content that you want to scan | [optional] 
**code_prompt** | **str** | Code snippet extracted from Prompt content that you want to scan | [optional] 
**code_response** | **str** | Code snippet extracted from Response content that you want to scan | [optional] 
**context** | **str** | The data context for contextual grounding | [optional] 
**tool_event** | [**ToolEvent**](ToolEvent.md) |  | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.scan_content import ScanContent

# TODO update the JSON string below
json = "{}"
# create an instance of ScanContent from a JSON string
scan_content_instance = ScanContent.from_json(json)
# print the JSON string representation of the object
print(ScanContent.to_json())

# convert the object into a dict
scan_content_dict = scan_content_instance.to_dict()
# create an instance of ScanContent from a dict
scan_content_from_dict = ScanContent.from_dict(scan_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


