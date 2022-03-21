# Blocks from a Receiver

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![CI](https://github.com/efabless/caravel_user_project_analog/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_user_project_analog/actions/workflows/user_project_ci.yml) [![Caravan Build](https://github.com/efabless/caravel_user_project_analog/actions/workflows/caravan_build.yml/badge.svg)](https://github.com/efabless/caravel_user_project_analog/actions/workflows/caravan_build.yml)

---


## OTA and detector blocks
 This design contains an envelope detector. This block is formed by an nfet_01V8 transistor and an RC filter. 
 ![image](https://user-images.githubusercontent.com/68408995/159381402-803a28c0-883d-476f-bc72-2213fe1d1e63.png)

The OTA block is a OTA is current mirror type with pfet transistors operating in strong and moderate inversion.
![image](https://user-images.githubusercontent.com/68408995/159381578-adb3f9a5-2f22-4620-8795-48c06b0e453b.png)
 
 
 The design implementation was based on the repository [caravel_user_project_analog](https://github.com/efabless/caravel_user_project_analog.git). 
Refer to [README](docs/source/index.rst) for this sample project documentation. 
