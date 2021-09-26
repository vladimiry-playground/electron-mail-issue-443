The "About" app's window should show the `v4.12.9 2360806` version.

https://github.com/vladimiry/ElectronMail/runs/3714891211?check_suite_focus=true#step:17:2784 (hashes printed at the 2784 line)

Hashing 6 package's located in ./dist directory:
- electron-mail-4.12.9-linux-amd64.deb [sha256]: 06f6e5a8e51d296aeaf003d6f09629640421c8d0c6658578785f4db5a42ff929
- electron-mail-4.12.9-linux-amd64.snap [sha256]: a76c1743d8bf567136e69079e70222c8a4b7897b74fd03b5e0c723bb01253c3c
- electron-mail-4.12.9-linux-x64.freebsd [sha256]: 834f8ba0219f87d81931606c8421590c32ea60fbeeb3fe4acce551430b94f6d7
- electron-mail-4.12.9-linux-x64.pacman [sha256]: 2179a93fa6518cdee65272c54d97c56c39f4caac2c6f0ab9c92e4df977701021
- electron-mail-4.12.9-linux-x86_64.AppImage [sha256]: 9707b9fe70984647b803b0d2d4959a0403b674e3eb9cf49d38dca5ce0f2f30f4
- electron-mail-4.12.9-linux-x86_64.rpm [sha256]: 15b2ad42e05d4ef57b6e3feec931abaa0a26aabcc9335f19b7dc5a8f389d230f

###  How install & run the flatpak beta version

Beta branch location: https://github.com/flathub/com.github.vladimiry.ElectronMail/tree/beta

Commands to execute:
- `flatpak remote-add --user flathub-beta https://flathub.org/beta-repo/flathub-beta.flatpakrepo`
- `flatpak update --appstream`
- Run `flatpak search com.github.vladimiry.ElectronMail` and make sure that `com.github.vladimiry.ElectronMail 4.12.9 beta flathub-beta` is in the list.
- `flatpak install --user flathub-beta com.github.vladimiry.ElectronMail//beta`
- `flatpak run --branch=beta com.github.vladimiry.ElectronMail` (starting the app).
