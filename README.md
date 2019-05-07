# ![LOGO](logo.png) U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) **flow**ground Connector

## Description

A generated **flow**ground connector for the U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) API (version 0.0.0).

Generated from: https://api.apis.guru/v2/specs/epa.gov/dfr/0.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:23+03:00

## API Description

Enforcement and Compliance History Online (ECHO) is a tool developed and maintained by EPA's Office of Enforcement and Compliance Assurance for public use. ECHO provides integrated compliance and enforcement information for about 800,000 regulated facilities nationwide.
<BR><BR>DFR Rest Services provide multiple service endpoints, to retrieve detailed facility location, enforcement, compliance monitoring, and pollutant information for any single facility.  See the Detailed Facility Report (DFR) Help Page (https://echo.epa.gov/help/reports/detailed-facility-report-help) for additional information on the DFR.  Additionally, a Data Dictionary (https://echo.epa.gov/help/reports/dfr-data-dictionary) is also available.<BR><BR>
There is one primary service end point, get_dfr, that provides all available DFR data.  All other service end points that are exposed, will return data on a single section of the DFR. <br>  
<br>
Additional ECHO Resources:   <a href="https://echo.epa.gov/tools/web-services">Web Services</a>, <a href="https://echo.epa.gov/resources/echo-data/about-the-data">About ECHO's Data</a>, <a href="https://echo.epa.gov/tools/data-downloads">Data Downloads</a>
<br>

## Authorization

This API does not require authorization.

## Actions

### Detailed Facility Report Air Compliance Report Service

> This procedure obtains data for Air Compliance in the Environmental Conditions Section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Air Compliance Report Service

> This procedure obtains data for Air Compliance in the Environmental Conditions Section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Air Quality Report Service

> This procedure obtains data for Air Quality in the Environmental Conditions Section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Air Quality Report Service

> This procedure obtains data for Air Quality in the Environmental Conditions Section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report 5 Year Compliance Monitoring History Service

> This procedure obtains data for the Compliance Monitoring History (5 years) in the Enforcement and Compliance Section of the Detailed Facility report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report 5 Year Compliance Monitoring History Service

> This procedure obtains data for the Compliance Monitoring History (5 years) in the Enforcement and Compliance Section of the Detailed Facility report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Compliance Summary Service

> This procedure obtains data for Compliance Summary Data in the Enforcement and Compliance Section of the Detailed Facility report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Compliance Summary Service

> This procedure obtains data for Compliance Summary Data in the Enforcement and Compliance Section of the Detailed Facility report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report 3 Year CWA Facility-Level Status Service

> This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:<br/>
> > "In Viol" = Facility is in violation<br/>
> > "No Viol" = No violation found<br/>
> > "Unk" = Unknown status<br/>
> > "SNC/Cat 1" = SNC/Category I violation found

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report 3 Year CWA Facility-Level Status Service

> This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:<br/>
> > "In Viol" = Facility is in violation<br/>
> > "No Viol" = No violation found<br/>
> > "Unk" = Unknown status<br/>
> > "SNC/Cat 1" = SNC/Category I violation found

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA CSV Compliance Service

> This procedure obtains data for the CWA Compliance Schedule Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA CSV Compliance Service

> This procedure obtains data for the CWA Compliance Schedule Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA Effluent ALR Service

> This procedure obtains data for the CWA Pollutant Discharge section located in the Three Year Compliance Status by Quarter portion of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA Effluent ALR Service

> This procedure obtains data for the CWA Pollutant Discharge section located in the Three Year Compliance Status by Quarter portion of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA Effluent Compliance Service

> This procedure obtains data for the CWA Effluent Compliance section on the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA Effluent Compliance Service

> This procedure obtains data for the CWA Effluent Compliance section on the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA PSV Compliance Service

> This procedure obtains data for the CWA Permit Schedule Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA PSV Compliance Service

> This procedure obtains data for the CWA Permit Schedule Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA RNC Compliance Service

> This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.<br/>
> > S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule<br/>
> > E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)<br/>
> > X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)<br/>
> > T = SNC/Category I - compliance schedule reporting violation<br/>
> > D = SNC/Category I - reporting violation - nonreceipt of DMR<br/>
> > N = RNC/Category II - reportable non-compliance<br/>
> > P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion<br/>
> > R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action<br/>
> > C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted "m".<br/>
> > Blank = Not considered in RNC/SNC<br/>
> > N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA RNC Compliance Service

> This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.<br/>
> > S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule<br/>
> > E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)<br/>
> > X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)<br/>
> > T = SNC/Category I - compliance schedule reporting violation<br/>
> > D = SNC/Category I - reporting violation - nonreceipt of DMR<br/>
> > N = RNC/Category II - reportable non-compliance<br/>
> > P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion<br/>
> > R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action<br/>
> > C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted "m".<br/>
> > Blank = Not considered in RNC/SNC<br/>
> > N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA SEV Compliance Service

> This procedure obtains data for the CWA Single Event Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report CWA SEV Compliance Service

> This procedure obtains data for the CWA Single Event Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_radius` - _optional_
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_radius` - _optional_
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Service

> This procedure is the overall service for the Detailed Facility Report. It returns all of the data displayed in the DFR web report by invoking individual procedures that each return a targeted portion of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_system` - _optional_ - System Acronym Filter.  Enter a single system acronym to filter results.
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Service

> This procedure is the overall service for the Detailed Facility Report. It returns all of the data displayed in the DFR web report by invoking individual procedures that each return a targeted portion of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_system` - _optional_ - System Acronym Filter.  Enter a single system acronym to filter results.
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Enforcement Summary Service

> This procedure obtains data for the Enforcement and Compliance Summary in the Facility Summary section of the Detailed Facility Report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Enforcement Summary Service

> This procedure obtains data for the Enforcement and Compliance Summary in the Facility Summary section of the Detailed Facility Report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Formal Actions Service

> This procedure obtains data for the Formal Enforcement Actions section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Formal Actions Service

> This procedure obtains data for the Formal Enforcement Actions section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report ICIS Formal Actions Service

> This procedure obtains data for the Integrated Compliance Information System, Formal Enforcement Actions section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report ICIS Formal Actions Service

> This procedure obtains data for the Integrated Compliance Information System, Formal Enforcement Actions section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Inspections Summary Service

> This procedure obtains data for Enforcement and Compliance Summary Section of the Detailed Facility report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Inspections Summary Service

> This procedure obtains data for Enforcement and Compliance Summary Section of the Detailed Facility report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Map Service

> Returns an object with the facility's latitude and longitude coordinates.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Map Service

> Returns an object with the facility's latitude and longitude coordinates.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report NAICS Code Service

> This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report NAICS Code Service

> This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Notices Service

> This procedure obtains data for the Notices/Informal Actions section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Notices Service

> This procedure obtains data for the Notices/Informal Actions section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Permits Service

> This procedure obtains data for the following sections of the Detailed Facility Report.<br/>
> > Facility Information (FRS) in the Facility Summary.<br/>
> > Regulatory Interests in the Facility Summary.<br/>
> > Also Reports in the Facility Summary.<br/>
> > Facility/System Characteristics in Facility/System Characteristics.<br/>
> > Facility Contact Information in Facility/System Characteristics.<br/>
> > Facility SIC Codes in Facility/System Characteristics section.<br/>
> > Facility NAICS Codes in Facility/System Characteristics section.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Permits Service

> This procedure obtains data for the following sections of the Detailed Facility Report.<br/>
> > Facility Information (FRS) in the Facility Summary.<br/>
> > Regulatory Interests in the Facility Summary.<br/>
> > Also Reports in the Facility Summary.<br/>
> > Facility/System Characteristics in Facility/System Characteristics.<br/>
> > Facility Contact Information in Facility/System Characteristics.<br/>
> > Facility SIC Codes in Facility/System Characteristics section.<br/>
> > Facility NAICS Codes in Facility/System Characteristics section.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report RCRA Compliance Service

> This procedure obtains data for the RCRA Compliance section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report RCRA Compliance Service

> This procedure obtains data for the RCRA Compliance section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Lead and Copper Service

> This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Lead and Copper Service

> This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Sanitary Surveys Service

> This procedure obtains data for the SDWA, Sanitary Surveys section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Sanitary Surveys Service

> This procedure obtains data for the SDWA, Sanitary Surveys section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Sanitary Site Visits Service

> This procedure obtains data for the SDWA, Sanitary Site Visits section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Sanitary Site Visits Service

> This procedure obtains data for the SDWA, Sanitary Site Visits section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Violations Service

> This procedure obtains data for the SDWA Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWA Violations Service

> This procedure obtains data for the SDWA Violations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWIS Compliance Service

> This procedure obtains data for the SDWA Compliance section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SDWIS Compliance Service

> This procedure obtains data for the SDWA Compliance section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SIC Code Service

> This procedure obtains data for the Facility SIC Codes section in Facility/System Characteristics of the Detailed Facility Report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report SIC Code Service

> This procedure obtains data for the Facility SIC Codes section in Facility/System Characteristics of the Detailed Facility Report.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Spatial Metadata Service

> Returns an object with the facility coordinate spatial metadata.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Spatial Metadata Service

> Returns an object with the facility coordinate spatial metadata.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report TRI History Service

> This procedure obtains data for the TRI History section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report TRI History Service

> This procedure obtains data for the TRI History section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report TRI Releases Service

> This procedrue obtains data for the TRI Releases section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report TRI Releases Service

> This procedrue obtains data for the TRI Releases section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Tribes Service

> This procedure obtains data for the Tribes and Reservations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Tribes Service

> This procedure obtains data for the Tribes and Reservations section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Water Quality Service

> This procedure obtains data for the Water Quality section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_radius` - _optional_
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Detailed Facility Report Water Quality Service

> This procedure obtains data for the Water Quality section of the DFR.

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_radius` - _optional_
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_radius` - _optional_
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

### Placeholder

*Tags:* `Detailed Facility Report`

#### Input Parameters
* `output` - _optional_ - Output Format Flag.  Enter one of the following keywords:
- JSON = Data model formatted as Javascript Object Notation (default).
- JSONP = Data model formatted as Javascript Object Notation with Padding.  
- XML = Data model formatted as Extensible Markup Language.
    Possible values: JSONP, JSON, XML.
* `p_id` - _required_ - Either the EPA Facility Registry System's REGISTRY_ID for a facility or the facility identifier from the following EPA Systems: RCRAINFO (HANDLER_ID), AFS (SCSC), ICIS NPDES (NPDES_ID), or SDWIS (PWS_ID).
* `p_radius` - _optional_
* `callback` - _optional_ - JSONP Callback.  For use with JSONP and GEOJSONP output only.  Enter a name of the function in which to wrap the JSON response.

## License

**flow**ground :- Telekom iPaaS / epa-gov-dfr-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
