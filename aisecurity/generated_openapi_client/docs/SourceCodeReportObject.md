# SourceCodeReportObject


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**verdict** | **str** | Detection service verdict such as \&quot;malicious\&quot; or \&quot;benign\&quot; | [optional] 
**confidence_score** | **float** | Confidence score of the source code detection | [optional] 
**code_present** | **bool** | Indicates whether source code was detected in the content | [optional] 
**category** | **str** | Category of the detected source code (e.g., programming language) | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.source_code_report_object import SourceCodeReportObject

# TODO update the JSON string below
json = "{}"
# create an instance of SourceCodeReportObject from a JSON string
source_code_report_object_instance = SourceCodeReportObject.from_json(json)
# print the JSON string representation of the object
print(SourceCodeReportObject.to_json())

# convert the object into a dict
source_code_report_object_dict = source_code_report_object_instance.to_dict()
# create an instance of SourceCodeReportObject from a dict
source_code_report_object_from_dict = SourceCodeReportObject.from_dict(source_code_report_object_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


