# DSpico auto firmware builder
This will generate a new firmware build whenever the firmware, the bootloader or wrfuxxed get updated. 
<br>
Due to GitHub Actions limitations, updates must be scheduled to run once a day and won't be automatically triggered as soon as a commit is pushed to those repos.
<br>
The resulting firmware file isn't meant to be used standalone, as it doesn't include the WRFU Tester rom and it won't work on DSi or 3DS consoles until it's patched. This is meant to be used with: https://github.com/Asaduji/DSpico-firmware-patcher
