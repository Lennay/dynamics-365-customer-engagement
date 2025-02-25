---
title: "View minutes used in voice calls | MicrosoftDocs"
description: "View the report to see the minutes used in voice calls in Omnichannel for Customer Service."
author: neeranelli
ms.author: nenellim
manager: shujoshi
ms.date: 08/13/2021
ms.topic: article
ms.service: dynamics-365-customerservice
ROBOTS: NOINDEX,NOFOLLOW
---


# Preview: View minutes used in voice calls

[!INCLUDE[cc-use-with-omnichannel](../includes/cc-use-with-omnichannel.md)]

> [!IMPORTANT]
> [!INCLUDE[cc-preview-feature](../includes/cc-preview-feature.md)]
>
> [!INCLUDE[cc-preview-features-definition](../includes/cc-preview-features-definition.md)]
>
> [!INCLUDE[cc-preview-features-expect-changes](../includes/cc-preview-features-expect-changes.md)]
>
> [!INCLUDE[cc-preview-features-no-ms-support](../includes/cc-preview-features-no-ms-support.md)]


## Introduction

The Voice usage report lets Omnichannel administrators view a Power BI report in Omnichannel admin center that helps them to get insights about how many call intelligence minutes and intelligent voicebot minutes from the voice quota have been consumed.

## Prerequisites

The voice channel should be configured and in use for the report to display data.

## View the voice usage report

To view the voice usage report, go to the Omnichannel admin center app, and in the site map, under **Insights**, select **Voice usage (Preview)**.

> ![The voice usage report.](media/voice-usage-report.png "The voice usage report.")

The following table contains the metrics.

|Metric|Description|
|--------|------|
|Call intelligence minutes|Number of minutes of calls where call transcription is generated. Number is rounded down to a whole number.  |
|Intelligent voicebot minutes|Number of minutes used by voicebot. Number is rounded down to a whole number.|
|Usage over time|Overtime trending of call intelligence minutes and intelligent voicebot minutes. |
|||

### Slice metrics by time

The Duration option lets you filter the report details and affects all metrics in the report. More information: [Slice metrics by time](intraday-insights-dashboard.md#slice-metrics-by-time)


### See also

[Overview of voice channel in Omnichannel for Customer Service](voice-channel.md)  