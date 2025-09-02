
<img src="/profile/img/openmbee-logo.svg" width="400" alt="OpenMBEE" />



## Welcome to OpenMBEE
OpenMBEE (Open Model Based Engineering Environment) is an open source collaborative engineering system. It enables engineers to work in the language of their choice and easily share and document their work across other tools.

## OpenMBEE Architectures
### Flexo
The predecessor architecture, Execubots, stores model elements as objects in a document-oriented database, whereas Flexo provides a graph-native approach to storing and diff'ing models. Models in Flexo are not limited to enterprise model development platforms. Flexo can store anything expressed as RDF.

Relevant Repositories (repositories relevant to this architecture are prefixed with "flexo-"):  
- [flexo-mms-deployment](https://github.com/Open-MBEE/flexo-mms-deployment) - examples for setting up Flexo-mms with docker compose or k8s
- [flexo-mms-layer1-service](https://github.com/Open-MBEE/flexo-mms-layer1-service) - Root component of the Flexo MMS stack, allowing for version-controlled CRUD operations of RDF models
- [flexo-mms-sysmlv2](https://github.com/Open-MBEE/flexo-mms-sysmlv2) - SysMLv2 API service using flexo layer1 as a backend
- [openapi-graph-extractor](https://github.com/Open-MBEE/openapi-graph-extractor) - Converts well-defined JSON data to RDF by consuming an OpenAPI document 

### Execubots
The Execubots architecture allows Systems Engineers to develop models in their enterprise model development platform and publish aspects of the model to the web.  

Relevant Repositories (repositories relevant to this architecture are prefixed with "exec-"):
- [Model Management System](https://github.com/Open-MBEE/exec-mms) - Management and version control for SysML models
- [Cameo Model Development Kit](https://github.com/Open-MBEE/exec-cameo-mdk) - Cameo Systems Modeler plugin for defining views for View Editor
- [View Editor](https://github.com/Open-MBEE/exec-ve) - Interact with SysML models within a web-based environment

## Example Models
SysML v1 example models.
- [TMT-SysML-Model](https://github.com/Open-MBEE/TMT-SysML-Model) - Thirty Meter Telescope System Model in SysML 
- [OpenSE-Cookbook](https://github.com/Open-MBEE/OpenSE-Cookbook) - Collection of examples and best practices



## Contributing 
- [General Contributing Guidelines](https://www.openmbee.org/contribute.html#)
- [License](https://www.openmbee.org/licenses.html#)


