# android-samsung-keyboard-bug-demo
An example app used to reproduce the [Samsung Korean keyboard bug from Flutter](https://github.com/flutter/flutter/issues/29341).

## Reproduction instructions
Use a later-model Samsung phone with the Samsung Keyboard set to the Korean language.

  1. Type "ㄴ" into the input.
  1. Press the button, which will move the cursor to the beginning of the input.
  1. Type "ㅇ" into the input.
  1. Notice that the result is backwards. It is "ㄴㅇ" when it should be "ㅇㄴ".

<img src="./korean_input_bug.gif" />

## Affected devices

  * Known to be affected:
    - S8
    - S9
    - Galaxy Note9
  * Know to NOT be affected:
    - S6 and earlier

