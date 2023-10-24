# PAVoice-Vietnamese-Text-To-Speech-dataset

PAVoice - Vietnamese Text-To-Speech Dataset for Community

## Overview

PAVoice is a comprehensive Vietnamese Text-To-Speech dataset recorded in March 2022 by a 23-year-old amateur female vocalist from the North of Vietnam. This dataset is provided to the community for research and development purposes. It offers a substantial collection of spoken sentences, totaling 1.9GB in size and 18.15 hours of audio.

## Dataset Composition

The dataset includes 11,256 sentences, each of varying lengths and covering diverse topics. These sentences were carefully selected from online newspapers to represent real-world use cases. The text was sourced from novels and short stories written by "Vu Trong Phung," and it is in the public domain, ensuring no copyright restrictions.

## Data Format

- Audio Format: The audio data is recorded in '.wav' format at 44.1 kHz and subsequently downsampled to 16 kHz. It uses a single channel with 16 bits per sample.
- Noise Reduction: The speech audio has been processed using the Facebook Denoiser to improve audio quality.
- Phonetic Alignment: The audio files have been passed through Montreal Forced Aligner (MFA) to obtain a .TextGrid file containing timestamps for each character in the text.

## Audio Samples

For a quick glimpse of the dataset, here's a sample:

- **Sample 1**:
  - Audio: 20310-20544_117_1408736_1409894.wav
  - Text: `sao em lại cười`

## Download

You can access the PAVoice dataset through the following link: [Download PAVoice Dataset](https://husteduvn-my.sharepoint.com/:u:/g/personal/son_lt173346_sis_hust_edu_vn/EeEEDikRLmBEpZNa9bIhlgkBW3UqJMU2sNEt52u_6Xmbtw?e=wLvOvB)

## Dataset Directory Structure

The dataset is organized as follows:

```
dataset
└── wav
    ├── 000000.wav
    ├── 000000.TextGrid
    ├── 000001.wav
    ├── 000001.TextGrid
    ...
```

## Dataset Statistics

- Number of Clips: 11,256 clips
- Total Audio Duration: 18.15 hours
- Shortest Audio Clip: 2.17 seconds
- Mean Clip Duration: 5.77 seconds
- Longest Audio Clip: 12.66 seconds
- Sampling Rate: 16 kHz
- Bits Per Sample: 16 bit
- Number of Channels: 1
- Mean Pitch: 226.63 Hz

## Screenshot

![Dataset Screenshot](https://user-images.githubusercontent.com/102223527/182779098-8685bb98-19ce-4cae-a6ce-6002c10f221f.png)

Please note that the audio data in this dataset is not intended for commercial use.

For any questions or concerns related to the dataset, you can contact [insert your contact information here]. We hope this dataset serves as a valuable resource for your research and development projects. Enjoy exploring the world of Vietnamese Text-To-Speech with PAVoice!
