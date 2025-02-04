---
title: "list_origin_mapping.go"
description: "list_origin_mapping.go"
date: "2017-11-23"
classes: 
    - "SoftLayer_Network_ContentDelivery_Account"
tags:
    - "cdn"
---


```go
/*
List all the origin pull mappings in the CDN.

Important manual pages:
http://sldn.softlayer.com/reference/services/SoftLayer_Network_ContentDelivery_Account/getOriginPullMappingInformation

License: http://sldn.softlayer.com/article/License
Author: SoftLayer Technologies, Inc. <sldn@softlayer.com>
*/
package main

import (
	"fmt"
	"github.com/softlayer/softlayer-go/session"
	"github.com/softlayer/softlayer-go/services"
	"encoding/json"
)

func main() {
	// SoftLayer API username and key
	username := "set me"
	apikey   := "set me"

	// The id of CDN Account you wish to get pull mapping information
	cdnId := 8166

	// Create SoftLayer API session
	sess := session.New(username, apikey)

	// Get SoftLayer_Network_ContentDelivery_Account service
	service := services.GetNetworkContentDeliveryAccountService(sess)

	// Call the getOriginPullMappingInformation() method to get mapping information.
	cdnMapping, err := service.Id(cdnId).GetOriginPullMappingInformation()
	if err != nil {
		fmt.Printf("\n Unable to retrieve pull mapping information of CDN:\n - %s\n", err)
		return
	}

	// Following helps to print the result in json format.
	for _,origin := range cdnMapping {
		jsonFormat, jsonErr := json.Marshal(origin)
		if jsonErr != nil {
			fmt.Println(jsonErr)
			return
		}

		fmt.Println(string(jsonFormat))
	}
}

```
