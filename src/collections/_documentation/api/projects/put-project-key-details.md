---
# This file is automatically generated from the API using `api-docs/generate.py`
# Do not manually this file.
{
  "api_path": "/api/0/projects/{organization_slug}/{project_slug}/keys/{key_id}/", 
  "authentication": "required", 
  "description": "Update a client key.  This can be used to rename a key.", 
  "example_request": "", 
  "example_response": "", 
  "method": "PUT", 
  "parameters": [
    {
      "description": "the new name for the client key.", 
      "name": "name", 
      "type": "string"
    }
  ], 
  "path_parameters": [
    {
      "description": "the slug of the organization the client keys belong to.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the slug of the project the client keys belong to.", 
      "name": "project_slug", 
      "type": "string"
    }, 
    {
      "description": "the ID of the key to update.", 
      "name": "key_id", 
      "type": "string"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 14, 
  "title": "Update a Client Key", 
  "warning": null
}
---
