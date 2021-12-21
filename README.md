# firebase-unity-apple-silicon

For context, please see;

https://github.com/firebase/quickstart-unity/issues/1100


## If you are using .tgz files

    Extract .tgz file to a directory
    Find and replace bundle files (find matching one from arm64 folder)
    Rename x86_64 to arm64
    Rename x86_64.meta to arm64.meta
    Compress the directory to .tgz file

## If you are using .unitypackage

    Copy the arm64 directory into Assets/Firebase/Plugins
    Delete x86_64 from Assets/Firebase/Plugins
    Restart Unity