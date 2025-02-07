<div align="center">
<h1><kbd>🧩 PatternConnect</kbd></h1>
An extension for MIT App Inventor 2.<br>
Developed by th using Fast.
</div>

## 📝 Specifications
* **
💾 **Size:** 33.50 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-02-07 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel)

## <kbd>Events:</kbd>
**PatternConnect** has total 7 events.

### 💛 Error
Error occurred

| Parameter | Type
| - | - |
| message | text

### 💛 PatternEntered
Pattern was entered by the user

| Parameter | Type
| - | - |
| pattern | text

### 💛 PatternAbandoned
Pattern input was abandoned

### 💛 AnimateInStarted
Animation to show pattern view has started

### 💛 AnimateInCompleted
Animation to show pattern view has completed

### 💛 AnimateOutStarted
Animation to hide pattern view has started

### 💛 AnimateOutCompleted
Animation to hide pattern view has completed

## <kbd>Methods:</kbd>
**PatternConnect** has total 6 methods.

### 💜 Initialize
Initialize the ConnectPatternView within a given HorizontalArrangement or VerticalArrangement.

| Parameter | Type
| - | - |
| arrangement | component

### 💜 Cleanup
Clean up the pattern view resources

### 💜 AnimateIn
Animate the pattern view in

### 💜 AnimateOut
Animate the pattern view out

### 💜 GetCurrentPattern
Get current pattern as string

### 💜 ResetToDefaults
Reset to default settings

## <kbd>Setters:</kbd>
**PatternConnect** has total 7 setter properties.

### 💚 BackgroundColor
Set background color of the pattern view

* Input type: `number`

### 💚 CircleColor
Set the color of the circles

* Input type: `number`

### 💚 NumberOfConnectors
Set the number of connectors (2, 3, 5, or 9)

* Input type: `number`

### 💚 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Input type: `number`

### 💚 CircleRadius
Set circle radius in dp

* Input type: `number`

### 💚 LineColor
Set the color of pattern lines

* Input type: `number`

### 💚 LineWidth
Set the width of pattern lines

* Input type: `number`

## <kbd>Getters:</kbd>
**PatternConnect** has total 4 getter properties.

### 🟢 NumberOfConnectors
Set the number of connectors (2, 3, 5, or 9)

* Return type: `number`

### 🟢 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Return type: `number`

### 🟢 GetLineColor
Get the current color of pattern lines

* Return type: `number`

### 🟢 GetLineWidth
Get the current width of pattern lines

* Return type: `number`


