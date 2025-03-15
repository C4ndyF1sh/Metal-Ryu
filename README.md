# Building

1. Download and install DotNet9 (https://github.com/C4ndyF1sh/Metal-Ryu/releases/download/1.0/dotnet-sdk-9.0.201-osx-arm64.pkg)
2. Download the ryujinx-metal file (https://github.com/C4ndyF1sh/Metal-Ryu/releases/download/1.0/ryujinx-metal.zip) and cd into the folder of it
3. execute **./distribution/macos/create_macos_build_ava.sh . publish_tmp publish ./distribution/macos/entitlements.xml 1.1.0 "result=$(git rev-parse --short HEAD)" Debug "-p:ExtraDefineConstants=DISABLE_UPDATER"**
4. Open the following directory: /ryujinx-metal/publish_tmp/publish_arm64
5. Run the Ryujinx executable

Or if you dont want to build it, just download the publish_arm64.zip file from here https://github.com/C4ndyF1sh/Metal-Ryu/releases/download/1.0/publish_arm64.zip
