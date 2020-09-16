# **RestOperation**
**namespace:** laplacian.arch.api.service

rest_operation



---

## Properties

### method: `String`
The method of this rest_operation.

### path: `String`
The path of this rest_operation.

### name: `String`
The name of this rest_operation.
- **Attributes:** *PK*

## Relationships

### path_parameters: `List<RestRequestParameter>`
path_parameters
- **Cardinality:** `*`

### query_parameters: `List<RestRequestParameter>`
query_parameters
- **Cardinality:** `*`

### rest_resource: `RestResource`
rest_resource
- **Cardinality:** `1`