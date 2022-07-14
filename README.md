![GitHub all releases](https://img.shields.io/github/downloads/SmokeyStack/texture_list-generator/total?style=for-the-badge)

# texture_list-generator
Welcome! Thank you for downloading SmokeyStack's Texture List Generator.

## What is this application for?
This application is used to generate a `texture_list.json` file for MC Bedrock add-ons. Why do we need that file? Learn more [here](https://wiki.bedrock.dev/concepts/texture-list.html)

## Prerequisites
- [Microsoft Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe) installed.

## Setup
- Download the latest release from the [Releases](https://github.com/SmokeyStack/texture_list-generator/releases) section. Unzip it somewhere.
- Run `texture_list_gen.exe` or `texture_list_gen`(Linux only) in a terminal to start the program.

## Compiling It From Source
If you don't feel comfortable downloading an `.exe` or a linux executable, you can compile this yourself.
- Download [JSON for Modern C++ version](https://github.com/nlohmann/json/releases). You can just download the `json.hpp` file.
- Compile it using this command in the terminal

```bash
g++ -std=c++17 Source.cpp json.hpp -o texture_list_gen
```

- Then execute the output file in the terminal

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
