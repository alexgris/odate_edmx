# odate_edmx
$metadata of odata v2 service TRUI_TU_CFP_MAINT_O2


<edmx:Edmx xmlns:edmx="http://schemas.microsoft.com/ado/2007/06/edmx" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:sap="http://www.sap.com/Protocols/SAPData" Version="1.0">
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_AGGREGATION',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="Org.OData.Aggregation.V1" Alias="Aggregation"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_ANALYTICS',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.Analytics.v1" Alias="Analytics"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_CAPABILITIES',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="Org.OData.Capabilities.V1" Alias="Capabilities"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_CODELIST',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.CodeList.v1" Alias="SAP__CodeList"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_COMMON',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.Common.v1" Alias="Common"/>
<edmx:Include Namespace="com.sap.vocabularies.Common.v1" Alias="SAP__common"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_COMMUNICATION',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.Communication.v1" Alias="Communication"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_CORE',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="Org.OData.Core.V1" Alias="SAP__core"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_MEASURES',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="Org.OData.Measures.V1" Alias="Measures"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_PDF',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.PDF.v1" Alias="SAP__PDF"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_PERSONALDATA',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.PersonalData.v1" Alias="PersonalData"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_UI',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="com.sap.vocabularies.UI.v1" Alias="UI"/>
</edmx:Reference>
<edmx:Reference xmlns:edmx="http://docs.oasis-open.org/odata/ns/edmx" Uri="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/iwfnd/catalogservice;v=2/Vocabularies(TechnicalName='%2FIWBEP%2FVOC_VALIDATION',Version='0001',SAP__Origin='')/$value">
<edmx:Include Namespace="Org.OData.Validation.V1" Alias="Validation"/>
</edmx:Reference>
<edmx:DataServices m:DataServiceVersion="2.0">
<Schema xmlns="http://schemas.microsoft.com/ado/2008/09/edm" Namespace="cds_xbtlxtrui_tu_cfp_maint" xml:lang="en" sap:schema-version="1">
<EntityType Name="xBTLxTRL_CONSUM_UNIT_VHType" sap:label="Value Help for Consumption Unit" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="UnitOfMeasure"/>
</Key>
<Property Name="UnitOfMeasure" Type="Edm.String" Nullable="false" MaxLength="3" sap:text="UnitOfMeasure_Text" sap:label="Unit of Measure" sap:semantics="unit-of-measure"/>
<Property Name="UnitOfMeasure_Text" Type="Edm.String" MaxLength="30" sap:label="Meas. Unit Text" sap:quickinfo="Unit of Measurement Text (Maximum 30 Characters)" sap:creatable="false" sap:updatable="false"/>
<Property Name="UnitOfMeasureDimension" Type="Edm.String" MaxLength="6" sap:display-format="UpperCase" sap:label="Dimension" sap:quickinfo="Dimension key"/>
</EntityType>
<EntityType Name="xBTLxTRL_EMISSION_CLASS_VHType" sap:label="Value Help for Emission Class" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="SAPDataDictionaryDomain"/>
<PropertyRef Name="DomainValue"/>
<PropertyRef Name="DomainActivationState"/>
<PropertyRef Name="DomainValuePosition"/>
<PropertyRef Name="DomainVersion"/>
</Key>
<Property Name="SAPDataDictionaryDomain" Type="Edm.String" Nullable="false" MaxLength="30" sap:display-format="UpperCase" sap:label="Domain name"/>
<Property Name="DomainValue" Type="Edm.String" Nullable="false" MaxLength="10" sap:display-format="UpperCase" sap:text="DomainValue_Text" sap:label="Lower Value" sap:quickinfo="Values for Domains: Single Value/Lower Limit"/>
<Property Name="DomainValue_Text" Type="Edm.String" MaxLength="60" sap:label="Short Descript." sap:quickinfo="Short Text for Fixed Values" sap:creatable="false" sap:updatable="false"/>
<Property Name="DomainActivationState" Type="Edm.String" Nullable="false" MaxLength="1" sap:display-format="UpperCase" sap:label="Activation Status" sap:quickinfo="Activation State of Repository Object"/>
<Property Name="DomainValuePosition" Type="Edm.String" Nullable="false" MaxLength="4" sap:display-format="NonNegative" sap:label="Value key" sap:quickinfo="Domain value key"/>
<Property Name="DomainVersion" Type="Edm.String" Nullable="false" MaxLength="4" sap:display-format="NonNegative" sap:label="Version" sap:quickinfo="Version of the entry (not used)"/>
</EntityType>
<EntityType Name="xBTLxTRL_EMISSION_TECH_VHType" sap:label="Value Help for Emission Technology" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="SAPDataDictionaryDomain"/>
<PropertyRef Name="DomainValue"/>
<PropertyRef Name="DomainActivationState"/>
<PropertyRef Name="DomainValuePosition"/>
<PropertyRef Name="DomainVersion"/>
</Key>
<Property Name="SAPDataDictionaryDomain" Type="Edm.String" Nullable="false" MaxLength="30" sap:display-format="UpperCase" sap:label="Domain name"/>
<Property Name="DomainValue" Type="Edm.String" Nullable="false" MaxLength="10" sap:display-format="UpperCase" sap:text="DomainValue_Text" sap:label="Lower Value" sap:quickinfo="Values for Domains: Single Value/Lower Limit"/>
<Property Name="DomainValue_Text" Type="Edm.String" MaxLength="60" sap:label="Short Descript." sap:quickinfo="Short Text for Fixed Values" sap:creatable="false" sap:updatable="false"/>
<Property Name="DomainActivationState" Type="Edm.String" Nullable="false" MaxLength="1" sap:display-format="UpperCase" sap:label="Activation Status" sap:quickinfo="Activation State of Repository Object"/>
<Property Name="DomainValuePosition" Type="Edm.String" Nullable="false" MaxLength="4" sap:display-format="NonNegative" sap:label="Value key" sap:quickinfo="Domain value key"/>
<Property Name="DomainVersion" Type="Edm.String" Nullable="false" MaxLength="4" sap:display-format="NonNegative" sap:label="Version" sap:quickinfo="Version of the entry (not used)"/>
</EntityType>
<EntityType Name="xBTLxTRL_ENGINE_CAP_UNIT_VHType" sap:label="Value Help for Engine Capacity Unit" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="UnitOfMeasure"/>
</Key>
<Property Name="UnitOfMeasure" Type="Edm.String" Nullable="false" MaxLength="3" sap:text="UnitOfMeasure_Text" sap:label="Unit of Measure" sap:semantics="unit-of-measure"/>
<Property Name="UnitOfMeasure_Text" Type="Edm.String" MaxLength="30" sap:label="Meas. Unit Text" sap:quickinfo="Unit of Measurement Text (Maximum 30 Characters)" sap:creatable="false" sap:updatable="false"/>
<Property Name="UnitOfMeasureDimension" Type="Edm.String" MaxLength="6" sap:display-format="UpperCase" sap:label="Dimension" sap:quickinfo="Dimension key"/>
</EntityType>
<EntityType Name="xBTLxTRL_PARTICLE_FILTER_VHType" sap:label="Value Help for Particle Filter" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="SAPDataDictionaryDomain"/>
<PropertyRef Name="DomainValue"/>
<PropertyRef Name="DomainActivationState"/>
<PropertyRef Name="DomainValuePosition"/>
<PropertyRef Name="DomainVersion"/>
</Key>
<Property Name="SAPDataDictionaryDomain" Type="Edm.String" Nullable="false" MaxLength="30" sap:display-format="UpperCase" sap:label="Domain name"/>
<Property Name="DomainValue" Type="Edm.String" Nullable="false" MaxLength="10" sap:display-format="UpperCase" sap:text="DomainValue_Text" sap:label="Lower Value" sap:quickinfo="Values for Domains: Single Value/Lower Limit"/>
<Property Name="DomainValue_Text" Type="Edm.String" MaxLength="60" sap:label="Short Descript." sap:quickinfo="Short Text for Fixed Values" sap:creatable="false" sap:updatable="false"/>
<Property Name="DomainActivationState" Type="Edm.String" Nullable="false" MaxLength="1" sap:display-format="UpperCase" sap:label="Activation Status" sap:quickinfo="Activation State of Repository Object"/>
<Property Name="DomainValuePosition" Type="Edm.String" Nullable="false" MaxLength="4" sap:display-format="NonNegative" sap:label="Value key" sap:quickinfo="Domain value key"/>
<Property Name="DomainVersion" Type="Edm.String" Nullable="false" MaxLength="4" sap:display-format="NonNegative" sap:label="Version" sap:quickinfo="Version of the entry (not used)"/>
</EntityType>
<EntityType Name="xBTLxTRP_TU_CFPType" sap:label="TU Carbon Footprint relavant Properties" sap:content-version="1">
<Key>
<PropertyRef Name="ObjectNr"/>
<PropertyRef Name="EquipmentNr"/>
<PropertyRef Name="TuId"/>
</Key>
<Property Name="ObjectNr" Type="Edm.String" Nullable="false" MaxLength="22" sap:display-format="UpperCase" sap:label="Object number" sap:creatable="false" sap:updatable="false"/>
<Property Name="EquipmentNr" Type="Edm.String" Nullable="false" MaxLength="18" sap:display-format="UpperCase" sap:label="Equipment" sap:quickinfo="Equipment Number" sap:creatable="false" sap:updatable="false"/>
<Property Name="TuId" Type="Edm.Guid" Nullable="false" sap:label="Equipment-ID" sap:creatable="false" sap:updatable="false"/>
<Property Name="MaintainedFlag" Type="Edm.String" MaxLength="1"/>
<Property Name="EngineCap" Type="Edm.Decimal" Precision="13" Scale="3" sap:unit="CapUnit" sap:label="Engine capacity"/>
<Property Name="CapUnit" Type="Edm.String" MaxLength="3" sap:label="Unit capacity" sap:quickinfo="Unit for engine capacity measurement" sap:value-list="standard" sap:semantics="unit-of-measure"/>
<Property Name="PrimaryFuel" Type="Edm.String" MaxLength="12" sap:display-format="UpperCase" sap:label="Primary fuel" sap:quickinfo="Consumable Type of Primary Fuel" sap:value-list="standard"/>
<Property Name="EngineType" Type="Edm.String" MaxLength="10" sap:display-format="UpperCase" sap:label="Engine type" sap:value-list="standard"/>
<Property Name="AverageConsumption" Type="Edm.Decimal" Precision="3" Scale="1" sap:unit="ConsumptionUnit" sap:label="Average Consumption" sap:quickinfo="Average fuel consumption of a transport unit"/>
<Property Name="BioFuelRatio" Type="Edm.Decimal" Precision="4" Scale="1" sap:label="Bio Fuel in %" sap:quickinfo="Percentage of bio fuel consumed by a transport unit"/>
<Property Name="ConsumptionUnit" Type="Edm.String" MaxLength="3" sap:label="Consumption Unit" sap:quickinfo="Unit of fuel consumption" sap:value-list="standard" sap:semantics="unit-of-measure"/>
<Property Name="EmissionStandard" Type="Edm.String" MaxLength="10" sap:display-format="UpperCase" sap:label="Emission Class" sap:quickinfo="Emission class of a transport unit" sap:value-list="standard"/>
<Property Name="EmissionTechnology" Type="Edm.String" MaxLength="10" sap:display-format="UpperCase" sap:label="Emission Technology" sap:quickinfo="Emission reducing technology used by a transport unit" sap:value-list="standard"/>
<Property Name="ParticleFilter" Type="Edm.String" MaxLength="5" sap:display-format="UpperCase" sap:label="Particle Filter" sap:quickinfo="Type of particle filter installed in a transport unit" sap:value-list="standard"/>
</EntityType>
<EntityType Name="I_FleetConsumableTypeType" sap:label="Fleet Consumable Type" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="FleetConsumableType"/>
</Key>
<Property Name="FleetConsumableType" Type="Edm.String" Nullable="false" MaxLength="12" sap:display-format="UpperCase" sap:text="FleetConsumableType_Text" sap:label="Fluid type" sap:quickinfo="Fluid Type"/>
<Property Name="FleetConsumableType_Text" Type="Edm.String" MaxLength="30" sap:label="Text for fluid type" sap:quickinfo="Description of Fluid Type" sap:creatable="false" sap:updatable="false"/>
</EntityType>
<EntityType Name="I_FleetEngineTypeType" sap:label="Fleet Engine Type" sap:value-list="true" sap:content-version="1">
<Key>
<PropertyRef Name="FleetEngineType"/>
</Key>
<Property Name="FleetEngineType" Type="Edm.String" Nullable="false" MaxLength="10" sap:display-format="UpperCase" sap:text="FleetEngineType_Text" sap:label="Engine type"/>
<Property Name="FleetEngineType_Text" Type="Edm.String" MaxLength="30" sap:label="Engine type - text" sap:quickinfo="Short text for engine type" sap:creatable="false" sap:updatable="false"/>
</EntityType>
<EntityType Name="SAP__Currency" sap:content-version="1">
<Key>
<PropertyRef Name="CurrencyCode"/>
</Key>
<Property Name="CurrencyCode" Type="Edm.String" Nullable="false" MaxLength="5" sap:label="Currency" sap:semantics="currency-code"/>
<Property Name="ISOCode" Type="Edm.String" Nullable="false" MaxLength="3" sap:label="ISO code"/>
<Property Name="Text" Type="Edm.String" Nullable="false" MaxLength="15" sap:label="Short text"/>
<Property Name="DecimalPlaces" Type="Edm.Byte" Nullable="false" sap:label="Decimals"/>
</EntityType>
<EntityType Name="SAP__UnitOfMeasure" sap:content-version="1">
<Key>
<PropertyRef Name="UnitCode"/>
</Key>
<Property Name="UnitCode" Type="Edm.String" Nullable="false" MaxLength="3" sap:label="Internal UoM" sap:semantics="unit-of-measure"/>
<Property Name="ISOCode" Type="Edm.String" Nullable="false" MaxLength="3" sap:label="ISO Code"/>
<Property Name="ExternalCode" Type="Edm.String" Nullable="false" MaxLength="3" sap:label="Commercial"/>
<Property Name="Text" Type="Edm.String" Nullable="false" MaxLength="30" sap:label="Meas. Unit Text"/>
<Property Name="DecimalPlaces" Type="Edm.Int16" sap:label="Decimal Places"/>
</EntityType>
<EntityType Name="SAP__DocumentDescription" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID"/>
<Property Name="CreatedBy" Type="Edm.String" Nullable="false" MaxLength="12"/>
<Property Name="CreatedAt" Type="Edm.DateTime" Nullable="false" Precision="0" sap:label="Time Stamp"/>
<Property Name="FileName" Type="Edm.String" Nullable="false" MaxLength="256"/>
<Property Name="Title" Type="Edm.String" Nullable="false" MaxLength="256"/>
<NavigationProperty Name="Format" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_format" FromRole="FromRole_to_format" ToRole="ToRole_to_format"/>
<NavigationProperty Name="TableColumns" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_tablecolumns" FromRole="FromRole_to_tablecolumns" ToRole="ToRole_to_tablecolumns"/>
<NavigationProperty Name="CoverPage" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_coverpage" FromRole="FromRole_to_coverpage" ToRole="ToRole_to_coverpage"/>
<NavigationProperty Name="Signature" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_signature" FromRole="FromRole_to_signature" ToRole="ToRole_to_signature"/>
<NavigationProperty Name="PDFStandard" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_pdfstandard" FromRole="FromRole_to_pdfstandard" ToRole="ToRole_to_pdfstandard"/>
<NavigationProperty Name="Hierarchy" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_Hierarchy" FromRole="FromRole_to_Hierarchy" ToRole="ToRole_to_Hierarchy"/>
<NavigationProperty Name="Header" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_header" FromRole="FromRole_to_header" ToRole="ToRole_to_header"/>
<NavigationProperty Name="Footer" Relationship="cds_xbtlxtrui_tu_cfp_maint.to_Footer" FromRole="FromRole_to_Footer" ToRole="ToRole_to_Footer"/>
</EntityType>
<EntityType Name="SAP__Format" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="FitToPage" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__FitToPage" Nullable="false"/>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="FontSize" Type="Edm.Int32" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Orientation" Type="Edm.String" Nullable="false" MaxLength="10" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="PaperSize" Type="Edm.String" Nullable="false" MaxLength="10" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="BorderSize" Type="Edm.Int32" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="MarginSize" Type="Edm.Int32" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="FontName" Type="Edm.String" Nullable="false" MaxLength="255" sap:label="Font Name" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Padding" Type="Edm.Int32" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__PDFStandard" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="UsePDFAConformance" Type="Edm.Boolean" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="DoEnableAccessibility" Type="Edm.Boolean" Nullable="false" sap:label="Indicator" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__TableColumns" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
<PropertyRef Name="Name"/>
<PropertyRef Name="Header"/>
</Key>
<Property Name="Format" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__TableColumnFormat" Nullable="false"/>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Name" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Header" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="HorizontalAlignment" Type="Edm.String" Nullable="false" MaxLength="10" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__CoverPage" sap:content-version="1">
<Key>
<PropertyRef Name="Title"/>
<PropertyRef Name="Id"/>
<PropertyRef Name="Name"/>
</Key>
<Property Name="Title" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Name" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Value" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__Signature" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="DoSign" Type="Edm.Boolean" Nullable="false" sap:label="Indicator" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="Reason" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__Hierarchy" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="DistanceFromRootElement" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="DrillStateElement" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__PDFHeader" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="Right" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__HeaderFooterField" Nullable="false"/>
<Property Name="Left" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__HeaderFooterField" Nullable="false"/>
<Property Name="Center" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__HeaderFooterField" Nullable="false"/>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__PDFFooter" sap:content-version="1">
<Key>
<PropertyRef Name="Id"/>
</Key>
<Property Name="Right" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__HeaderFooterField" Nullable="false"/>
<Property Name="Left" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__HeaderFooterField" Nullable="false"/>
<Property Name="Center" Type="cds_xbtlxtrui_tu_cfp_maint.SAP__HeaderFooterField" Nullable="false"/>
<Property Name="Id" Type="Edm.Guid" Nullable="false" sap:label="UUID" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</EntityType>
<EntityType Name="SAP__ValueHelp" sap:content-version="1">
<Key>
<PropertyRef Name="VALUEHELP"/>
</Key>
<Property Name="VALUEHELP" Type="Edm.String" Nullable="false"/>
<Property Name="FIELD_VALUE" Type="Edm.String" Nullable="false" MaxLength="10"/>
<Property Name="DESCRIPTION" Type="Edm.String"/>
</EntityType>
<ComplexType Name="DummyFunctionImportResult">
<Property Name="IsInvalid" Type="Edm.Boolean" sap:label="TRUE"/>
</ComplexType>
<ComplexType Name="SAP__FitToPage">
<Property Name="ErrorRecoveryBehavior" Type="Edm.String" Nullable="false" MaxLength="8" sap:label="Error behavior" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="IsEnabled" Type="Edm.Boolean" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="MinimumFontSize" Type="Edm.Int32" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</ComplexType>
<ComplexType Name="SAP__TableColumnFormat">
<Property Name="DisplayFormat" Type="Edm.String" Nullable="false" MaxLength="40" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="IANATimezone" Type="Edm.String" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
<Property Name="IANATimezoneProperty" Type="Edm.String" Nullable="false" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</ComplexType>
<ComplexType Name="SAP__HeaderFooterField">
<Property Name="Type" Type="Edm.String" Nullable="false" MaxLength="256" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
</ComplexType>
<Association Name="to_format" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_format"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__Format" Multiplicity="1" Role="ToRole_to_format"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_format">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_format">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_tablecolumns" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_tablecolumns"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__TableColumns" Multiplicity="*" Role="ToRole_to_tablecolumns"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_tablecolumns">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_tablecolumns">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_coverpage" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_coverpage"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__CoverPage" Multiplicity="*" Role="ToRole_to_coverpage"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_coverpage">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_coverpage">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_signature" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_signature"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__Signature" Multiplicity="1" Role="ToRole_to_signature"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_signature">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_signature">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_pdfstandard" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_pdfstandard"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFStandard" Multiplicity="1" Role="ToRole_to_pdfstandard"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_pdfstandard">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_pdfstandard">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_Hierarchy" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_Hierarchy"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__Hierarchy" Multiplicity="1" Role="ToRole_to_Hierarchy"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_Hierarchy">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_Hierarchy">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_header" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_header"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFHeader" Multiplicity="1" Role="ToRole_to_header"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_header">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_header">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<Association Name="to_Footer" sap:content-version="1">
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" Multiplicity="1" Role="FromRole_to_Footer"/>
<End Type="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFFooter" Multiplicity="1" Role="ToRole_to_Footer"/>
<ReferentialConstraint>
<Principal Role="FromRole_to_Footer">
<PropertyRef Name="Id"/>
</Principal>
<Dependent Role="ToRole_to_Footer">
<PropertyRef Name="Id"/>
</Dependent>
</ReferentialConstraint>
</Association>
<EntityContainer Name="cds_xbtlxtrui_tu_cfp_maint_Entities" m:IsDefaultEntityContainer="true" sap:message-scope-supported="true" sap:supported-formats="atom json xlsx pdf">
<EntitySet Name="SAP__FormatSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__Format" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__PDFStandardSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFStandard" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__TableColumnsSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__TableColumns" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__CoverPageSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__CoverPage" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__SignatureSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__Signature" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__HierarchySet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__Hierarchy" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__PDFHeaderSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFHeader" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__PDFFooterSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFFooter" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:addressable="false" sap:content-version="1"/>
<EntitySet Name="SAP__ValueHelpSet" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__ValueHelp" sap:content-version="1"/>
<EntitySet Name="xBTLxTRL_CONSUM_UNIT_VH" EntityType="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRL_CONSUM_UNIT_VHType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="xBTLxTRL_EMISSION_CLASS_VH" EntityType="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRL_EMISSION_CLASS_VHType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="xBTLxTRL_EMISSION_TECH_VH" EntityType="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRL_EMISSION_TECH_VHType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="xBTLxTRL_ENGINE_CAP_UNIT_VH" EntityType="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRL_ENGINE_CAP_UNIT_VHType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="xBTLxTRL_PARTICLE_FILTER_VH" EntityType="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRL_PARTICLE_FILTER_VHType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="xBTLxTRP_TU_CFP" EntityType="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType" sap:creatable="false" sap:deletable="false" sap:searchable="true" sap:content-version="1"/>
<EntitySet Name="I_FleetConsumableType" EntityType="cds_xbtlxtrui_tu_cfp_maint.I_FleetConsumableTypeType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="I_FleetEngineType" EntityType="cds_xbtlxtrui_tu_cfp_maint.I_FleetEngineTypeType" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1"/>
<EntitySet Name="SAP__Currencies" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__Currency" sap:content-version="1"/>
<EntitySet Name="SAP__UnitsOfMeasure" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__UnitOfMeasure" sap:content-version="1"/>
<EntitySet Name="SAP__MyDocumentDescriptions" EntityType="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription" sap:content-version="1"/>
<AssociationSet Name="to_FooterSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_Footer" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_Footer"/>
<End EntitySet="SAP__PDFFooterSet" Role="ToRole_to_Footer"/>
</AssociationSet>
<AssociationSet Name="to_headerSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_header" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_header"/>
<End EntitySet="SAP__PDFHeaderSet" Role="ToRole_to_header"/>
</AssociationSet>
<AssociationSet Name="to_formatSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_format" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_format"/>
<End EntitySet="SAP__FormatSet" Role="ToRole_to_format"/>
</AssociationSet>
<AssociationSet Name="to_pdfstandardSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_pdfstandard" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_pdfstandard"/>
<End EntitySet="SAP__PDFStandardSet" Role="ToRole_to_pdfstandard"/>
</AssociationSet>
<AssociationSet Name="to_tablecolumnsSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_tablecolumns" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_tablecolumns"/>
<End EntitySet="SAP__TableColumnsSet" Role="ToRole_to_tablecolumns"/>
</AssociationSet>
<AssociationSet Name="to_signatureSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_signature" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_signature"/>
<End EntitySet="SAP__SignatureSet" Role="ToRole_to_signature"/>
</AssociationSet>
<AssociationSet Name="to_coverpageSet" Association="cds_xbtlxtrui_tu_cfp_maint.to_coverpage" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_coverpage"/>
<End EntitySet="SAP__CoverPageSet" Role="ToRole_to_coverpage"/>
</AssociationSet>
<AssociationSet Name="to_HierarchySet" Association="cds_xbtlxtrui_tu_cfp_maint.to_Hierarchy" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:content-version="1">
<End EntitySet="SAP__MyDocumentDescriptions" Role="FromRole_to_Hierarchy"/>
<End EntitySet="SAP__HierarchySet" Role="ToRole_to_Hierarchy"/>
</AssociationSet>
<FunctionImport Name="copy_data" ReturnType="cds_xbtlxtrui_tu_cfp_maint.DummyFunctionImportResult" m:HttpMethod="POST" sap:action-for="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType">
<Parameter Name="ObjectNr" Type="Edm.String" Mode="In" MaxLength="22" sap:label="Object number"/>
<Parameter Name="EquipmentNr" Type="Edm.String" Mode="In" MaxLength="18" sap:label="Equipment"/>
<Parameter Name="TuId" Type="Edm.Guid" Mode="In" sap:label="Equipment-ID"/>
<Parameter Name="source_tu" Type="Edm.String" Mode="In" MaxLength="22" Nullable="true" sap:label="{@i18n>F7164.SourceTu}" sap:quickinfo="Object number"/>
<Parameter Name="copy_engine_type" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyEngineType}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_engine_cap" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyEngineCap}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_primary_fuel" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyPrimaryFuel}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_avg_cons" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyAvgCons}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_bio_fuel_ratio" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyBioFuelRatio}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_emssn_standard" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyEmssnStandard}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_emssn_tech" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyEmssnTech}" sap:quickinfo="Truth Value: True/False"/>
<Parameter Name="copy_particle_filter" Type="Edm.Boolean" Mode="In" Nullable="true" sap:label="{@i18n>F7164.CopyParticleFilter}" sap:quickinfo="Truth Value: True/False"/>
</FunctionImport>
</EntityContainer>
<Annotation xmlns="http://docs.oasis-open.org/odata/ns/edm" Term="Core.SchemaVersion" String="1.0.0"/>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/CapUnit">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Unit capacity"/>
<PropertyValue Property="CollectionPath" String="xBTLxTRL_ENGINE_CAP_UNIT_VH"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="CapUnit"/>
<PropertyValue Property="ValueListProperty" String="UnitOfMeasure"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="UnitOfMeasure_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/PrimaryFuel">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Primary fuel"/>
<PropertyValue Property="CollectionPath" String="I_FleetConsumableType"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="PrimaryFuel"/>
<PropertyValue Property="ValueListProperty" String="FleetConsumableType"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="FleetConsumableType_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/EngineType">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Engine type"/>
<PropertyValue Property="CollectionPath" String="I_FleetEngineType"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="EngineType"/>
<PropertyValue Property="ValueListProperty" String="FleetEngineType"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="FleetEngineType_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/ConsumptionUnit">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Consumption Unit"/>
<PropertyValue Property="CollectionPath" String="xBTLxTRL_CONSUM_UNIT_VH"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="ConsumptionUnit"/>
<PropertyValue Property="ValueListProperty" String="UnitOfMeasure"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="UnitOfMeasure_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/EmissionStandard">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Emission Class"/>
<PropertyValue Property="CollectionPath" String="xBTLxTRL_EMISSION_CLASS_VH"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="EmissionStandard"/>
<PropertyValue Property="ValueListProperty" String="DomainValue"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="DomainValue_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/EmissionTechnology">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Emission Technology"/>
<PropertyValue Property="CollectionPath" String="xBTLxTRL_EMISSION_TECH_VH"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="EmissionTechnology"/>
<PropertyValue Property="ValueListProperty" String="DomainValue"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="DomainValue_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.xBTLxTRP_TU_CFPType/ParticleFilter">
<Annotation Term="Common.ValueList">
<Record>
<PropertyValue Property="Label" String="Particle Filter"/>
<PropertyValue Property="CollectionPath" String="xBTLxTRL_PARTICLE_FILTER_VH"/>
<PropertyValue Property="SearchSupported" Bool="false"/>
<PropertyValue Property="Parameters">
<Collection>
<Record Type="Common.ValueListParameterInOut">
<PropertyValue Property="LocalDataProperty" PropertyPath="ParticleFilter"/>
<PropertyValue Property="ValueListProperty" String="DomainValue"/>
</Record>
<Record Type="Common.ValueListParameterDisplayOnly">
<PropertyValue Property="ValueListProperty" String="DomainValue_Text"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.cds_xbtlxtrui_tu_cfp_maint_Entities">
<Annotation Term="Common.ApplyMultiUnitBehaviorForSortingAndFiltering" Bool="true"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.cds_xbtlxtrui_tu_cfp_maint_Entities/xBTLxTRP_TU_CFP">
<Annotation Term="SAP__core.OptimisticConcurrency">
<Collection/>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.cds_xbtlxtrui_tu_cfp_maint_Entities">
<Annotation Term="Org.OData.Capabilities.V1.BatchSupport">
<Record Type="Org.OData.Capabilities.V1.BatchSupportType">
<PropertyValue Property="ReferencesAcrossChangeSetsSupported" Bool="true"/>
</Record>
</Annotation>
<Annotation Term="SAP__CodeList.CurrencyCodes">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__Currencies"/>
</Record>
</Annotation>
<Annotation Term="SAP__CodeList.UnitsOfMeasure">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__UnitsOfMeasure"/>
</Record>
</Annotation>
<Annotation Term="SAP__PDF.Features">
<Record>
<PropertyValue Property="DocumentDescriptionReference" String="./$metadata"/>
<PropertyValue Property="DocumentDescriptionCollection" String="SAP__MyDocumentDescriptions"/>
<PropertyValue Property="ArchiveFormat" Bool="true"/>
<PropertyValue Property="CoverPage" Bool="true"/>
<PropertyValue Property="Signature" Bool="true"/>
<PropertyValue Property="FitToPage" Bool="true"/>
<PropertyValue Property="FontName" Bool="true"/>
<PropertyValue Property="FontSize" Bool="true"/>
<PropertyValue Property="Margin" Bool="true"/>
<PropertyValue Property="Border" Bool="true"/>
<PropertyValue Property="Padding" Bool="true"/>
<PropertyValue Property="HeaderFooter" Bool="true"/>
<PropertyValue Property="IANATimezoneFormat" Bool="true"/>
<PropertyValue Property="ResultSizeDefault" Int="20000"/>
<PropertyValue Property="ResultSizeMaximum" Int="20000"/>
</Record>
</Annotation>
<Annotation Term="SAP__CodeList.SAP__DocumentDescription">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__MyDocumentDescriptions"/>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__Currency/CurrencyCode">
<Annotation Term="SAP__common.Text" Path="Text"/>
<Annotation Term="SAP__common.UnitSpecificScale" Path="DecimalPlaces"/>
<Annotation Term="SAP__CodeList.StandardCode" Path="ISOCode"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__UnitOfMeasure/UnitCode">
<Annotation Term="SAP__common.Text" Path="Text"/>
<Annotation Term="SAP__common.UnitSpecificScale" Path="DecimalPlaces"/>
<Annotation Term="SAP__CodeList.StandardCode" Path="ISOCode"/>
<Annotation Term="SAP__CodeList.ExternalCode" Path="ExternalCode"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__UnitOfMeasure">
<Annotation Term="SAP__core.AlternateKeys">
<Collection>
<Record>
<PropertyValue Property="Key">
<Collection>
<Record>
<PropertyValue Property="Name" Path="ExternalCode"/>
<PropertyValue Property="Alias" String="ExternalCode"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Collection>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription/CreatedBy">
<Annotation Term="SAP__core.Computed"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription/CreatedAt">
<Annotation Term="SAP__core.Computed"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__DocumentDescription">
<Annotation Term="SAP__capabilties.InsertRestrictions">
<Record>
<PropertyValue Property="Insertable" Bool="false"/>
</Record>
</Annotation>
<Annotation Term="SAP__capabilties.UpdateRestrictions">
<Record>
<PropertyValue Property="Updatable" Bool="false"/>
<PropertyValue Property="QueryOptions">
<Record>
<PropertyValue Property="SelectSupported" Bool="true"/>
</Record>
</PropertyValue>
</Record>
</Annotation>
<Annotation Term="SAP__capabilties.DeleteRestrictions">
<Record>
<PropertyValue Property="Deletable" Bool="false"/>
</Record>
</Annotation>
<Annotation Term="SAP__capabilties.FilterRestrictions">
<Record>
<PropertyValue Property="FilterExpressionRestrictions">
<Collection>
<Record>
<PropertyValue Property="Property" PropertyPath="Format/Orientation"/>
<PropertyValue Property="AllowedExpressions" String="Multivalue"/>
</Record>
<Record>
<PropertyValue Property="Property" PropertyPath="Format/PaperSize"/>
<PropertyValue Property="AllowedExpressions" String="Multivalue"/>
</Record>
</Collection>
</PropertyValue>
</Record>
</Annotation>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__Format/FitToPage/ErrorRecoveryBehavior">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="../../../../SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27ErrorRecoveryBehaviour%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__Format/FontName">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27FontName%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__Format/PaperSize">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27PaperSize%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFHeader/Left">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HeaderFooter%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFHeader/Right">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HeaderFooter%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFHeader/Center">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HeaderFooter%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFFooter/Left">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HeaderFooter%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFFooter/Right">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HeaderFooter%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__PDFFooter/Center">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HeaderFooter%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__TableColumns/Format/Display_Format">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27TableColumnFormat%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__Format/Orientation">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27FontName%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<Annotations xmlns="http://docs.oasis-open.org/odata/ns/edm" Target="cds_xbtlxtrui_tu_cfp_maint.SAP__TableColumns/HorizontalAlignment">
<Annotation Term="SAP__common.ValueListReferences">
<Record>
<PropertyValue Property="Url" String="./$metadata"/>
<PropertyValue Property="CollectionPath" String="SAP__ValueHelpSet?$filter=VALUEHELP%20eq%20%27HorizontalAlignment%27"/>
</Record>
</Annotation>
<Annotation Term="SAP__common.ValueListWithFixedValues"/>
</Annotations>
<atom:link xmlns:atom="http://www.w3.org/2005/Atom" rel="self" href="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/BTL/TRUI_TU_CFP_MAINT_O2/$metadata"/>
<atom:link xmlns:atom="http://www.w3.org/2005/Atom" rel="latest-version" href="https://ldcioid.devsys.net.sap:44300/sap/opu/odata/BTL/TRUI_TU_CFP_MAINT_O2/$metadata"/>
</Schema>
</edmx:DataServices>
</edmx:Edmx>
