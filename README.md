# LLuviaOS
## Official devices application

Devices repository: https://github.com/LLuviaDevices

Few things you should know before getting started:

### 1. Hosting

Our files are hosted on [SourceForge](https://sourceforge.net/projects/lluviaos-3-0/), you will receive access when you join the team.

### 2. Over-the-air (OTA) updates
Our system is automatic, you should not worry about updating some script, just upload the new build to [SourceForge](https://sourceforge.net/projects/lluviaos-3-0/) and send a pull request with the changelog and also edit your device JSON file (**builds/your_device_codename.json**) in [this](https://github.com/LLuviaDevices/official_builds) repository. Please read the ReadMe file on that repo.

Eg: Moto G 2015 is called **osprey**, so the device JSON file is **builds/osprey.json**

**Note:** New builds can take up to 30 minutes to appear on the site and in the OTA application.

### 3. JSON parameters
| Param | Description | Required |
|--|--|--|
| name | Device name | Yes |
| brand | Device manufacturer | Yes |
| codename | Device codename, eg: falcon | Yes |
| version_code | Version code, lowercase, eg: oreo | Yes |
| version_name | Version name, will be shown on download portal, eg: Oreo | Yes |
| maintainer_name | Your name | Yes |
| maintainer_url | Your personal URL, eg: https://github.com/srijith2001/ or https://forum.xda-developers.com/member.php?u=8350895 | No  |
| xda_thread | XDA thread URL, eg: https://forum.xda-developers.com/zuk-z1/orig-development/rom-lluviaos-v1-1-t3792422 | No |

**Please format your JSON code properly, [here](https://jsonformatter.curiousconcept.com/).**

### 4. Build type
You need to add 'export LLUVIA_BUILD_TYPE=OFFICIAL' in your build environment so that the OTA app will be included in your build.

### 5. Device tree
Maintainers should upload their device trees on https://github.com/LLuviaDevices

### Important Links:

- [Website](https://www.lluvia.ga/)
- [Download Center](https://downloads.aospextended.com/)
- [Apply for Official Device](https://goo.gl/forms/lad1qDHLKttcffei2)
- [Telegram Channel](https://telegram.me/LLuvia_Os/)
- [Official Devices](https://github.com/LLuviadevices/)
