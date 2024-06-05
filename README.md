# surge-xt-chord-strips
TouchOSC chord strip interface for Surge XT inspired by the chord strips in GarageBand

Currently, only minor key signatures are implemented.

- TouchOSC .tosc files are XML files that have been zlib compressed.
- An easy way to uncompress them is to open them in the TouchOSC editor and export to XML. zlib-flate is another option if you prefer.
- After modifying the XML file it can be opened in the TouchOSC editor by changing the file extension from .xml to .tosc.
    - The file does not have to be zlib compressed first.
    - The extension must be changed or the editor will complain.
- Notes are sent using OSC, so host address and ports must be configured in Surge and TouchOSC in order for them to communicate.

![screenshot](https://github.com/abelzile/surge-xt-chord-strips/assets/8238590/8ade704d-912d-4d50-b54f-1523f5145384)
