---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW VERSION OF THE SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new ExportPersonalDataPostRequestBody();
$requestBody->setStorageLocation('MyStorageAccount');

$graphServiceClient->directory()->inboundSharedUserProfiles()->byInboundSharedUserProfileId('inboundSharedUserProfile-userId')->exportPersonalData()->post($requestBody)->wait();

```