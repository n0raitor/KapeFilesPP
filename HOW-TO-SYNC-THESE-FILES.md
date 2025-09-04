# HOW TO SYNC These Files to KAPE

Tell KAPE to Use this Fork:

By default, KAPE syncs against Eric’s repo. To use your fork, update the Kape.exe.config file:

* Open Kape.exe.config in the same folder as Kape.exe.
* Look for the line that defines the repo URL (it points to Eric’s GitHub by default).
* Replace it with your fork’s repo URL:
```
<add key="KapeFilesUrl" value="https://github.com/<YourOrg>/KapeFiles" />
```
