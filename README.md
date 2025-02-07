<div align="center">
<h1><kbd>🧩 PatternConnect</kbd></h1>
An extension for MIT App Inventor 2.<br>
Developed by th using Fast.
</div>

## 📝 Specifications
* **
💾 **Size:** 33.50 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-02-07 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel)
<br>
**Telegram:** [here](https://t.me/techhamara91)<br>
**Find** more Extension [here](https://github.com/TechHamara/Th_Free_Extensions)<br><br>

## <kbd>Events:</kbd>
**PatternConnect** has total 7 events.
<br><br>
![ErrorBlock](https://github.com/user-attachments/assets/75c6304f-8f25-4677-bf26-6db3e986dc6b)
### 💛 Error
Error occurred

| Parameter | Type
| - | - |
| message | text

![PatternEnteredBlock](https://github.com/user-attachments/assets/7b9e1233-3348-4d32-b57a-02f736264f3f)

### 💛 PatternEntered
Pattern was entered by the user

| Parameter | Type
| - | - |
| pattern | text

![PatternAbandonedBlock](https://github.com/user-attachments/assets/f3a839fe-302c-49fc-a19c-910d858a1b90)
### 💛 PatternAbandoned
Pattern input was abandoned

![AnimateInStartedBlock](https://github.com/user-attachments/assets/556400fc-2e43-4703-8c24-31fd211bf645)

### 💛 AnimateInStarted
Animation to show pattern view has started

![AnimateInCompletedBlock](https://github.com/user-attachments/assets/81711483-baad-4ace-a1ba-bc4a059a1b9b)

### 💛 AnimateInCompleted
Animation to show pattern view has completed

![AnimateOutStartedBlock](https://github.com/user-attachments/assets/d793a273-bcee-4f4f-a3c0-6012500b401c)

### 💛 AnimateOutStarted
Animation to hide pattern view has started

![AnimateOutCompletedBlock](https://github.com/user-attachments/assets/ba41ca81-8bb5-4b33-878b-f943a8dc92ff)

### 💛 AnimateOutCompleted
Animation to hide pattern view has completed
<br><br>
## <kbd>Methods:</kbd>
**PatternConnect** has total 6 methods.
<br>
![InitializeBlock](https://github.com/user-attachments/assets/85472472-38aa-4fe9-86e7-c757cfdd3599)

### 💜 Initialize
Initialize the ConnectPatternView within a given HorizontalArrangement or VerticalArrangement.

| Parameter | Type
| - | - |
| arrangement | component

![CleanupBlock](https://github.com/user-attachments/assets/a4037ac8-1387-4c7c-8a55-d36e30b82df0)

### 💜 Cleanup
Clean up the pattern view resources

![AnimateInBlock](https://github.com/user-attachments/assets/e22b9878-6fec-4f41-9b57-abdd27c229d9)

### 💜 AnimateIn
Animate the pattern view in

![AnimateOutBlock](https://github.com/user-attachments/assets/24218d11-7122-43d9-a53c-f34ade724130)

### 💜 AnimateOut
Animate the pattern view out

![GetCurrentPatternBlock](https://github.com/user-attachments/assets/e5a7f366-665f-4650-b0b2-c5e15a66e945)

### 💜 GetCurrentPattern
Get current pattern as string

![ResetToDefaultsBlock](https://github.com/user-attachments/assets/d1e5abe5-fea6-4327-bb14-8f45836d3099)

### 💜 ResetToDefaults
Reset to default settings
<br><br>
## <kbd>Setters:</kbd>
**PatternConnect** has total 7 setter properties.
<br>
![BackgroundColorBlock](https://github.com/user-attachments/assets/546a96ff-d819-4e33-b060-ffa21bce2c28)
### 💚 BackgroundColor
Set background color of the pattern view

* Input type: `number`

![CircleColorBlock](https://github.com/user-attachments/assets/58143da1-25cb-4732-9dda-d09e0499e1d5)

### 💚 CircleColor
Set the color of the circles

* Input type: `number`

![NumberOfConnectorsBlock](https://github.com/user-attachments/assets/c996a5e0-7251-4811-a69e-0999d3890cc9)

### 💚 NumberOfConnectors
Set the number of connectors (2, 3, 5, or 9)

* Input type: `number`

![AnimationTypeBlock](https://github.com/user-attachments/assets/36ebaba3-42cc-46be-97b9-6504af3ffb87)

### 💚 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Input type: `number`

![CircleRadiusBlock](https://github.com/user-attachments/assets/9bd0ad87-a28c-4ed8-af38-fe0ef0a02344)

### 💚 CircleRadius
Set circle radius in dp

* Input type: `number`

![LineColorBlock](https://github.com/user-attachments/assets/701233a8-e745-4c7a-b567-e8c624ca2292)

### 💚 LineColor
Set the color of pattern lines

* Input type: `number`

![LineWidthBlock](https://github.com/user-attachments/assets/2c19046d-8d7d-47e9-a28f-144bb9e9c47b)

### 💚 LineWidth
Set the width of pattern lines

* Input type: `number`

## <kbd>Getters:</kbd>
**PatternConnect** has total 4 getter properties.

![NumberOfConnectorsBlock](https://github.com/user-attachments/assets/783a72d4-bc75-42eb-8c6f-260d2daa95e3)
### 🟢 NumberOfConnectors
Set the number of connectors (2, 3, 5, or 9)

* Return type: `number`

![getAnimationTypeBlock](https://github.com/user-attachments/assets/06d92fe9-920f-4ae6-b222-036e8c9fca06)
### 🟢 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Return type: `number`

![GetLineColorBlock](https://github.com/user-attachments/assets/5250c9fc-f2ec-4cf9-a392-642390a8b7c4)
### 🟢 GetLineColor
Get the current color of pattern lines

* Return type: `number`

![GetLineWidthBlock](https://github.com/user-attachments/assets/8ff4fc4d-7585-4e98-b166-ffa0aa55cd6e)
### 🟢 GetLineWidth
Get the current width of pattern lines

* Return type: `number`

### Demo Blocks

![pattern demo blocks](https://github.com/user-attachments/assets/5f842b4e-c4ed-44d4-a881-7014f412a45f)

### Thanks and Regards
    TechHamara
    https://t.me/techhamara91

