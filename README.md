# PoSDBoS
Portable System to Detect Driver Drowsiness with Body Sensors

See the scientific project on [Research Gate](https://www.researchgate.net/project/Portable-System-to-Detect-Driver-Drowsiness-with-Body-Sensors) (paper and thesis only available in german)

## Goal
Driver drowsiness causes inattention and seconds sleep, it is responsible for many severe traffic accidents. According to Claudia Evers (Unterschätzte Risikofaktoren Übermüdung und Ablenkung als Ursache für schwere Lkw-Unfälle) every fifth accident is caused by driver drowsiness. Therefore detecting drowsiness is a task that can prevent accidents and save lives.
We propose a system that will alarm the driver and suggest to take a break, if it detects drowsiness. Earlier researches delivered good results with body sensors, especially with an EEG, but they often lack of portability and aren't easy to use. Therefore we decided to take a 14-channel EEG (EPOC Emotiv) to determine the current state of the driver (awake / drowsy). Our focus is to reduce the hardware environment and increase the comfort for the driver, so we can test it easily in a real car. An EEG is still an uncomfortable hardware and therefore it won't be used in production. But we can use our system to validate and improve other approaches, as it works very precisely. The whole system is implemented and tested at our driving simulator.

## Special thanks to
* [Emokit](https://github.com/openyou/emokit)
* [MNE-Python](https://github.com/mne-tools/mne-python)
