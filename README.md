# Keybinds backup for Elite Dangerous

## Peripherals
1. Stick R - Virpil Constellation Alpha Grip R
2. Stick L - Virpil Constellation Alpha Grip L
3. Thrust Control - Virpil Mongoost T-50CM3
4. Rudder Peddals - Virplil ACE-Collection Rudder Pedals

## High Control Concept

### Right Grip
Basic Flight Controls and Navigation

- Orientation - Pitch
- Orientation - Roll
- Target Selection
- Menu Navigation
- FireGroup Selection
- Free Look

### Left Grip
Advance Combat Maneuvering

 - Thrusters - Vertical
 - Thrusters - Lateral 
 - Thrusters - Forward/Reverse (Used in combat and during landing and take off)
 - Subsystem Selection

### Thrust Control
Exploration/Long Range Travel

- Thrusters - Forward (Constant Thurst)
- Modes - Cockpit Mod Selection
- Modes - Switch Game Mode (Galaxy/System Map)
- FSS Imersive mode (Using the little dials)
- Photography

### Ruder Pedals
- Orientation - Yaw



## Keybind Issues

### Names and Version Numbers
It appears that ED Keybinds are being reset on every version because Elite Dangerous generates a new Keybind file. The files apper to follow the XML format.

e.g.
```xml
<YawAxisRaw>
    <Binding Device="334401F8" Key="Joy_ZAxis" />
    <Inverted Value="1" />
    <Deadzone Value="0.00000000" />
</YawAxisRaw>
```

The `YawAxisRaw` Binding for example, is Assigned to Device with id "334401F8" and key "Joy_ZAxis". That most likely must be my Rudder Pedal. That detail will probably make sharing these keybinds with another CMDR, or even with a future installation on another machine, difficult, as the device ids would be different, unless they can find a way to find the Device ID and find/replace. 



