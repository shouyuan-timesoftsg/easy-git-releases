# Easy Git releases

Downloads of Easy Git.

This repository has only the releases. The code is kept elsewhere.

## Installing

1. Open the [latest release](../../releases/latest) and download `EasyGitSetup-<tag>.exe`.
2. Run it. If Windows says it protected your PC, choose **More info**, then **Run anyway**.
3. Tick what you want and press **Install**. It installs for you alone, so it needs no administrator, and it comes with Git, so you needn't install Git.

For a newer version, run the newer setup. To remove Easy Git, choose **Uninstall** next to it in **Settings > Apps > Installed apps**.

## Checking a download

The programs are signed by Shouyuan, Times Software Pte Ltd. Each release's notes give the certificate's thumbprint; compare it with the **Digital Signatures** tab of the file's **Properties**.
The certificate is self-signed, so Windows calls the signature untrusted until you trust the certificate.

## For programs

`latest.json` in each release describes its setup: version, download address, size, SHA-256 and signer thumbprint, and the release notes.
https://github.com/shouyuan-timesoftsg/easy-git-releases/releases/latest/download/latest.json is always the newest release's, pre-releases left out.

## Git for Windows

Easy Git comes with Git for Windows (MinGit), free software under the GNU GPL v2. Each release's notes name its version and link to its source.
