**README.md:**

# Sound Max Synthesizer - Prototype v1.0

## Overview
The Sound Max Synthesizer is a prototype version (v1.0) built on Max, employing FM synthesis techniques to delve into a diverse range of musical textures. It focuses on exploring timbral phenomena, particularly emphasizing attack time and micro-temporal effects. This project originated from musical analyses that integrated score information with audio descriptors to examine Ligeti’s compositions, providing a unique platform for investigating sound masses. To genetate the textures, parameters such as pitch and rhythm remain static, while the synthesizer explores attack and micro-temporal phenomena. The FM synthesis model employed in this version incorporates two modulating waves for a carrier, offering control over micro-temporal aspects. Additionally, traditional ADSR envelope techniques are utilized to manage attack time.

## Usage
- **Main File**: `_main_soundmas_fm.maxpat`
- **Integration Module**: `score_soundmass_fm.maxpat`

The integration modules contains the scripts for generating various temporal transformations in synthesis parameters. 

## Installation
1. Clone the repository to your local machine.
2. Open `_main_soundmas_fm.maxpat` in Max.

## License
This project is licensed under the [Creative Commons License](LICENSE).
