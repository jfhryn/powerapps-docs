---
title: "SdkMessageProcessingStep table/entity reference (Microsoft Dataverse) | Microsoft Docs"
description: "Includes schema information and supported messages for the SdkMessageProcessingStep table/entity."
ms.date: 10/27/2023
ms.service: "powerapps"
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "phecke"
ms.author: "pehecke"
search.audienceType: 
  - developer
---

# SdkMessageProcessingStep table/entity reference

> [!NOTE]
> Unsure about table vs. entity? See [Developers: Understand terminology in Microsoft Dataverse](/powerapps/developer/data-platform/understand-terminology).

Stage in the execution pipeline that a plug-in is to execute.


## Messages

|Message|Web API Operation|SDK class or method|
|-|-|-|
|Create|POST /sdkmessageprocessingsteps<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE /sdkmessageprocessingsteps(*sdkmessageprocessingstepid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Retrieve|GET /sdkmessageprocessingsteps(*sdkmessageprocessingstepid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET /sdkmessageprocessingsteps<br />See [Query Data](/powerapps/developer/data-platform/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|SetState|PATCH /sdkmessageprocessingsteps(*sdkmessageprocessingstepid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH /sdkmessageprocessingsteps(*sdkmessageprocessingstepid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|SdkMessageProcessingSteps|
|DisplayCollectionName|Sdk Message Processing Steps|
|DisplayName|Sdk Message Processing Step|
|EntitySetName|sdkmessageprocessingsteps|
|IsBPFEntity|False|
|LogicalCollectionName|sdkmessageprocessingsteps|
|LogicalName|sdkmessageprocessingstep|
|OwnershipType|OrganizationOwned|
|PrimaryIdAttribute|sdkmessageprocessingstepid|
|PrimaryNameAttribute|name|
|SchemaName|SdkMessageProcessingStep|

<a name="writable-attributes"></a>

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [AsyncAutoDelete](#BKMK_AsyncAutoDelete)
- [CanUseReadOnlyConnection](#BKMK_CanUseReadOnlyConnection)
- [Category](#BKMK_Category)
- [Configuration](#BKMK_Configuration)
- [Description](#BKMK_Description)
- [EnablePluginProfiler](#BKMK_EnablePluginProfiler)
- [EventExpander](#BKMK_EventExpander)
- [EventHandler](#BKMK_EventHandler)
- [EventHandlerTypeCode](#BKMK_EventHandlerTypeCode)
- [FilteringAttributes](#BKMK_FilteringAttributes)
- [FxExpressionId](#BKMK_FxExpressionId)
- [ImpersonatingUserId](#BKMK_ImpersonatingUserId)
- [IntroducedVersion](#BKMK_IntroducedVersion)
- [InvocationSource](#BKMK_InvocationSource)
- [IsCustomizable](#BKMK_IsCustomizable)
- [IsHidden](#BKMK_IsHidden)
- [Mode](#BKMK_Mode)
- [Name](#BKMK_Name)
- [PluginTypeId](#BKMK_PluginTypeId)
- [PowerfxRuleId](#BKMK_PowerfxRuleId)
- [Rank](#BKMK_Rank)
- [RuntimeIntegrationProperties](#BKMK_RuntimeIntegrationProperties)
- [SdkMessageFilterId](#BKMK_SdkMessageFilterId)
- [SdkMessageId](#BKMK_SdkMessageId)
- [SdkMessageProcessingStepId](#BKMK_SdkMessageProcessingStepId)
- [SdkMessageProcessingStepSecureConfigId](#BKMK_SdkMessageProcessingStepSecureConfigId)
- [Stage](#BKMK_Stage)
- [StateCode](#BKMK_StateCode)
- [StatusCode](#BKMK_StatusCode)
- [SupportedDeployment](#BKMK_SupportedDeployment)


### <a name="BKMK_AsyncAutoDelete"></a> AsyncAutoDelete

|Property|Value|
|--------|-----|
|Description|Indicates whether the asynchronous system job is automatically deleted on completion.|
|DisplayName|Asynchronous Automatic Delete|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|asyncautodelete|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### AsyncAutoDelete Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_CanUseReadOnlyConnection"></a> CanUseReadOnlyConnection

|Property|Value|
|--------|-----|
|Description|Identifies whether a SDK Message Processing Step type will be ReadOnly or Read Write. false - ReadWrite, true - ReadOnly |
|DisplayName|Intent|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|canusereadonlyconnection|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### CanUseReadOnlyConnection Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_Category"></a> Category

**Added by**: API messages extension solution Solution

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Category|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|category|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_Configuration"></a> Configuration

|Property|Value|
|--------|-----|
|Description|Step-specific configuration for the plug-in type. Passed to the plug-in constructor at run time.|
|DisplayName|Configuration|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|configuration|
|MaxLength|1073741823|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_Description"></a> Description

|Property|Value|
|--------|-----|
|Description|Description of the SDK message processing step.|
|DisplayName|Description|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|description|
|MaxLength|256|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_EnablePluginProfiler"></a> EnablePluginProfiler

**Added by**: Plugin Infrastructure Extension Solution

|Property|Value|
|--------|-----|
|Description|EnablePluginProfiler|
|DisplayName|EnablePluginProfiler|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|enablepluginprofiler|
|RequiredLevel|None|
|Type|Boolean|

#### EnablePluginProfiler Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Yes||
|0|No||

**DefaultValue**: 0



### <a name="BKMK_EventExpander"></a> EventExpander

|Property|Value|
|--------|-----|
|Description|Configuration for sending pipeline events to the Event Expander service.|
|DisplayName|EventExpander|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|eventexpander|
|MaxLength|1073741823|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_EventHandler"></a> EventHandler

|Property|Value|
|--------|-----|
|Description|Unique identifier of the associated event handler.|
|DisplayName|Event Handler|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|eventhandler|
|RequiredLevel|SystemRequired|
|Targets|plugintype,serviceendpoint|
|Type|Lookup|


### <a name="BKMK_EventHandlerTypeCode"></a> EventHandlerTypeCode

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|eventhandlertypecode|
|RequiredLevel|None|
|Type|EntityName|


### <a name="BKMK_FilteringAttributes"></a> FilteringAttributes

|Property|Value|
|--------|-----|
|Description|Comma-separated list of attributes. If at least one of these attributes is modified, the plug-in should execute.|
|DisplayName|Filtering Attributes|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|filteringattributes|
|MaxLength|100000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_FxExpressionId"></a> FxExpressionId

**Added by**: msft_PowerfxRuleSolution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for fxexpression associated with SdkMessageProcessingStep.|
|DisplayName|fxexpressionid|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|fxexpressionid|
|RequiredLevel|None|
|Targets|fxexpression|
|Type|Lookup|


### <a name="BKMK_ImpersonatingUserId"></a> ImpersonatingUserId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user to impersonate context when step is executed.|
|DisplayName|Impersonating User|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|impersonatinguserid|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_IntroducedVersion"></a> IntroducedVersion

|Property|Value|
|--------|-----|
|Description|Version in which the form is introduced.|
|DisplayName|Introduced Version|
|FormatName|VersionNumber|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|introducedversion|
|MaxLength|48|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_InvocationSource"></a> InvocationSource

|Property|Value|
|--------|-----|
|Description|Identifies if a plug-in should be executed from a parent pipeline, a child pipeline, or both.|
|DisplayName|Invocation Source|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|invocationsource|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### InvocationSource Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|-1|Internal||
|0|Parent||
|1|Child||



### <a name="BKMK_IsCustomizable"></a> IsCustomizable

|Property|Value|
|--------|-----|
|Description|Information that specifies whether this component can be customized.|
|DisplayName|Customizable|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|iscustomizable|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|


### <a name="BKMK_IsHidden"></a> IsHidden

|Property|Value|
|--------|-----|
|Description|Information that specifies whether this component should be hidden.|
|DisplayName|Hidden|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|ishidden|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|


### <a name="BKMK_Mode"></a> Mode

|Property|Value|
|--------|-----|
|Description|Run-time mode of execution, for example, synchronous or asynchronous.|
|DisplayName|Execution Mode|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|mode|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### Mode Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|0|Synchronous||
|1|Asynchronous||



### <a name="BKMK_Name"></a> Name

|Property|Value|
|--------|-----|
|Description|Name of SdkMessage processing step.|
|DisplayName|Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|name|
|MaxLength|256|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_PluginTypeId"></a> PluginTypeId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the plug-in type associated with the step.|
|DisplayName|Plug-In Type|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|plugintypeid|
|RequiredLevel|SystemRequired|
|Targets|sdkmessagefilter|
|Type|Lookup|


### <a name="BKMK_PowerfxRuleId"></a> PowerfxRuleId

**Added by**: msft_PowerfxRuleSolution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier for powerfxrule associated with SdkMessageProcessingStep.|
|DisplayName|powerfxruleid|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|powerfxruleid|
|RequiredLevel|None|
|Targets|powerfxrule|
|Type|Lookup|


### <a name="BKMK_Rank"></a> Rank

|Property|Value|
|--------|-----|
|Description|Processing order within the stage.|
|DisplayName|Execution Order|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|rank|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|SystemRequired|
|Type|Integer|


### <a name="BKMK_RuntimeIntegrationProperties"></a> RuntimeIntegrationProperties

**Added by**: RuntimeIntegration Solution

|Property|Value|
|--------|-----|
|Description|For internal use only. Holds miscellaneous properties related to runtime integration.|
|DisplayName|Runtime Integration Properties|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|runtimeintegrationproperties|
|MaxLength|512|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_SdkMessageFilterId"></a> SdkMessageFilterId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the SDK message filter.|
|DisplayName|SdkMessage Filter|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|sdkmessagefilterid|
|RequiredLevel|None|
|Targets|sdkmessagefilter|
|Type|Lookup|


### <a name="BKMK_SdkMessageId"></a> SdkMessageId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the SDK message.|
|DisplayName|SDK Message|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|sdkmessageid|
|RequiredLevel|SystemRequired|
|Targets|sdkmessage|
|Type|Lookup|


### <a name="BKMK_SdkMessageProcessingStepId"></a> SdkMessageProcessingStepId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the SDK message processing step entity.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|sdkmessageprocessingstepid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_SdkMessageProcessingStepSecureConfigId"></a> SdkMessageProcessingStepSecureConfigId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the Sdk message processing step secure configuration.|
|DisplayName|SDK Message Processing Step Secure Configuration|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|sdkmessageprocessingstepsecureconfigid|
|RequiredLevel|ApplicationRequired|
|Targets|sdkmessageprocessingstepsecureconfig|
|Type|Lookup|


### <a name="BKMK_Stage"></a> Stage

|Property|Value|
|--------|-----|
|Description|Stage in the execution pipeline that the SDK message processing step is in.|
|DisplayName|Execution Stage|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|stage|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### Stage Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|5|Initial Pre-operation (For internal use only)||
|10|Pre-validation||
|15|Internal Pre-operation Before External Plugins (For internal use only)||
|20|Pre-operation||
|25|Internal Pre-operation After External Plugins (For internal use only)||
|30|Main Operation (For internal use only)||
|35|Internal Post-operation Before External Plugins (For internal use only)||
|40|Post-operation||
|45|Internal Post-operation After External Plugins (For internal use only)||
|50|Post-operation (Deprecated)||
|55|Final Post-operation (For internal use only)||
|80|Pre-Commit stage fired before transaction commit (For internal use only)||
|90|Post-Commit stage fired after transaction commit (For internal use only)||



### <a name="BKMK_StateCode"></a> StateCode

|Property|Value|
|--------|-----|
|Description|Status of the SDK message processing step.|
|DisplayName|Status|
|IsValidForCreate|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### StateCode Choices/Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Enabled|1|Enabled|
|1|Disabled|2|Disabled|



### <a name="BKMK_StatusCode"></a> StatusCode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the SDK message processing step.|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statuscode|
|RequiredLevel|None|
|Type|Status|

#### StatusCode Choices/Options

|Value|Label|State|
|-----|-----|-----|
|1|Enabled|0|
|2|Disabled|1|



### <a name="BKMK_SupportedDeployment"></a> SupportedDeployment

|Property|Value|
|--------|-----|
|Description|Deployment that the SDK message processing step should be executed on; server, client, or both.|
|DisplayName|Deployment|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|supporteddeployment|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### SupportedDeployment Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|0|Server Only||
|1|Microsoft Dynamics 365 Client for Outlook Only||
|2|Both||


<a name="read-only-attributes"></a>

## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [ComponentState](#BKMK_ComponentState)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [CustomizationLevel](#BKMK_CustomizationLevel)
- [EventHandlerName](#BKMK_EventHandlerName)
- [FxExpressionIdName](#BKMK_FxExpressionIdName)
- [ImpersonatingUserIdName](#BKMK_ImpersonatingUserIdName)
- [IsManaged](#BKMK_IsManaged)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [OrganizationId](#BKMK_OrganizationId)
- [OverwriteTime](#BKMK_OverwriteTime)
- [PluginTypeIdName](#BKMK_PluginTypeIdName)
- [PowerfxRuleIdName](#BKMK_PowerfxRuleIdName)
- [SdkMessageIdName](#BKMK_SdkMessageIdName)
- [SdkMessageProcessingStepIdUnique](#BKMK_SdkMessageProcessingStepIdUnique)
- [SolutionId](#BKMK_SolutionId)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_ComponentState"></a> ComponentState

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Component State|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|componentstate|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### ComponentState Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|0|Published||
|1|Unpublished||
|2|Deleted||
|3|Deleted Unpublished||



### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the SDK message processing step.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the SDK message processing step was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the sdkmessageprocessingstep.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CustomizationLevel"></a> CustomizationLevel

|Property|Value|
|--------|-----|
|Description|Customization level of the SDK message processing step.|
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|customizationlevel|
|MaxValue|255|
|MinValue|-255|
|RequiredLevel|SystemRequired|
|Type|Integer|


### <a name="BKMK_EventHandlerName"></a> EventHandlerName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|eventhandlername|
|MaxLength|256|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_FxExpressionIdName"></a> FxExpressionIdName

**Added by**: msft_PowerfxRuleSolution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|fxexpressionidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ImpersonatingUserIdName"></a> ImpersonatingUserIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|impersonatinguseridname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_IsManaged"></a> IsManaged

|Property|Value|
|--------|-----|
|Description|Information that specifies whether this component is managed.|
|DisplayName|State|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|ismanaged|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### IsManaged Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Managed||
|0|Unmanaged||

**DefaultValue**: 0



### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who last modified the SDK message processing step.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the SDK message processing step was last modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who last modified the sdkmessageprocessingstep.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OrganizationId"></a> OrganizationId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the organization with which the SDK message processing step is associated.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|organizationid|
|RequiredLevel|SystemRequired|
|Targets|organization|
|Type|Lookup|


### <a name="BKMK_OverwriteTime"></a> OverwriteTime

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|For internal use only.|
|DisplayName|Record Overwrite Time|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|overwritetime|
|RequiredLevel|SystemRequired|
|Type|DateTime|


### <a name="BKMK_PluginTypeIdName"></a> PluginTypeIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|plugintypeidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_PowerfxRuleIdName"></a> PowerfxRuleIdName

**Added by**: msft_PowerfxRuleSolution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|powerfxruleidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_SdkMessageIdName"></a> SdkMessageIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|sdkmessageidname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_SdkMessageProcessingStepIdUnique"></a> SdkMessageProcessingStepIdUnique

|Property|Value|
|--------|-----|
|Description|Unique identifier of the SDK message processing step.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|sdkmessageprocessingstepidunique|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_SolutionId"></a> SolutionId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the associated solution.|
|DisplayName|Solution|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|solutionid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Solution|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|supportingsolutionid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|--------|-----|
|Description|Number that identifies a specific revision of the SDK message processing step. |
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [SdkMessageProcessingStep_AsyncOperations](#BKMK_SdkMessageProcessingStep_AsyncOperations)
- [sdkmessageprocessingstepid_sdkmessageprocessingstepimage](#BKMK_sdkmessageprocessingstepid_sdkmessageprocessingstepimage)


### <a name="BKMK_SdkMessageProcessingStep_AsyncOperations"></a> SdkMessageProcessingStep_AsyncOperations

Same as the [SdkMessageProcessingStep_AsyncOperations](asyncoperation.md#BKMK_SdkMessageProcessingStep_AsyncOperations) many-to-one relationship for the [asyncoperation](asyncoperation.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|owningextensionid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|SdkMessageProcessingStep_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_sdkmessageprocessingstepid_sdkmessageprocessingstepimage"></a> sdkmessageprocessingstepid_sdkmessageprocessingstepimage

Same as the [sdkmessageprocessingstepid_sdkmessageprocessingstepimage](sdkmessageprocessingstepimage.md#BKMK_sdkmessageprocessingstepid_sdkmessageprocessingstepimage) many-to-one relationship for the [sdkmessageprocessingstepimage](sdkmessageprocessingstepimage.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|sdkmessageprocessingstepimage|
|ReferencingAttribute|sdkmessageprocessingstepid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|sdkmessageprocessingstepid_sdkmessageprocessingstepimage|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related table. Listed by **SchemaName**.

- [plugintype_sdkmessageprocessingstep](#BKMK_plugintype_sdkmessageprocessingstep)
- [sdkmessagefilterid_sdkmessageprocessingstep](#BKMK_sdkmessagefilterid_sdkmessageprocessingstep)
- [serviceendpoint_sdkmessageprocessingstep](#BKMK_serviceendpoint_sdkmessageprocessingstep)
- [lk_sdkmessageprocessingstep_createdonbehalfby](#BKMK_lk_sdkmessageprocessingstep_createdonbehalfby)
- [organization_sdkmessageprocessingstep](#BKMK_organization_sdkmessageprocessingstep)
- [impersonatinguserid_sdkmessageprocessingstep](#BKMK_impersonatinguserid_sdkmessageprocessingstep)
- [lk_sdkmessageprocessingstep_modifiedonbehalfby](#BKMK_lk_sdkmessageprocessingstep_modifiedonbehalfby)
- [modifiedby_sdkmessageprocessingstep](#BKMK_modifiedby_sdkmessageprocessingstep)
- [sdkmessageid_sdkmessageprocessingstep](#BKMK_sdkmessageid_sdkmessageprocessingstep)
- [sdkmessageprocessingstepsecureconfigid_sdkmessageprocessingstep](#BKMK_sdkmessageprocessingstepsecureconfigid_sdkmessageprocessingstep)
- [createdby_sdkmessageprocessingstep](#BKMK_createdby_sdkmessageprocessingstep)
- [plugintypeid_sdkmessageprocessingstep](#BKMK_plugintypeid_sdkmessageprocessingstep)
- [fxexpression_sdkmessageprocessingstep](#BKMK_fxexpression_sdkmessageprocessingstep)
- [powerfxrule_sdkmessageprocessingstep](#BKMK_powerfxrule_sdkmessageprocessingstep)


### <a name="BKMK_plugintype_sdkmessageprocessingstep"></a> plugintype_sdkmessageprocessingstep

See the [plugintype_sdkmessageprocessingstep](plugintype.md#BKMK_plugintype_sdkmessageprocessingstep) one-to-many relationship for the [plugintype](plugintype.md) table/entity.

### <a name="BKMK_sdkmessagefilterid_sdkmessageprocessingstep"></a> sdkmessagefilterid_sdkmessageprocessingstep

See the [sdkmessagefilterid_sdkmessageprocessingstep](sdkmessagefilter.md#BKMK_sdkmessagefilterid_sdkmessageprocessingstep) one-to-many relationship for the [sdkmessagefilter](sdkmessagefilter.md) table/entity.

### <a name="BKMK_serviceendpoint_sdkmessageprocessingstep"></a> serviceendpoint_sdkmessageprocessingstep

See the [serviceendpoint_sdkmessageprocessingstep](serviceendpoint.md#BKMK_serviceendpoint_sdkmessageprocessingstep) one-to-many relationship for the [serviceendpoint](serviceendpoint.md) table/entity.

### <a name="BKMK_lk_sdkmessageprocessingstep_createdonbehalfby"></a> lk_sdkmessageprocessingstep_createdonbehalfby

See the [lk_sdkmessageprocessingstep_createdonbehalfby](systemuser.md#BKMK_lk_sdkmessageprocessingstep_createdonbehalfby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_organization_sdkmessageprocessingstep"></a> organization_sdkmessageprocessingstep

See the [organization_sdkmessageprocessingstep](organization.md#BKMK_organization_sdkmessageprocessingstep) one-to-many relationship for the [organization](organization.md) table/entity.

### <a name="BKMK_impersonatinguserid_sdkmessageprocessingstep"></a> impersonatinguserid_sdkmessageprocessingstep

See the [impersonatinguserid_sdkmessageprocessingstep](systemuser.md#BKMK_impersonatinguserid_sdkmessageprocessingstep) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_lk_sdkmessageprocessingstep_modifiedonbehalfby"></a> lk_sdkmessageprocessingstep_modifiedonbehalfby

See the [lk_sdkmessageprocessingstep_modifiedonbehalfby](systemuser.md#BKMK_lk_sdkmessageprocessingstep_modifiedonbehalfby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_modifiedby_sdkmessageprocessingstep"></a> modifiedby_sdkmessageprocessingstep

See the [modifiedby_sdkmessageprocessingstep](systemuser.md#BKMK_modifiedby_sdkmessageprocessingstep) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_sdkmessageid_sdkmessageprocessingstep"></a> sdkmessageid_sdkmessageprocessingstep

See the [sdkmessageid_sdkmessageprocessingstep](sdkmessage.md#BKMK_sdkmessageid_sdkmessageprocessingstep) one-to-many relationship for the [sdkmessage](sdkmessage.md) table/entity.

### <a name="BKMK_sdkmessageprocessingstepsecureconfigid_sdkmessageprocessingstep"></a> sdkmessageprocessingstepsecureconfigid_sdkmessageprocessingstep

See the [sdkmessageprocessingstepsecureconfigid_sdkmessageprocessingstep](sdkmessageprocessingstepsecureconfig.md#BKMK_sdkmessageprocessingstepsecureconfigid_sdkmessageprocessingstep) one-to-many relationship for the [sdkmessageprocessingstepsecureconfig](sdkmessageprocessingstepsecureconfig.md) table/entity.

### <a name="BKMK_createdby_sdkmessageprocessingstep"></a> createdby_sdkmessageprocessingstep

See the [createdby_sdkmessageprocessingstep](systemuser.md#BKMK_createdby_sdkmessageprocessingstep) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_plugintypeid_sdkmessageprocessingstep"></a> plugintypeid_sdkmessageprocessingstep

See the [plugintypeid_sdkmessageprocessingstep](plugintype.md#BKMK_plugintypeid_sdkmessageprocessingstep) one-to-many relationship for the [plugintype](plugintype.md) table/entity.

### <a name="BKMK_fxexpression_sdkmessageprocessingstep"></a> fxexpression_sdkmessageprocessingstep

**Added by**: msft_PowerfxRuleSolution Solution

See the [fxexpression_sdkmessageprocessingstep](fxexpression.md#BKMK_fxexpression_sdkmessageprocessingstep) one-to-many relationship for the [fxexpression](fxexpression.md) table/entity.

### <a name="BKMK_powerfxrule_sdkmessageprocessingstep"></a> powerfxrule_sdkmessageprocessingstep

**Added by**: msft_PowerfxRuleSolution Solution

See the [powerfxrule_sdkmessageprocessingstep](powerfxrule.md#BKMK_powerfxrule_sdkmessageprocessingstep) one-to-many relationship for the [powerfxrule](powerfxrule.md) table/entity.

### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Web API Reference](/dynamics365/customer-engagement/web-api/about)  
<xref href="Microsoft.Dynamics.CRM.sdkmessageprocessingstep?text=sdkmessageprocessingstep EntityType" />