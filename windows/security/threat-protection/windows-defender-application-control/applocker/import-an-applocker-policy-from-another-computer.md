---
title: Import an AppLocker policy from another computer
description: This topic for IT professionals describes how to import an AppLocker policy.
ms.reviewer: 
ms.author: vinpa
ms.prod: windows-client
ms.localizationpriority: medium
author: vinaypamnani-msft
manager: aaroncz
ms.topic: conceptual
ms.technology: itpro-security
ms.date: 12/31/2017
---

# Import an AppLocker policy from another computer

> [!NOTE]
> Some capabilities of Windows Defender Application Control are only available on specific Windows versions. Learn more about the [Windows Defender Application Control feature availability](/windows/security/threat-protection/windows-defender-application-control/feature-availability).

This topic for IT professionals describes how to import an AppLocker policy.

Before completing this procedure, you should have exported an AppLocker policy. For more information, see [Export an AppLocker policy to an XML file](export-an-applocker-policy-to-an-xml-file.md).

Membership in the local **Administrators** group, or equivalent, is the minimum required to complete this procedure.

> **Caution:**  Importing a policy will overwrite the existing policy on that computer.
 
**To import an AppLocker policy**

1.  From the AppLocker console, right-click **AppLocker**, and then click **Import Policy**.

2.  In the **Import Policy** dialog box, locate the file that you exported, and then click **Open**.

3.  The **Import Policy** dialog box will warn you that importing a policy will overwrite the existing rules and enforcement settings. If acceptable, click **OK** to import and overwrite the policy.

4.  The **AppLocker** dialog box will notify you of how many rules were overwritten and imported. Click **OK**.
