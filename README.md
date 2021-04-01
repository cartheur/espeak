# espeak
Mirror of main eSpeak SourceForce subversion repository

espeak is the staple when it comes to a simple implementation of synthetic voices.

eSpeak is a compact open source software speech synthesizer for English and other languages, for Linux and Windows.
eSpeak uses a "formant synthesis" method. This allows many languages to be provided in a small size. The speech is clear, and can be used at high speeds, but is not as natural or smooth as larger synthesizers which are based on human speech recordings.

eSpeak is available as:

* A command line program (Linux and Windows) to speak text from a file or from stdin.
* A shared library version for use by other programs. (On Windows this is a DLL).
* A SAPI5 version for Windows, so it can be used with screen-readers and other programs that support the Windows SAPI5 interface.

Features.

* Includes different Voices, whose characteristics can be altered.
* Can produce speech output as a WAV file.
* SSML (Speech Synthesis Markup Language) is supported (not complete), and also HTML.
* Compact size. The program and its data, including many languages, totals about 2 Mbytes.
* Can be used as a front-end to MBROLA diphone voices. eSpeak converts text to phonemes with pitch and length information.
* Can translate text into phoneme codes, so it could be adapted as a front end for another speech synthesis engine.
* Potential for other languages. Several are included in varying stages of progress. Help from native speakers for these or other languages is welcome.
* Development tools are available for producing and tuning phoneme data.
* Written in C.

----

espeakedit is a GUI program used to prepare and compile phoneme data. It is now available for download at: http://espeak.sourceforge.net/test/latest.html

----

History: Originally known as speak and originally written for Acorn/RISC_OS computers starting in 1995. This version is an enhancement and re-write, including a relaxation of the original memory and processing power constraints, and with support for additional languages.
