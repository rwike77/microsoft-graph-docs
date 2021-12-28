---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

WorkbookRangeViewCollectionPage rows = graphClient.drive().root().workbook().worksheets("{id}")
	.range(WorkbookWorksheetRangeParameterSet
		.newBuilder()
		.withAddress("A1:Z10")
		.build())
	.visibleView().rows()
	.buildRequest()
	.get();

```