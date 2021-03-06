---
title: Set up exclusions for Windows Defender AV scans
description: You can exclude files (including files modified by specified processes) and folders from being scanned by Windows Defender AV. Validate your exclusions with PowerShell.
keywords: 
search.product: eADQiWindows 10XVcnh
ms.pagetype: security
ms.prod: w10
ms.mktglfcycl: manage
ms.sitesec: library
ms.pagetype: security
ms.localizationpriority: medium
author: denisebmsft
ms.author: deniseb
ms.custom: nextgen
ms.date: 02/05/2020
ms.reviewer: 
manager: dansimp
---

# Configure and validate exclusions for Windows Defender Antivirus scans

**Applies to:**

- [Microsoft Defender Advanced Threat Protection (Microsoft Defender ATP)](https://go.microsoft.com/fwlink/p/?linkid=2069559)

You can exclude certain files, folders, processes, and process-opened files from Windows Defender Antivirus scans. Such exclusions apply to [scheduled scans](scheduled-catch-up-scans-windows-defender-antivirus.md), [on-demand scans](run-scan-windows-defender-antivirus.md), and [always-on real-time protection and monitoring](configure-real-time-protection-windows-defender-antivirus.md). Exclusions for process-opened files only apply to real-time protection.

>[!WARNING]
>Defining exclusions lowers the protection offered by Windows Defender Antivirus. You should always evaluate the risks that are associated with implementing exclusions, and you should only exclude files that you are confident are not malicious.

- [Configure and validate exclusions based on file name, extension, and folder location](configure-extension-file-exclusions-windows-defender-antivirus.md). This enables you to exclude files from Windows Defender Antivirus scans based on their file extension, file name, or location.

- [Configure and validate exclusions for files opened by processes](configure-process-opened-file-exclusions-windows-defender-antivirus.md). This enables you to exclude files from scans that have been opened by a specific process.

## Related articles

[Windows Defender Antivirus exclusions on Windows Server 2016](configure-server-exclusions-windows-defender-antivirus.md)