![macOS Monterey running on the T440p](https://dl.exploitox.de/t440p-oc/Hackintosh_T440p_V4.jpg)

<h3 align="center">Lenovo ThinkPad xx40 Series All In One - OpenCore Configuation</h3>
<p align="center">
    <a href="https://github.com/valnoxy/t440p-oc/"><strong>Go back »</strong></a>
    <br />
  </p>
</p>

![-----------------------------------------------------](https://dl.exploitox.de/t440p-oc/rainbow.png)

### Version 1.0.0 (MultimediaLucario) (09.26.2022)

- OpenCore to ```0.8.3```
- Kext Changes
  - New / Updated
    - Added USBInject.Kext
    - Updated AirPortItwlm.kext
- Config Changes
    - Changed from ```MacBookPro11,1``` to ```MacBookPro11,5``` 
- Other Changes
  - Added support for the Lenovo ThinkPad T440s, X240, T440, and L440. 

### Version 1.7.2 (05.03.2022)
- OpenCore to ```0.7.8```
- Kext Changes
  - New / Updated
    - Added VoodooRMI (issue #27)
    - AppleALC to ```1.6.9```
    - FeatureUnlock to ```1.0.6```
    - Lilu to ```1.6.0```
    - VoodooPS2Controller to ```2.2.7```
    - WhateverGreen to ```1.5.7```
- Config Changes
  - Disabled Kext ```VoodooInput.kext```

### Version 1.7.1 (07.02.2022)
- OpenCore to ```0.7.7```
- README: Add note for missing installer in boot picker (issue #40)
- Kext Changes
  - New / Updated
    - AppleALC to ```1.6.8```
    - FeatureUnlock to ```1.0.5```
    - Lilu to ```1.5.9```
    - VoodooPS2Controller to ```2.2.7```
    - WhateverGreen to ```1.5.6```
    - Replaced IntelBluetoothInjector with BlueToolFixup (issue #42)
- Config Changes
  - Added SystemAudioVolumeDB key ```(NVRAM -> Add -> 7C436110-AB2A-4BBB-A880-FE41995C9F82)```
  - Added PointerPollMask key ```(NVRAM -> Add -> AppleInput)```
  - Added PointerPollMax key ```(NVRAM -> Add -> AppleInput)```
  - Added PointerPollMin key ```(NVRAM -> Add -> AppleInput)```
  - Removed AudioOut key ```(UEFI -> APFS -> Audio)```
  - Added AudioOutMask key ```(UEFI -> APFS -> Audio)```
  - Removed MinimumVolume key ```(UEFI -> APFS -> Audio)```
  - Added DisconnectHda key ```(UEFI -> APFS -> Audio)```
  - Added MaximumGain key ```(UEFI -> APFS -> Audio)```
  - Added MinimumAssistGain key ```(UEFI -> APFS -> Audio)```
  - Added MinimumAudibleGain key ```(UEFI -> APFS -> Audio)```
  - Removed VolumeAmplifier key ```(UEFI -> APFS -> Audio)```

### Version 1.7.0 (25.12.2021)
- OpenCore to ```0.7.6```
- Kext Changes
  - New / Updated
    - AppleALC to ```1.6.7```
    - HibernationFixup to ```1.4.5```
    - Lilu to ```1.5.8```
    - VirtualSMC to ```1.2.8```
    - WhateverGreen to ```1.5.5```
    - Added RealtekCardReader
    - Added RealtekCardReaderFriend.kext
    - USBMap to ```1.0.1```
- Config Changes
  - New Model: ```MacBookPro12,1``` to ```MacBookPro11,4```
  - Removed Debug and verbose boot arg
  - SecureBootModel from ```Default``` to ```Disabled```
  - ScanTarget from ```67``` to ```3```
  - Removed outdated drivers

### Version 1.6.0 (25.10.2021)
- OpenCore to ```0.7.4```
- SSDT Changes
  - New / Updated 
    - SSDT-PLUG ```(source code included)```
    - SSDT-PNLF ```(source code included)```
    - SSDT-GPI0 ```(source code included)```
- Kext Changes
  - New / Updated
    - AppleALC to ```1.6.5```
    - CpuTscSync (new - syncing TSC, can improve performance)
    - HibernationFix (new)
    - Lilu to ```1.5.6```
    - VirtualSMC to ```1.2.7```
    - WhateverGreen to ```1.5.4```

### Version 1.5.2 (15.08.2021)
- Update Airportitlwm / itlwm to ```2.0.0```
- Update AppleALC to ```1.6.3```
- Update FeatureUnlock to ```1.0.3```
- Update IntelBluetooth to ```2.0.0```
- Update VirtualSMC to ```1.2.6```
- Update WhateverGreen to ```1.5.2```
- Remove Tools
- Remove SSDT-BAT (YogaSMC should work now)

### Version 1.5.1 (25.07.2021)
- Update Bluetooth kexts
- Add YogaSMC
- Support Sidecar and AirPlay for Mac
- Fix Audio & Microphone

### Version 1.5.0 (17.07.2021)
- Update OpenCore to ```0.7.1```
- Update USBPort.kext
- Change model to ```MacBookPro12,1```
- Add Tool (TpmInfo.efi)
- Remove Theme ([BsxDarkFencePinkPurple1](https://github.com/blackosx/BsxDarkFencePinkPurple1_))
- Remove Tool (ResetSystem.efi)

### Version 1.4.0 (30.06.2021)
- Update Kexts
- Update README
- Add multiple EFI's for different macOS Versions
- Add Heliport Version (Compatible with all macOS Versions)

### Version 1.3.0 (08.06.2021)
- Support macOS Monterey (Beta)

### Version 1.2.1 (03.06.2021)
- Fix Headphones buzzing noise

### Version 1.2.0 (02.06.2021)
- Add UltrabayHDD support
- Add Intel Bluetooth kext
- Add AppleALC kext
- Remove VoodooHDA kext

### Version 1.1.0 (21.04.2021)
- Add new Theme [BsxDarkFencePinkPurple1](https://github.com/blackosx/BsxDarkFencePinkPurple1_) (you can enable it by changing the value of ```PickerVariant``` to ```BsxDarkFencePinkPurple1_```)
- Add Tool (ResetSystem.efi)
- Update Kexts and drivers
- Update OpenCore (REL-069-2021-04-21)

### Version 1.0.1 (20.03.2021)
- Remove Tools
- Update Introduction

### Version 1.0.1 (14.11.2020)
- Fix Audio Jack

### Version 1.0 (14.11.2020)
- Initial Release
