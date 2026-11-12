# Digital Mixer Patch List & Control Guide (Soundcraft Ui16)

## Connect the tablet

The Ui16 has no physical faders. The tablet browser is its control panel: moving a screen slider tells the mixer what to do.

1. Power the Ui16 with speakers/amplifiers still off.
2. Open the tablet's Wi-Fi settings and join the approved mixer network. Name and secure password access: **[TODO]**. Do not remain connected only to the school internet network.
3. Open the browser and try the saved mixer quick link. If it fails, enter **http://10.10.1.1** or **http://ui-mixer.io** directly in the address bar, rather than searching. The tablet must be on the mixer network. Internet is not required; a no-internet warning can be normal.
4. Confirm the mixer page loads and controls respond. Before connecting audio sources, **mute all input channels and outputs and lower all channel/main/Aux master faders fully to minus infinity**. Check main and monitor views separately. **0 dB is not silence.** Set input gain separately during soundcheck.
5. Connect the Dell control-device charger; its battery life is short. Do not reset the mixer or change its network settings if a bookmark fails.

These local addresses are supported by [Soundcraft's getting-started guide](https://www.soundcraft.com/en-US/get-started/ui-series) and [HARMAN's Ui FAQ](https://help.harmanpro.com/en_US/sc-ui-series/ui-series-digital-mixers-faq). An external router may use a different address; confirm the local arrangement before changing settings.

![Photo Needed: Tablet Wi-Fi selection, mixer browser address and safely muted main and Aux views](images/tablet-mixer-connection.png)

| Connection detail | Approved value |
| --- | --- |
| Built-in Ui16 hotspot or external router | [TODO] |
| Wi-Fi name (SSID) | [TODO] |
| Wi-Fi password access | [TODO: secure location/contact] |
| Mixer browser address | Saved quick link; fallback http://10.10.1.1 or http://ui-mixer.io on mixer network |
| Backup control device and connection method | [TODO] |
| Approved saved setup for band / video | [TODO] |
| Firmware and date last checked | [TODO] |

**Keep live passwords out of this guide if it is publicly accessible.** Record the secure way volunteers obtain them instead. Do not factory-reset or change network settings during a service.

## Read the patch list

A **patch list** is the seating chart for cables: it tells you which source belongs in which socket. Laptop input 11 is confirmed; other input numbers still need confirmation. Add a row for each physical source once confirmed; do not treat these rows as a proposed channel order.

| Source / screen name | Ui16 physical input | Cable ID/colour | DI / adapter | Phantom power | Main mix | Aux 1 | Mode |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Laptop / media | 11 | Blue: [TODO ID] | Yellow-toolbox DI, pad 0 dB; taped adapter assembly, DI compatibility [TODO] | [TODO: DI requirement] | Yes | [TODO] | Videos/announcements; lyrics displayed during band worship |
| Speaking microphone(s), one row each | [TODO] | [TODO] | [TODO] | [TODO] | Yes | [TODO] | As required |
| Band vocal(s), one row each | [TODO] | [TODO] | [TODO] | [TODO] | Yes | [TODO] | Band |
| Band instrument(s), one row each | [TODO] | [TODO] | [TODO] | [TODO] | Yes | [TODO] | Band |

| Output | Destination | Cable / socket | Approved setting |
| --- | --- | --- | --- |
| Main L | Audiocenter left speaker, facing stage | XLR to INPUT 1; proposed MAIN-L label | Startup -60 dB; operating level/input mode/EQ [TODO] |
| Main R | Audiocenter right speaker, facing stage | XLR to INPUT 1; proposed MAIN-R label | Startup -60 dB; operating level/input mode/EQ [TODO] |
| Aux 1 | Samson powered mixer's line input | [TODO: cable + input] | [TODO: pre/post, input/master levels] |
| Other outputs | [TODO: unused or assigned] | [TODO] | [TODO] |

![Diagram Needed: Ui16 physical sockets and matching tablet channel names, including main L/R and Aux 1](images/ui16-patch-and-control-map.png)

## Use the essential controls

| Control | Beginner explanation | Safe use |
| --- | --- | --- |
| Input gain | Like the size of a doorway: sets how much source signal enters the mixer | Set during soundcheck with the loudest expected source; avoid red clipping |
| Channel fader | How much of one source enters the selected mix | Confirm whether you are viewing mains or Aux 1 before moving it |
| Main master | Overall congregation level | Start down and increase gradually; it does not replace Aux 1 control |
| Aux 1 send / master | Source amount / overall level for the monitor mix | Check sends and master separately; keep stage volume modest |
| Mute | Stops a signal at a particular point | Learn its effect on mains and monitors during soundcheck |
| EQ / effects | Tone shaping / added sound such as reverb | Leave approved settings alone until trained; excessive boosts encourage feedback |
| Saved setup / snapshot | Like a recipe card storing mixer settings | Recall only the approved version with outputs safe; ask before overwriting |

For full connection and control details, use the [official Ui16 product/manual page](https://www.soundcraft.com/en-US/products/ui16.html) and [Ui-series getting-started resources](https://www.soundcraft.com/en-US/get-started/ui-series.html). The Ui16 provides main outputs and four physical XLR Aux outputs; this system's confirmed monitor assignment is Aux 1.

## Photograph the approved speaker settings

Record both Audiocenter rear panels, including INPUT 1, the -60 dB startup level, the eventual operating level, input sensitivity/mic-line selection if present, and any tone/preset switches. Do not prescribe settings from an unverified model or assume a clock position is correct.

![Photo Needed: Both Audiocenter CA Jam Pack 15 rear panels showing approved sockets, switches and knob settings](images/audiocenter-rear-settings.png)

**[TODO: exact model label, final operating levels and other switches, Samson controls and lead sign-off. Left/right orientation, INPUT 1 and -60 dB startup are confirmed.]**

## Prepare sermon recording

During setup, insert the USB with the **ENH Build conference lanyard** into **MEDIA - REC**. It lives in the side pocket inside the laptop bag's main compartment. Check that the top-right record control above the main speaker sliders becomes available/fully coloured. Availability does not mean recording has started: follow the [recording checklist](sermon-recording.md).

---

[Back to home](README.md) | [Next: Digital Stock & Cable Inventory](inventory.md)
