# B2B Integration Factory - Communication Sender Flows 

\| [Recipes by Topic](../../readme.md ) \| [Recipes by Author](../../author.md ) \| [Request Enhancement](https://github.com/SAP-samples/cloud-integration-flow/issues/new?assignees=&labels=Recipe%20Fix,enhancement&template=recipe-request.md&title=Improve%20[B2B%20Integration%20Factory]%20Communication%20Sender%20Flows) \| [Report a bug](https://github.com/SAP-samples/cloud-integration-flow/issues/new?assignees=&labels=Recipe%20Fix,bug&template=bug_report.md&title=Issue%20with%20[B2B%20Integration%20Factory]%20Communication%20Sender%20Flows)\| [Fix documentation](https://github.com/SAP-samples/cloud-integration-flow/issues/new?assignees=&labels=Recipe%20Fix,documentation&template=bug_report.md&title=Docu%20fix%20[B2B%20Integration%20Factory]%20Communication%20Sender%20Flows) \| 

 ![SAP Business Accelerator Hub](https://github.com/SAPAPIBusinessHub.png?size=50 ) | [SAP Business Accelerator Hub](https://api.sap.com/allcommunity) | 
 ----|----| 

This package includes all MS3-related sender communication flows for TPM B2B, provided by SAP. These sender flows connect to Step 1b: 'Sender Interchange Header Extraction Flow'.

<p>This integration package provides all MS3 related sender communication flows for the TPM B2B communication, which are provided by SAP.</p>
<p>These sender communication flows are connected to the Step 1b "Step 1b - Sender Interchange Header Extraction Flow".&nbsp;</p>

[Download the integration package](B2BIntegrationFactoryCommunicationSenderFlows.zip)\
[View package on the SAP Business Accelerator Hub](https://api.sap.com/package/B2BIntegrationFactoryCommunicationSenderFlows)\
[View documentation, page 14](../b2bintegrationfactorycloudintegrationtradingpartnermanagement/B2B_Integration_Factory_TPM_Integration_Packages.pdf)\
[View high level effort](../b2bintegrationfactorycloudintegrationtradingpartnermanagement/effort.md)
## Integration flows
### Step 1a - SOAP Sender 
Receives messages via SOAP protocol, identifies type system and writes payload and header parameters into message queue \
 ![input-image](Step_1a_-_SOAP_Sender.png)
### Step 1a - AS2 Sender 
Receives messages via AS2 protocol, identifies type system and writes payload and header parameters into message queue \
 ![input-image](Step_1a_-_AS2_Sender.png)
### Step 1a - IDOC Sender 
Receives messages via IDoc protocol, identifies type system and writes payload and header parameters into message queue \
 ![input-image](Step_1a_-_IDOC_Sender.png)
### Step 1a - SFTP Sender 
Receives messages via SFTP protocol, identifies type system and writes payload and header parameters into message queue \
 ![input-image](Step_1a_-_SFTP_Sender.png)
### Step 1a - B2B Simulation Sender 
Receives messages from sender via HTTP/HTTPS protocol and hands over to step 1b flow. \
 ![input-image](Step_1a_-_B2B_Simulation_Sender.png)
### Step 1a - TEMPLATE Sender 
Receives messages via any supported communication protocol, identifies type system and writes payload and header parameters into message queue \
 ![input-image](Step_1a_-_TEMPLATE_Sender.png)
### Step 1a - HTTP Sender 
Receives messages from sender via HTTP/HTTPS protocol and provides a response in synchronous call, if required. \
 ![input-image](Step_1a_-_HTTP_Sender.png)