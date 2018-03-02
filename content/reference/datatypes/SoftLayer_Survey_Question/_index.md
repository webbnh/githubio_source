---
title: "SoftLayer_Survey_Question"
description: "The SoftLayer_Survey_Question data type contains general information relating to a single SoftLayer survey question."
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Survey"
classes:
    - "SoftLayer_Survey_Question"
---

# SoftLayer_Survey_Question
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
        <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Survey_Question' >Datatype</a></li>
    </ul>
</div>

## Description 
The SoftLayer_Survey_Question data type contains general information relating to a single SoftLayer survey question. 
<!-- Service Filer BEGIN -->
<div class="view-filters">
        <div class="clearfix">
            <div class="search-input-box">
                <input placeholder="Method Filter" onkeyup="titleSearch(inputId='prop-input', divId='properties', elementClass='prop-row')" 
                    type="text" id="prop-input" value="" size="30" maxlength="128" class="form-text">
            </div>
        </div>
</div>
<!-- Service Filer END -->

<div id="properties" class="content">
    <div id="localProperties" class="prop-content" >
        <h2>Local</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#id" name=id>id</a></span>
            <div class='views-field-body'>A survey question's Id. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p>integer</p></div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#isRequired" name=isRequired>isRequired</a></span>
            <div class='views-field-body'>A flag indicating that a survey question requires a response. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p>integer</p></div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#multiAnswer" name=multiAnswer>multiAnswer</a></span>
            <div class='views-field-body'>A flag indicating that a survey question can have multiple answers responded to. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p>integer</p></div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#question" name=question>question</a></span>
            <div class='views-field-body'>A survey question's question. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p>string</p></div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#questionOrder" name=questionOrder>questionOrder</a></span>
            <div class='views-field-body'>A value indicating the order in when a survey question will be asked. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p>integer</p></div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#surveyId" name=surveyId>surveyId</a></span>
            <div class='views-field-body'>A survey question's associated [[SoftLayer_Survey|Survey]] Id. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p>integer</p></div>
        </div>
            </div>
        <div id="relationalProperties"  class="prop-content" >
        <h2>Relational</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#answers" name=answers>answers</a></span>
            <div class='views-field-body'>The possible answers for a survey question. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p><a href='/reference/datatypes/SoftLayer_Survey_Answer'>SoftLayer_Survey_Answer[] </a></p></div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'><a href="#survey" name=survey>survey</a></span>
            <div class='views-field-body'>The survey that a question belongs to. </div>
            <span class="type-label">Type:</span> <div class='type-content'><p><a href='/reference/datatypes/SoftLayer_Survey'>SoftLayer_Survey </a></p></div>
        </div>
            </div>
</div>

