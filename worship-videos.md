# Mode 2: Worship Video / No-Band Setup

## Use FreeShow for worship and announcements

Use **FreeShow** for general presentations, live worship lyrics, announcements, and worship videos when there is no band. Sermons use **PowerPoint**; see [presentations and sermon slides](presentations.md).

## Connect the laptop at the media desk

Without a band, worship videos play from the laptop and the Samson remains packed away. Speech microphones still use the Ui16 as needed.

**Reported route:** laptop 3.5 mm headphone output -> L/R splitter with two mono 6.35 mm plugs -> taped adapter with a stereo-style 6.35 mm plug -> DI input -> DI XLR output -> blue XLR -> **Ui16 input 11**. The DI and lead assembly live in the **yellow toolbox**.

The team has inspected the plugs: the L/R leads are mono-style, and the adapter has a stereo-style plug identified by its insulation rings. Electrical tape holds the assembly together. Preserve the assembly; do not pull it apart during setup.

A **DI box** is like a translator: it prepares a suitable source signal for the long XLR run to the mixer. Its **pad** reduces the signal. For this laptop route, set the DI channel's pad slider to **0 dB**, not a negative-dB position; an engaged pad is a known cause of very quiet laptop audio.

> **Plug type and DI compatibility are different checks.** Two insulation rings normally identify a three-contact TRS plug. That plug can carry stereo left/right or balanced mono, depending on the equipment. The team's inspection confirms the plug construction; the DI input design still determines how those contacts are used. A single ordinary balanced-mono DI input does not preserve stereo merely because a TRS plug fits it.

1. Keep Ui16 channel **11** muted and its fader fully down while connecting.
2. Connect the selected blue XLR between **DI XLR OUTPUT** and **Ui16 input 11**. Connect the assembly's large plug to the corresponding DI **INPUT**, and the 3.5 mm end to the laptop headphone socket. Set the DI pad to **0 dB**.
3. Connect the laptop charger to the small desk multiplug. Keep the Dell mixer-control device charging too. Silence notifications and prevent sleep during service.
4. Check the playback application's output device. HDMI audio can otherwise take sound away from the headphone socket. Test an actual FreeShow video, not only a system sound.
5. At low volume, test known left-only and right-only content and an actual worship video. Both sides must be audible without missing vocals, thin sound, hum or distortion.
6. **[TODO: DI model/input wiring and approved mono/stereo handling.]** One XLR into channel 11 carries a single balanced-mono feed, not two independent stereo channels. If the DI explicitly sums L/R, follow its instructions. If it has a normal balanced-mono input, have the lead confirm a proper summing device or laptop mono with one identified splitter branch and suitable mono wiring. Do not join headphone outputs with an ordinary Y adapter. Software mono alone does not correct stereo wiring into a balanced differential input, which can subtract the two sides.
7. Start laptop volume modestly and set channel 11 gain during soundcheck. Approved laptop volume/gain: **[TODO]**. Raise the main mix gradually after the wiring check. If distortion occurs, check source level and DI specifications rather than blindly increasing gain.

**Expected result:** FreeShow audio reaches both main speakers through channel 11, including content from both sides of the original track. Playing the same mono feed from two speakers does not make it stereo.

![Diagram Needed: Taped L/R mono plugs to stereo-style adapter, DI model and input wiring, XLR output and Ui16 input 11](images/laptop-mono-di-routing.png)

**[TODO: laptop OS, DI model/power requirements, confirmed summing or mono arrangement, normal laptop volume and cable ID.]**

---

[Back to home](README.md) | [Next: Presentations, Lyrics & Sermon Slides](presentations.md)
