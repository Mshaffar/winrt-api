---
-api-id: P:Windows.UI.Input.Preview.Injection.InjectedInputGamepadInfo.Buttons
-api-type: winrt property
---

<!-- Property syntax.
public GamepadButtons Buttons { get;  set; }
-->

# Windows.UI.Input.Preview.Injection.InjectedInputGamepadInfo.Buttons

## -description
Gets or sets the gamepad buttons used for input injection.

## -property-value
One or more gamepad buttons used for input injection.

## -remarks

> [!Important]
> The APIs in this namespace require the inputInjectionBrokered [restricted capability](https://docs.microsoft.com/windows/uwp/packaging/app-capability-declarations#special-and-restricted-capabilities).

Using input injection requires the following be added to the Package.appxmanifest:

- To `<Package>`
    - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
    - `IgnorableNamespaces="rescap"`
- To `<Capabilities>`
    - `<rescap:Capability Name="inputInjectionBrokered" />`

## -examples

Here are some downloadable samples demonstrating basic input and input injection:

- [Input injection sample (mouse to touch)](https://github.com/MicrosoftDocs/windows-topic-specific-samples/archive/uwp-input-injection-mouse-to-touch.zip)
- [Touch injection sample](http://code.msdn.microsoft.com/Touch-Injection-Sample-444d9bf7)
- [Input: XAML user input events sample](http://code.msdn.microsoft.com/windowsapps/Input-3dff271b)

## -see-also

[InjectedInputGamepadInfo](GamepadReading reading), [Simulate user input through input injection](https://docs.microsoft.com/windows/uwp/design/input/input-injection)
