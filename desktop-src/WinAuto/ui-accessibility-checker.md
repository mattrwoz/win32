---
title: UI Accessibility Checker
description: Describes UI Accessibility Checker, a tool for testing an application's UI Automation or Microsoft Active Accessibility (MSAA) implementation.
ms.assetid: 92155984-356A-4774-A99D-35B15A3BB704
keywords:
- UI Accessibility Checker
- AccChecker
- UI Automation implementation,testing
- UIA implementation,testing
- Microsoft Active Accessibility implementation,testing
- MSAA implementation,testing
- testing UI Automation
- testing UIA
- testing Microsoft Active Accessibility
- testing MSAA
- UIA testing tools
- UI Automation testing tools
- MSAA testing tools
- Microsoft Active Accessibility testing tools
ms.topic: article
ms.date: 05/31/2018
---

# UI Accessibility Checker

The UI Accessibility Checker (AccChecker) tool verifies that key UI accessibility requirements are met in the design and implementation of UI Automation (UIA) or Microsoft Active Accessibility (MSAA) regardless of the underlying UI framework. AccChecker also includes a set of web accessibility verifications.

AccChecker provides the following levels of functionality:

-   A Windows GUI application that supports manual testing, message logging, and suppression generation.
-   An API for use in automated testing frameworks.
-   A console application that supports unmanaged test automations for scenarios where the AccChecker managed API can't be used.

All levels of AccChecker functionality provide routines for verifying Microsoft Active Accessibility programmatic access, programmatic event generation, control layout, and keyboard navigation. AccChecker also provides a basic screen reader transcription service.

AccChecker is installed with the Windows Software Development Kit (SDK). It is located in the \\bin\\<*version*>\\<*platform*>\\AccChecker folder of the SDK installation path.

## In this section

-   [Testing with AccChecker](testing-with-accchecker.md)
-   [The AccChecker Graphical User Interface](the-accchecker-graphical-user-interface.md)
-   [The AccChecker Console](the-accchecker-console.md)
-   [The AccChecker API](the-accchecker-api.md)
-   [Verification Routines](verification-routines.md)
-   [Custom Verification Routines](custom-verification-routines.md)
-   [Verification Log Messages](verification-log-messages.md)

## Requirements

Requires .NET Framework 2.0 or later.

AccChecker can be used to examine accessibility data on systems that don't have Microsoft UI Automation, but can only examine the Microsoft Active Accessibility properties. To examine UI Automation, UI Automation must be present on the system. For more information, see the "Requirements" section of [UI Automation](entry-uiauto-win32.md).

AccChecker is installed as part of the overall set of tools in theWindows SDK, it is not distributed as a separate exe download. The Windows SDK includes all of the accessibility-related tools documented in this section. [Get the Windows SDK.](https://go.microsoft.com/fwlink/p/?LinkID=271979) (There's also an SDK download archive linked from that page, if you need a previous version.)

## Related topics

<dl> <dt>

[Accessible Event Watcher](accessible-event-watcher.md)
</dt> <dt>

[Inspect](inspect-objects.md)
</dt> <dt>

[Testing Tools](testing-tools.md)
</dt> <dt>

[UI Automation Verify](ui-automation-verify.md)
</dt> </dl>

 

 




