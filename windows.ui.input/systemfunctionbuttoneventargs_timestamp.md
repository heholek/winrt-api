---
-api-id: P:Windows.UI.Input.SystemFunctionButtonEventArgs.Timestamp
-api-type: winrt property
---

<!-- Property syntax.
public ulong Timestamp { get; }
-->

# Windows.UI.Input.SystemFunctionButtonEventArgs.Timestamp

## -description

Gets the date and time of the [SystemFunctionButtonPressed](systembuttoneventcontroller_systemfunctionbuttonpressed.md) and [SystemFunctionButtonReleased](systembuttoneventcontroller_systemfunctionbuttonreleased.md) events.

## -property-value

The date and time of the [SystemFunctionButtonPressed](systembuttoneventcontroller_systemfunctionbuttonpressed.md) and [SystemFunctionButtonReleased](systembuttoneventcontroller_systemfunctionbuttonreleased.md) events.

## -remarks

This API is intended for use by Accessibility tools as a low level hook for intercepting events from hardware system buttons.

[SystemButtonEventController](systembuttoneventcontroller.md) event registration applies system wide and is first-come, first-served. If an application or service sets a SystemButtonEventController event Handled property to true, applications or services that registered after that app or service for the same event notification will not receive the notification.

## -see-also

[Hooks Overview](/windows/win32/winmsg/about-hooks)

## -examples
