# ![LOGO](logo.png) LUIS Programmatic **flow**ground Connector

## Description

A generated **flow**ground connector for the LUIS Programmatic API (version v2.0).

Generated from: https://api.apis.guru/v2/specs/azure.com/cognitiveservices-LUIS-Programmatic/v2.0/swagger.json<br/>
Generated at: 2019-05-07T17:37:46+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key
## Actions

### Lists all of the user applications.

#### Input Parameters
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Creates a new LUIS app.

### Gets the endpoint URLs for the prebuilt Cortana applications.

### Gets the supported application cultures.

### Gets all the available custom prebuilt domains for all cultures.

### Adds a prebuilt domain along with its models as a new application.

### Gets all the available custom prebuilt domains for a specific culture.

#### Input Parameters
* `culture` - _required_ - Culture.

### Gets the available application domains.

### Imports an application to LUIS, the application's structure should be included in in the request body.

#### Input Parameters
* `appName` - _optional_ - The application name to create. If not specified, the application name will be read from the imported object.

### Gets the application available usage scenarios.

### Deletes an application.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Gets the application info.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Updates the name or description of the application.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Returns the available endpoint deployment regions and URLs.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Removes a user from the allowed list of users to access this LUIS application. Users are removed using their email address.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Gets the list of user emails that have permissions to access your application.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Adds a user to the allowed list of users to access this LUIS application. Users are added using their email address.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Replaces the current users access list with the one sent in the body. If an empty list is sent, all access to other users will be removed.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Publishes a specific version of the application.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Gets the query logs of the past month for the application.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Get the application settings.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Updates the application settings.

#### Input Parameters
* `appId` - _required_ - The application ID.

### Gets the application versions info.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Imports a new version into a LUIS application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _optional_ - The new versionId to import. If not specified, the versionId will be read from the imported object.

### Deletes an application version.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets the version info.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Updates the name or description of the application version.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Creates a new version using the current snapshot of the selected application version.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets information about the closedlist models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds a closed list model to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes a closed list model from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list model ID.

### Gets information of a closed list model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list model ID.

### Adds a batch of sublists to an existing closedlist.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list model ID.

### Updates the closed list model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list model ID.

### Adds a list to an existing closed list.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list entity extractor ID.

### Deletes a sublist of a specific closed list model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list entity extractor ID.
* `subListId` - _required_ - The sublist ID.

### Updates one of the closed list's sublists.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `clEntityId` - _required_ - The closed list entity extractor ID.
* `subListId` - _required_ - The sublist ID.

### Gets information about the composite entity models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds a composite entity extractor to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes a composite entity extractor from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `cEntityId` - _required_ - The composite entity extractor ID.

### Gets information about the composite entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `cEntityId` - _required_ - The composite entity extractor ID.

### Updates the composite entity extractor.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `cEntityId` - _required_ - The composite entity extractor ID.

### Creates a single child in an existing composite entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `cEntityId` - _required_ - The composite entity extractor ID.

### Deletes a composite entity extractor child from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `cEntityId` - _required_ - The composite entity extractor ID.
* `cChildId` - _required_ - The hierarchical entity extractor child ID.

### Adds a customizable prebuilt domain along with all of its models to this application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes a prebuilt domain's models from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `domainName` - _required_ - Domain name.

### Gets all custom prebuilt entities information of this application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Adds a custom prebuilt entity model to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets custom prebuilt intents information of this application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Adds a custom prebuilt intent model to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets all custom prebuilt models information of this application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets information about the entity models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds an entity extractor to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes an entity extractor from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `entityId` - _required_ - The entity extractor ID.

### Gets information about the entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `entityId` - _required_ - The entity extractor ID.

### Updates the name of an entity extractor.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `entityId` - _required_ - The entity extractor ID.

### Get suggestion examples that would improve the accuracy of the entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `entityId` - _required_ - The target entity extractor model to enhance.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds a labeled example to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Returns examples to be reviewed.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds a batch of labeled examples to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes the labeled example with the specified ID.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `exampleId` - _required_ - The example ID.

### Exports a LUIS application to JSON format.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets all the extraction features for the specified application version.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Gets information about the hierarchical entity models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds a hierarchical entity extractor to the application version.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes a hierarchical entity extractor from the application version.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.

### Gets information about the hierarchical entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.

### Updates the name and children of a hierarchical entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.

### Creates a single child in an existing hierarchical entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.

### Deletes a hierarchical entity extractor child from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.
* `hChildId` - _required_ - The hierarchical entity extractor child ID.

### Gets information about the hierarchical entity child model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.
* `hChildId` - _required_ - The hierarchical entity extractor child ID.

### Renames a single child in an existing hierarchical entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `hEntityId` - _required_ - The hierarchical entity extractor ID.
* `hChildId` - _required_ - The hierarchical entity extractor child ID.

### Gets information about the intent models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds an intent classifier to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes an intent classifier from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `intentId` - _required_ - The intent classifier ID.
* `deleteUtterances` - _optional_ - Also delete the intent's utterances (true). Or move the utterances to the None intent (false - the default value).

### Gets information about the intent model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `intentId` - _required_ - The intent classifier ID.

### Updates the name of an intent classifier.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `intentId` - _required_ - The intent classifier ID.

### Suggests examples that would improve the accuracy of the intent model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `intentId` - _required_ - The intent classifier ID.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Gets all the available prebuilt entity extractors for the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets information about the application version models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### [DEPRECATED NOTICE: This operation will soon be removed] Gets all the pattern features.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### [DEPRECATED NOTICE: This operation will soon be removed] Creates a new pattern feature.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### [DEPRECATED NOTICE: This operation will soon be removed] Deletes a pattern feature.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `patternId` - _required_ - The pattern feature ID.

### [DEPRECATED NOTICE: This operation will soon be removed] Gets the specified pattern feature's info.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `patternId` - _required_ - The pattern feature ID.

### [DEPRECATED NOTICE: This operation will soon be removed] Updates the pattern, the name and the state of the pattern feature.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `patternId` - _required_ - The pattern feature ID.

### Gets all the phraselist features.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Creates a new phraselist feature.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes a phraselist feature.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `phraselistId` - _required_ - The ID of the feature to be deleted.

### Gets phraselist feature info.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `phraselistId` - _required_ - The ID of the feature to be retrieved.

### Updates the phrases, the state and the name of the phraselist feature.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `phraselistId` - _required_ - The ID of the feature to be updated.

### Gets information about the prebuilt entity models.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `skip` - _optional_ - The number of entries to skip. Default value is 0.
* `take` - _optional_ - The number of entries to return. Maximum page size is 500. Default is 100.

### Adds a list of prebuilt entity extractors to the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Deletes a prebuilt entity extractor from the application.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `prebuiltId` - _required_ - The prebuilt entity extractor ID.

### Gets information about the prebuilt entity model.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.
* `prebuiltId` - _required_ - The prebuilt entity extractor ID.

### Deleted an unlabelled utterance.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Gets the training status of all models (intents and entities) for the specified LUIS app. You must call the train API to train the LUIS app before you call this API to get training status. "appID" specifies the LUIS app ID. "versionId" specifies the version number of the LUIS app. For example, "0.1".

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

### Sends a training request for a version of a specified LUIS app. This POST request initiates a request asynchronously. To determine whether the training request is successful, submit a GET request to get training status. Note: The application version is not fully trained unless all the models (intents and entities) are trained successfully or are up to date. To verify training success, get the training status at least once after training is complete.

#### Input Parameters
* `appId` - _required_ - The application ID.
* `versionId` - _required_ - The version ID.

## License

**flow**ground :- Telekom iPaaS / azure-com-cognitiveservices-luis-programmatic-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
