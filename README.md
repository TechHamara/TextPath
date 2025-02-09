# TextPath
An Ai2 Extension to Use this extension as text path animation.
<div align="center">
<h1><kbd>🧩 TextPathView</kbd></h1>
An extension for MIT App Inventor 2.<br>
Developed by th using Fast. Use this extension as text path animation.
</div>

## 📝 Specifications
* **
💾 **Size:** 16.38 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-02-09 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel)
<br>
**Telegram:** [here](https://t.me/techhamara91)<br>
**Find** more Extension [here](https://github.com/TechHamara/Th_Free_Extensions)<br>
**Apps On PlayStore:** [here](https://play.google.com/store/apps/dev?id=6332469651067611923)
<br><br>

## <kbd>Events:</kbd>
**TextPathView** has total 2 events.

![AnimationStartedBlock](https://github.com/user-attachments/assets/d0002bb4-dfdf-481d-86ca-65b0e648e8a5)
### 💛 AnimationStarted
Event triggered when the animation starts<br>

![AnimationEndedBlock](https://github.com/user-attachments/assets/6dd2a7b5-4718-4122-a442-9b87e48a8ed0)
### 💛 AnimationEnded
Event triggered when the animation ends
<br>

## <kbd>Methods:</kbd>
**TextPathView** has total 19 methods.<br>

![InitBlock](https://github.com/user-attachments/assets/80383d3f-23c8-40ec-9100-9c2e65244c57)
### 💜 Init
Attach the TextPathView to an HVArrangement.

| Parameter | Type
| - | - |
| arrangement | component<br>

![SetShadowBlock](https://github.com/user-attachments/assets/deb32243-70a0-4fb7-8b86-7e010964db2b)
### 💜 SetShadow
Set the shadow layer

| Parameter | Type
| - | - |
| radius | number
| dx | number
| dy | number
| color | number

![SetPaintTypeBlock](https://github.com/user-attachments/assets/88a8ef56-ece2-4ce3-b35a-a282f6789f84)
### 💜 SetPaintType
Set the paint type for the text. Use 0 for SINGLE and 1 for MULTIPLY.

| Parameter | Type
| - | - |
| type | number

![SetPhaseBlock](https://github.com/user-attachments/assets/ed4bde59-8ebc-4be1-89b7-fdaebeb44bb7)
### 💜 SetPhase
Set the phase (Rang of 0.0 to 1.0 )of the animation.

| Parameter | Type
| - | - |
| phase | number

![PhaseBlock](https://github.com/user-attachments/assets/c601cb40-b346-492c-805a-c4d99215d566)
### 💜 Phase
Get the current phase of the animation.

![StartAnimationBlock](https://github.com/user-attachments/assets/4831e9c3-72c3-46f7-9ef5-edc0247a921f)
### 💜 StartAnimation
Start the animation with optional looping. Set loop to true for infinite looping.

| Parameter | Type
| - | - |
| loop | boolean

![PauseAnimationBlock](https://github.com/user-attachments/assets/50111630-c402-4b27-9327-5ae2c47bace9)
### 💜 PauseAnimation
Pause the running animation.

![ResumeAnimationBlock](https://github.com/user-attachments/assets/524348dd-9d77-447e-a790-7b317d94bac7)
### 💜 ResumeAnimation
Resume the paused animation.

![ReverseAnimationBlock](https://github.com/user-attachments/assets/4424eb1c-d9ca-4593-bf02-9eddd963e595)
### 💜 ReverseAnimation
Reverse the animation.

![SetStartDelayBlock](https://github.com/user-attachments/assets/4bf79a07-693f-4bee-a627-9c302bb4c011)
### 💜 SetStartDelay
Set a start delay for the animation in milliseconds.

| Parameter | Type
| - | - |
| delay | number

![SetAnimationSpeedBlock](https://github.com/user-attachments/assets/9cf00bcb-0e71-419b-b549-4b74bafb8e3e)
### 💜 SetAnimationSpeed
Set the speed of the animation. Higher values make it faster.

| Parameter | Type
| - | - |
| speed | number

![SetEasingFunctionBlock](https://github.com/user-attachments/assets/fe8bdd89-ec33-45ea-a179-d8fa34a6b006)
### 💜 SetEasingFunction
Set a custom easing function. Use values like Linear, Bounce, or Accelerate.

| Parameter | Type
| - | - |
| easing | text

![SetAnimationColorBlock](https://github.com/user-attachments/assets/e707dc14-d2e8-4123-a523-701e9afdd454)
### 💜 SetAnimationColor
Change the color of the animated path dynamically.

| Parameter | Type
| - | - |
| color | number

![StartAnimationWithRepeatsBlock](https://github.com/user-attachments/assets/c2d31d9c-981c-4be2-a38d-9adcac32fdea)
### 💜 StartAnimationWithRepeats
Start the animation with a specified number of repeats.

| Parameter | Type
| - | - |
| repeatCount | number

![SetStrokeWidthBlock](https://github.com/user-attachments/assets/2e561f1d-ea7a-4a1f-bc02-9e8cd9914256)
### 💜 SetStrokeWidth
Set the stroke width of the animated path.

| Parameter | Type
| - | - |
| width | number

![SetGradientColorBlock](https://github.com/user-attachments/assets/3d2a09de-d60e-42a3-98c8-8492e5d38516)
### 💜 SetGradientColor
Apply a gradient color to the animated path.

| Parameter | Type
| - | - |
| startColor | number
| endColor | number

![StartBounceAnimationBlock](https://github.com/user-attachments/assets/5d98bacf-c701-4f43-86e0-edfadb2a1e3b)
### 💜 StartBounceAnimation
Start the animation with a bounce effect.

![ResetAnimationBlock](https://github.com/user-attachments/assets/5c8fe7e4-7e09-49f9-a0ff-7b357a15832b)
### 💜 ResetAnimation
Reset the animation to its initial state.

![SetAntiAliasBlock](https://github.com/user-attachments/assets/31f5c354-7fc6-439a-ba53-feea5625a57b)
### 💜 SetAntiAlias
Enable or disable anti-aliasing for smoother path rendering.

| Parameter | Type
| - | - |
| enabled | boolean

## <kbd>Setters:</kbd>
**TextPathView** has total 5 setter properties.<br>

![TextBlock](https://github.com/user-attachments/assets/60a3fff4-1745-4a41-907e-0a410f7bb97f)
### 💚 Text
Set the text to be displayed

* Input type: `text`

![TextColorBlock](https://github.com/user-attachments/assets/e4511222-f94f-4942-aa55-708c972f7094)
### 💚 TextColor
Set the text color

* Input type: `number`

![TextSizeBlock](https://github.com/user-attachments/assets/3e7ef3b9-de7b-4635-90ee-4f59652b5fb3)
### 💚 TextSize
Set the text size

* Input type: `number`

![TextWeightBlock](https://github.com/user-attachments/assets/f7b8361b-8671-4687-b9cc-3ff53ea84d0d)
### 💚 TextWeight
Set the text weight

* Input type: `number`

![DurationBlock](https://github.com/user-attachments/assets/ef0cd672-287e-47ab-8f14-95629e60d716)
### 💚 Duration
Set the duration of the animation

* Input type: `number`
### demo video 

https://youtube.com/shorts/I_smgEa0iy0?si=_t47DREwhAFy20Js

### Thanks
  TechHamara

