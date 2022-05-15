# deobfuscated-virus

I came across some kind of virus, targeted specifically for linux users. It was advertized as a "patch solving all problems".
While not hoping for anything, I decided to try to deobfuscate it.

It basically decodes base64 payload, which contains a python script, pipes it to temporary file, executes it and then removes it.
You can find deobfuscated python script in `deobfuscated.py`.
