# android-samsung-keyboard-bug-demo
An example app used to reproduce the Samsung Korean keyboard bug from Flutter.

## Reproduction instructions
Use a later-model Samsung phone with the Samsung Keyboard set to the Korean language.

  1. Type "ㄴ" into the input.
  1. Press the button, which will move the cursor to the beginning of the input.
  1. Type "ㅇ" into the input.
  1. Notice that the result is backwards. It is "ㄴㅇ" when it should be "ㅇㄴ".

It is known that an S6 does not exhibit this bug, but a Galaxy Note9 does. Using a different keyboard, like Gboard in Korean, does not exhibit the bug.

<img src="./korean_input_bug.gif" />
