# p4a_helloworld
A working example for how to build an APK with flask and pythonforandroid or buildozer.

Notes.

Buildozer docs.
https://buildozer.readthedocs.io/en/latest/installation.html

Buildozer did produce an APK that I did install but the "app" doesn't stay up, the screen flickers once and the app closes again. Maybe that's intended behavior as in the app launches, executes run for a tick, "finishes" and exits or something.

I don't know how to access or find logs for this.

python for android
https://python-for-android.readthedocs.io/en/latest/

I did not manage to complete a build with pythonforandroid.

Although there are technically instructions on how to do it:
https://python-for-android.readthedocs.io/en/latest/quickstart/?highlight=flask#build-a-webview-application

It... didn't work. Hopefully with your help I can manage to make it work and we can improve the docs.

Alright, I installed adb today and connected to the phone, the phone has to be put into debug mode,
the way I did was tapping the android build number 7 times and entering the phones password, but it looks like it was different in the past so maybe looking up the way to do it for you is something you can try if this doesn't work for you.

