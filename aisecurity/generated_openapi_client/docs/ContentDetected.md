# ContentDetected


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**agent** | **bool** | Indicates whether content contains any Agent related threats | [optional] 
**db_security** | **bool** | Indicates whether content contains any database security threats | [optional] 
**dlp** | **bool** | Indicates whether content contains any sensitive information | [optional] 
**injection** | **bool** | Indicates whether content contains any injection threats | [optional] 
**malicious_code** | **bool** | Indicates whether content contains any malicious code | [optional] 
**topic_violation** | **bool** | Indicates whether content violates topic guardrails | [optional] 
**toxic_content** | **bool** | Indicates whether content contains any harmful content | [optional] 
**url_cats** | **bool** | Indicates whether content contains any malicious URLs | [optional] 

## Example

```python
from aisecurity.generated_openapi_client.models.content_detected import ContentDetected

# TODO update the JSON string below
json = "{}"
# create an instance of ContentDetected from a JSON string
content_detected_instance = ContentDetected.from_json(json)
# print the JSON string representation of the object
print(ContentDetected.to_json())

# convert the object into a dict
content_detected_dict = content_detected_instance.to_dict()
# create an instance of ContentDetected from a dict
content_detected_from_dict = ContentDetected.from_dict(content_detected_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


