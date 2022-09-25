# Rage! solve

## Challenge information

**Category**: misc

**Difficulty**: easy

**Author**: Yo_Yo_Bro

A raging Real Wild Child!

**Flag Format**: STRING you end up with after solving challenge, case insensitive.

### Steps followed to attain flag

We are provided with an audio file `insert link to rage.wav` that when played sounds familiar and has what sounds like Morse Code is included.


First step is to slow down the play speed to make it easier to follow.

![Play speed](https://user-images.githubusercontent.com/99635259/192143202-e7b05ffd-be20-4730-8df4-04269181d824.jpg)


Second step is to filter out the music by lowering the output frequency volume to isolate the code.

From doing testing I was able to find the frequency the Morse Code sound was playing at.

Frequency: 500hz

![EQ settings](https://user-images.githubusercontent.com/99635259/192143884-6c1fb141-356c-4b59-b44f-2b0b4a4d96d5.jpg)


Third step is inputting the sounds as either a short sound `Dot ( . )` or a long sound `Dash ( - )` into a translation program. 

![Rage Morse Code](https://user-images.githubusercontent.com/99635259/192143074-4b816602-aaf9-46f3-b1fb-a89a5596c60f.gif)

From the above result the flag is **DUCTF{ragingtoweirdlibido}**

