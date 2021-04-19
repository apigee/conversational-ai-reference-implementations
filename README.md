# Conversational AI Reference Implementations

This project contains Apigee proxy and shared flow reference implementations to
enable integration of Google Cloud's Dialogflow product with mock backend
systems via Apigee using the `Parse Dialogflow Request` and `Set Dialogflow
Response` policies.

**Note** The reference implementations provided in this project will only work
with Apigee X version 1.5 or later.

## Categories

The reference implementation contains Apigee proxy and shared flow files for
common use-cases in the following industry verticals: 1. Telecommunications 2.
Financial Services 3. Vehicle Insurance

Each of these industry vertical sections contains further sub-categories of
reference implementations grouped together based on common use-cases such as
*account management*, *plan management*, etc.

## Usage

The reference implementations in this project are released as both individual
files and a collection of zip files. The zip files are provided for easy import
into Apigee. Alternatively, you could modify any of the reference implementation
files based on your particular requirements, create Apigee bundle zip files and
import into Apigee.

### Proxies and Shared Flows

Each sub-category under each industry vertical is released as a set of 4 files:
1. Dialogflow Webhook adapter proxy 2. Dialogflow Webhook adapter shared flow 3.
Southbound mock API proxy 4. Southbound mock API shared flow

To use any particular sub-category of a vertical industry you will have to
import all 4 bundled zip files relevant to that sub-category into Apigee. *Note*
that all the 4 bundles must be imported into the same Apigee org.

Refer
[here](https://cloud.google.com/apigee/docs/api-platform/fundamentals/download-api-proxies#upload)
for instructions on how to import a proxy/shared flow bundle into Apigee.

## Folder Structure

All the reference implementation files are released in two top-level folders
named `southbound-api-mocks` and `webhook-adapters`. Within each of these
folders, there are 2 sub-folders named `proxies` and `shared-flows`. Within each
of these folders is one folder per supported industry vertical. Sub-categories
are available as sub-folders within each industry vertical's folder.

## Support

Issues filed on Github are not subject to service level agreements (SLAs) and
responses should be assumed to be on an ad-hoc volunteer basis. The
[Apigee community board](https://community.apigee.com/) is recommended as for
community support and is regularly checked by Apigee experts.

Apigee customers should use
[formal support channels](https://cloud.google.com/apigee/support).

## Contributing

Contributions are welcome! Please see [CONTRIBUTING](CONTRIBUTING.md) for notes
on how to contribute to this project.

