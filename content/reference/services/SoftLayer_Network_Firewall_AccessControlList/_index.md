---
title: "SoftLayer_Network_Firewall_AccessControlList"
description: "The SoftLayer_Network_Firewall_AccessControlList service accesses general information relating to a single SoftLayer fir... "
date: "2018-02-12"
layout: "service"
tags:
    - "service"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Firewall_AccessControlList"
---
# SoftLayer_Network_Firewall_AccessControlList
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
    <li id='service'> <a href='/reference/services/SoftLayer_Network_Firewall_AccessControlList' >Service</a></li>    <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Network_Firewall_AccessControlList' >Datatype</a></li>
    </ul>
</div>

## Description
The SoftLayer_Network_Firewall_AccessControlList service accesses general information relating to a single SoftLayer firewall access control list.  This is the object which ties the running rules to a specific context. The current running rule set can be pulled from this service. Use the [[SoftLayer Network Firewall Template]] service to pull SoftLayer recommended rule set templates. Use the [[SoftLayer Network Firewall Update Request]] service to submit a firewall update request. 
### external links
        Array
(
    [url] => http://en.wikipedia.org/wiki/Firewall_(networking)
    [description] => Firewall at Wikipedia
)
1        
### seeAlso
        SoftLayer_Network_Firewall_Template1        SoftLayer_Network_Firewall_Update_Request1                
        
<div id="properties" class="content">
    <h2>Methods</h2>
    <div class="view-filters">
        <div class="clearfix">
            <div class="search-input-box">
                <input placeholder="Datatype Filter" onkeyup="titleSearch(inputId='edit-combine', divId='method-div', elementClass='method-row')" 
                    type="text" id="edit-combine" value="" size="30" maxlength="128" class="form-text">
            </div>
        </div>
    </div>
    <div id="method-div">
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Firewall_AccessControlList/getNetworkFirewallUpdateRequests'> getNetworkFirewallUpdateRequests</a> </span>
            <div class='views-field-body'>Retrieve the update requests made for this firewall.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Firewall_AccessControlList/getNetworkVlan'> getNetworkVlan</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Firewall_AccessControlList/getObject'> getObject</a> </span>
            <div class='views-field-body'>Retrieve a SoftLayer_Network_Firewall_AccessControlList record.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Firewall_AccessControlList/getRules'> getRules</a> </span>
            <div class='views-field-body'>Retrieve the currently running rule set of this context access control list firewall.</div>
        </div>
        </div>
</div>
