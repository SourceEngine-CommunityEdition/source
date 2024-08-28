# Source Engine: Community Edition

[![Build Status](https://github.com/SourceEngine-CommunityEdition/source/actions/workflows/build.yml/badge.svg)](https://github.com/SourceEngine-CommunityEdition/source/actions/workflows/build.yml)
[![Travis CI Status](https://api.travis-ci.com/SourceEngine-CommunityEdition/source.svg?branch=main)](https://github.com/SourceEngine-CommunityEdition/source/.travis.yml)

## Overview

Welcome to the **Source Engine: Community Edition**, an open-source project aimed at education and research, inspired by the 2017 leak of *Team Fortress 2*'s source code. The original leak is believed to have occurred privately in 2018 and was made public in 2020. This project serves as a learning platform for C++ development, game engine architecture, and modding, focusing on Valve's iconic Source Engine.

The Source Engine, which succeeded GoldSrc, was first introduced with *Half-Life: Source* in June 2004 and was later used in critically acclaimed titles like *Counter-Strike: Source* and *Half-Life 2*. Through this community-driven initiative, developers and enthusiasts can explore and understand the inner workings of one of the most influential game engines in history.

> **Please Note:** This project is strictly for **educational purposes**. It is neither endorsed by nor affiliated with Valve Corporation. The code provided is for learning and personal development only. Any commercial use or distribution of this code is prohibited.

For more information about the Source Engine, check out its [Wikipedia page](https://wikipedia.org/wiki/Source_(game_engine)).

## Important Notice

This repository is provided for **educational and research purposes only**. The content here is based on a leaked version of the Source Engine's code, which was not intended for public release. Therefore, the following terms apply:

- **No Commercial Use:** You may not use this code, or any derivatives thereof, for commercial purposes.
- **No Association with Valve:** This project is not affiliated with, endorsed by, or connected to Valve Corporation. Valve remains the rightful owner of the original Source Engine and all associated intellectual property.
- **Use at Your Own Risk:** The code is provided "as-is" with no warranties. By accessing or using this repository, you accept full responsibility for any consequences that may arise.

Should Valve Corporation or its representatives request the removal or modification of any content within this repository, we will comply promptly to respect their intellectual property rights.

## Getting Started

### Prerequisites

Before you begin, ensure that you have the following tools installed:

- **WAF Build System:** A powerful tool for compiling and managing the source code. Refer to the [WAF Book](https://waf.io/book) for detailed instructions.
- **Git:** For cloning the repository, including its submodules.
- **C++ Compiler:** This project has been tested with MSVC on Windows. Ensure you have an appropriate C++ compiler installed and configured.

### Cloning the Repository

To clone this repository along with its submodules, use the following command:

```bash
git clone --recurse-submodules git@github.com:SourceEngine-CommunityEdition/source.git
```

### Building the Source Engine: Community Edition on Windows

Once the repository is cloned, you can build the project using the WAF build system. Follow these steps:

1. **Configure the Build Environment:**

   Open a command prompt, navigate to the project directory, and run:

   ```cmd
   waf.bat configure
   ```

   This command configures the build environment, ensuring all dependencies are in place.

2. **Build the Project:**

   After configuration, compile the project with:

   ```cmd
   waf.bat build
   ```

   This process will generate the necessary binaries, such as `hl2.exe`, `tier0.dll`, and others.

### Need Help with WAF?

If you encounter any issues during the build process or have questions about using WAF, refer to the [official WAF documentation](https://waf.io/book) or seek assistance from the community.

## Contributing and Feedback

We encourage contributions to improve the Source Engine: Community Edition. Whether you're fixing bugs, enhancing documentation, or adding new features, your input is invaluable. To contribute:

1. Fork the repository.
2. Create a branch for your changes.
3. Submit a pull request once your changes are ready for review.

## Support the Project

If you'd like to support the ongoing development and maintenance of this project, consider contributing through the following platforms:

- **[Ko-fi](https://ko-fi.com/mykytashcherbyna)**
- **[Buy Me a Coffee](https://www.buymeacoffee.com/nsherbina1999)**
- **[Thanks.dev](https://thanks.dev/nsherbina1999)**
- **[Patreon](https://www.patreon.com/mykytashcherbyna)**
- **[PayPal Donation](https://www.paypal.com/donate/?hosted_button_id=9ETHFD5CQZVHL)**

Your support helps me continue learning, growing, and contributing to the open-source community.