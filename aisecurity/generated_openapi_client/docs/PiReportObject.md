# PiReportObject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**verdict** | **str** | Detection service verdict such as \&quot;malicious\&quot; or \&quot;benign\&quot; | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.pi_report_object import PiReportObject

# TODO update the JSON string below
json = "{}"
# create an instance of PiReportObject from a JSON string
pi_report_object_instance = PiReportObject.from_json(json)
# print the JSON string representation of the object
print(PiReportObject.to_json())

# convert the object into a dict
pi_report_object_dict = pi_report_object_instance.to_dict()
# create an instance of PiReportObject from a dict
pi_report_object_from_dict = PiReportObject.from_dict(pi_report_object_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


