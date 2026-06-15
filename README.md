# Pedal Manager

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

## About the Project

| ![Pedal Manager](https://github.com/fabemit/PedalManager_OS/blob/main/Images/fabOS-home.png) |
| :--------------------------------------------------------------------------------------------: |

Pedal Manager is the desktop companion for the custom sim-racing pedal project. It
lets you **calibrate the pedals, create and save custom profiles**, and tune
per-pedal settings (throttle, brake, clutch) over a serial connection.

---

## Features

- **Calibration** — set min/max travel and verify live pedal output.
- **Profiles** — create, save, and switch between per-game pedal profiles.
- **Per-pedal tuning** — independent throttle, brake, and clutch settings.
- **Serial connection** — talks to the pedal hardware over USB (`pyserial`).

---

## Getting Started

### Requirements

- Python 3.10+
- Dependencies in `requirements.txt`: `pyserial`, `pillow`.

### Installation

```bash
git clone https://github.com/fabemit/PedalManager_OS.git
cd PedalManager_OS
pip install -r requirements.txt
```

### Usage

```bash
python fabOS_Pedal_Manager.py
```

---

## Repository Contents

This repository is organised as follows:

- **`fabOS_Pedal_Manager.py`** — application entry point.
- **`pedal_settings.json`** — saved pedal configuration.
- **`fab.ico` / `fabPedal.png`** — application icon and image.
- **`*.spec`** — PyInstaller build specs (build output is gitignored).

Refer to the `CHANGELOG.md` for details about updates between versions.

---

## Learn More

### Documentation

Setup guides and reference material can be found here:
[ThisOldScot Docs](https://thisoldscot.com)
<!-- TODO: replace with the real docs URL when live -->

### ThisOldScot Community

ThisOldScot Community is a great space for the maker community — get answers to
your questions and solutions for our projects there.
<!-- TODO: add the real community/forum URL -->

### ThisOldScot Discord

Another option to get help and advice from other makers via the ThisOldScot Discord.
<!-- TODO: add the real Discord invite URL -->

---

## Contributing

Contributions are welcome! Here's how you can get involved:

- Submit pull requests to enhance the design or fix issues.
- Report bugs or problems by opening an issue.

We encourage community collaboration to make this project even better.

---

## About ThisOldScot

<img src="https://github.com/fabemit/PedalManager_OS/blob/main/Images/ThisOldScot_Logo.png" width="200" alt="ThisOldScot logo">

[ThisOldScot](https://thisoldscot.com) enjoys designing and making electronic
products and projects for enthusiasts, from hobbyists to professionals — boards,
sensors, hobby equipment, and anything else that catches my interest. Every
project is designed in-house and built on open-source hardware and software.

---

# Support the team
We :heart: doing research. New hardware (e.g. oscilloscopes, logic analysers,
servos, PCBs) is costly. Feel free to support us and accelerate our research.

Dev | ThisOldScot |
--- | --- |
Buy me a coffee | <a href="https://www.buymeacoffee.com/"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" height="20px"></a> |
Ko-fi | [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/) |
<!-- TODO: add the real Buy Me a Coffee / Ko-fi URLs -->

---

## License

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike
4.0 International License. Read more in the LICENSE file located in this repository.

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

---

**Disclaimer:**

This design is provided "AS IS", without warranty of any kind, either expressed or
implied. The entire quality and performance of what you do with the contents of
this repository is your responsibility. In no event will ThisOldScot be liable for
any damages or losses arising out of the use or inability to use the contents of
this repository.

> [!WARNING]
> Use responsibly and at your own risk.

---

## Have fun!

Thank you for your support from your fellow makers at ThisOldScot.

Happy Making!
