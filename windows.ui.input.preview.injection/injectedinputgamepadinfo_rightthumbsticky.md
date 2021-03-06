---
-api-id: P:Windows.UI.Input.Preview.Injection.InjectedInputGamepadInfo.RightThumbstickY
-api-type: winrt property
---

<!-- Property syntax.
public double RightThumbstickY { get;  set; }
-->

# Windows.UI.Input.Preview.Injection.InjectedInputGamepadInfo.RightThumbstickY

## -description
Gets or sets the position of the right stick on the Y-axis. 

## -property-value
A value between -1.0 (pressed towards the user) and 1.0 (pressed away from the user).

## -remarks

> [!Important]
> The APIs in this namespace require the inputInjectionBrokered [restricted capability](https://docs.microsoft.com/windows/uwp/packaging/app-capability-declarations#special-and-restricted-capabilities).

Using input injection requires the following be added to the Package.appxmanifest:

- To `<Package>`
    - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
    - `IgnorableNamespaces="rescap"`
- To `<Capabilities>`
    - `<rescap:Capability Name="inputInjectionBrokered" />`


## -see-also

### Conceptual

[Gaze interactions and eye tracking in UWP apps](https://docs.microsoft.com/windows/uwp/design/input/gaze-interactions)

### Samples

- [Simulate user input through input injection](https://review.docs.microsoft.com/windows/uwp/design/input/input-injection?branch=kbridge-inputinjection)
- [Input injection sample (mouse to touch)](https://github.com/MicrosoftDocs/windows-topic-specific-samples/archive/uwp-input-injection-mouse-to-touch.zip)
- [Touch injection sample](http://go.microsoft.com/fwlink/p/?LinkID=267906)
- [Input: XAML user input events sample](http://go.microsoft.com/fwlink/p/?linkid=226855)

## -examples

