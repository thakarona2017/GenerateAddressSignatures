# GenerateAddressSignatures
This program is used to generate signatures for registering your WOLF addresses for the snapshot.

It is written in C# .Net Core, with publishing targets for Windows, MacOS, and Linux. These ready to use, compiled archives are located in the dist folder. Currently, Windows is the only operating system tested. We will get the MacOS and Linux versions tested soon.

### Downloads
[GenerateAddressSignatures-win10-x64.zip - Windows](https://wolfpackbotdownloads.azureedge.net/wolfpackbotdownloadscontainer/tools/GenerateAddressSignatures-win10-x64.zip)

### Instructions
1. Download the archive for your operating system.
2. Decompress the archive
3. Modify the parameters (see below) in run.bat (or run.sh depending on your operating system).
4. Execute run.bat or run.sh

### Run Parameters
1. Absolute file path to the wolfcoin-cli file.
2. Text file name (and optional full path) for the resulting output file that will contain all of your addresses with the signatures.
