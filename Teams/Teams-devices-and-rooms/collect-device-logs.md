---
title: Collect Android Teams device logs
description: Describes how to use Teams admin center to collect Android device logs that run Teams.
author: MaryQiu1987
ms.author: v-maqiu
manager: dcscontentpm
audience: ITPro 
ms.topic: article 
ms.service: msteams
localization_priority: Normal
ms.custom: 
- CI 160238
- CSSTroubleshoot
ms.reviewer: miaitelh
appliesto:
- Microsoft Teams
search.appverid: 
- MET150
---
# Collect device logs for Android Teams devices

If you experience issues when you try to use Android devices that run Microsoft Teams, you'll have to collect diagnostic logs to be able to troubleshoot the issues. Here's how you can collect the device logs:

1. In the [Microsoft Teams admin center](https://admin.teams.microsoft.com/), select **Teams devices** on the navigation menu in the left pane, and then select the category of devices (such as **Phones**).
2. Select the Android device from which you want to download logs, and then select **Download device logs**.

   :::image type="content" source="media/collect-device-logs/teams-devices.png" alt-text="Screenshot of the Teams device field. The feature that's named Download device logs is highlighted.":::

3. After a few minutes, select the **History** tab, and then select the **Download** link under **Diagnostics file**.

   :::image type="content" source="media/collect-device-logs/history.png" alt-text="Screenshot of the History menu. The Download link is highlighted.":::

4. Extract the downloaded folder and look for a file name that begins with "Skylib". This file is the media log that contains diagnostic data.

   :::image type="content" source="media/collect-device-logs/skylib-file.png" alt-text="Screenshot of the extracted files. The file that has a name that begins as Skylib is highlighted.":::

Still need help? Go to [Microsoft Community](https://answers.microsoft.com/).
