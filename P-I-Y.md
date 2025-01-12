# PIY - Patch it Yourself
You can create your own version of NeoFreeBird if you'd like to avoid using random IPAs from GitHub. You just need to find an official Twitter IPA, then inject the tweaks and install it. If you prefer a video based tutorial you can use this [video tutorial](https://example.com)

## 1. Getting the app
First of all, you need a decrypted Twitter IPA. You can get one by either decrypting it yourself from a jailbroken iPhone, or using services like the [Decrypted App Store](https://armconverter.com/decryptedappstore/us) or [Decrypt.day](https://decrypt.day)

> [!WARNING]  
> Decrypt.day might not always have the latest Twitter version available. If you'd like the latest version straight from the App Store, you can use the Decrypted App Store instead.

## 2. Modifying the app
Now comes the fun part! Clone this repo by running this in your Terminal: 
```bash
git clone https://github.com/actuallyaridan/NeoFreeBird.git
```

> [!TIP]
> You can also [download it as a .zip file](https://github.com/actuallyaridan/NeoFreeBird/archive/refs/heads/main.zip) if you'd like to avoid the Terminal.

Next, decide if you'd like the older icons or the newer ones. Pick the folder containing the icons you prefer. You can see a comparison of the new and old icons below if you're unsure which to pick:

![Old vs. New Icons](https://github.com/user-attachments/assets/1b52957c-c177-4080-ac58-1cdcfd868747)
  

Now extract the ipa you downloaded earlier by renaming it from .ipa to .zip, then go into the extracted "Payload" Folder and if on macOS: Right Click the X.app and Choose "Show Package Contents", on Windows and Linux just double Click on the X.app Folder, then just drag the Contents of the Patches Folder into the .app (so the Assets.car, en.lproj, ...), choose "Replace" when asked if you want to replace the existing files.

## 3. Installing the app

Now we have to create a new ipa using the Patched Twitter App we just made, to do that, make a new Folder called "Payload" and drag the X.app in, then Compress it into a zip file and rename it to "something.ipa" where something can be any name you like, after doing that use a tool like [Sideloadly](https://sideloadly.io) or [AltStore Classic](https://altstore.io) to install the ipa!

Profit!
