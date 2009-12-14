
About
------------------
Mac OS X service to convert audio files' sample rates and resolutions using SoX.


Installation
------------------
1) Download Mac OS X SoX executable from http://sox.sourceforge.net/
2) Unzip the file
3) Using Terminal, type:
    sudo cp "path/to/sox" "/usr/bin/"
4) Double-click "Convert sample rate and resolution.workflow"
5) Choose File > Save As
6) Hit return when prompted for a name


Usage
------------------
1) Select one or more audio files
2) Right-click selection and choose "Services > Convert sample rate and resolution"
3) Follow the prompts

The service will save output files to the same directory as the inputs files.  Output files will be named input_file_name-samplerate-bitres.extension.

Example:
Converting input.wav to 192 kHz/24 bit will create a file in the same directory named input-192khz-24bit.wav.


Contact
------------------
Stephen Norum
stephen@mybunnyhug.org

