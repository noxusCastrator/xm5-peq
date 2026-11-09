# XM5 PEQ

Adds parametric EQ presets to the ONIX XM5 while keeping its original music-management workflow.

Put compatible Equalizer APO or AutoEQ text presets on the TF card, then select them on a separate PEQ page. Keep using your existing music folders, playlists and file-copy tools. No desktop application or managed library format is required.

This standalone firmware is based on official V2.43. The current release is [0.1.0-a / PEQ08](https://github.com/noxusCastrator/xm5-peq/releases/tag/v0.1.0-a).

## Features

- Keeps the factory EQ and adds a separate PEQ page. Swipe left from the factory EQ page to open it.
- Independent switches for PEQ and the factory EQ. Can be used separately or together.
- Supports up to 30 active filters.
- PEQ supports local PCM playback up to 192 kHz. The factory EQ remains limited to 48 kHz. PEQ does not apply to DSD playback or USB DAC mode.
- The interface follows the factory XM5 style and supports Simplified Chinese and English.

## Use

For firmware installation, refer to the [XM5 TF-card update instructions provided by ONIX](https://onixhiend.co.uk/overture-firmware-update/).

1. Create an `EQ` folder at the TF card root. Place your presets inside it as UTF-8 `.txt` files.
2. Swipe left from the factory EQ page to open the PEQ page.
3. Tap `PEQ OFF` to open the preset list, then tap `Rescan` to scan for files.
4. Select a preset and enable PEQ.

See the [configuration documentation](docs/CONFIG_FORMAT.md) for preset formats and limits. To convert other formats, give an AI your EQ settings together with the [AI conversion guide](docs/AI_EQ_CONVERSION.md) provided by this project.

The original cover-loading and library-scanning paths are retained. Large artwork can still put pressure on the stock player. This firmware adds PEQ; it does not include the prepared-cover and card-synchronization system.

For a desktop music manager, editable playlists and favorites, prepared small covers, lyrics and card synchronization, use [XM5 Management](https://github.com/noxusCastrator/xm5-management) with its paired firmware. Choose the project that fits how you want to use your XM5.

## Warning

This is an unofficial alpha modification. PEQ08 was confirmed usable on one XM5 owned by the author. That does not guarantee installation or operation on another device. Flashing can cause data loss or boot failure, and repairs may be necessary. Physical recovery after a failed flash has not been validated for this release.

Before flashing, back up your data and keep the official recovery package and instructions.

Excessive EQ gain can cause clipping or distortion, especially when both EQ layers are enabled. Keep the preset's preamp setting and lower it further if necessary.

Thanks to Shanling for their technical support.
