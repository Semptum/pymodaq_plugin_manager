# PyMoDAQ Plugin Manager

[<img src="https://img.shields.io/pypi/v/pymodaq_plugin_manager.svg">](https://pypi.org/project/pymodaq_plugin_manager/)
[<img src="https://readthedocs.org/projects/pymodaq/badge/?version=latest">](https://pymodaq.readthedocs.io/en/stable/?badge=latest)
[<img src="https://github.com/CEMES-CNRS/pymodaq_plugin_manager/workflows/Upload%20Python%20Package/badge.svg">](https://github.com/CEMES-CNRS/pymodaq_plugin_manager)


A plugin manager for PyMoDAQ, Modular Data Acquisition with Python.

Give a list of available, installable or updatable plugins compatible with pymodaq

# PyMoDAQ Plugins
|                                                          Repo Name                                                          |              Authors              |           Version plugin            |                                                                                                                                                                                                                                                                                                                                                                                                                       Instruments                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-----------------------------------------------------------------------------------------------------------------------------|-----------------------------------|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a href="https://pypi.org/project/pymodaq-plugins-orsay/" target="_top"># PyMoDAQ Orsay STEM and Camera plugin</a>          | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.1</a>  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| <a href="https://pypi.org/project/pymodaq-plugins-amplitude/" target="_top">Amplitude Lasers</a>                            | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin  Viewer0D ++++++++  * **AmplitudeSystemsCRC16**: Let you control the laser settings and grab info on the laser status (tested on a Satsuma)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| <a href="https://pypi.org/project/pymodaq-plugins-andor/" target="_top">Andor</a>                                           | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.4</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **Shamrock**: Shamrock series of spectrometer used as a monochromator  Viewer1D ++++++++  * **ShamrockCCD**: Shamrock series of spectrometer using the Andor CCD cameras * **ShamrockSCMOS**: Shamrock series of spectrometer using the Andor SCMOS cameras  Viewer2D ++++++++  * **AndorCCD**: Andor CCD camera using the SDK2 * **AndorSCMOS**: Andor CCD camera using the SDK3                                                                                                                                                                                                                                                                                                                                                                                      |
| <a href="https://pypi.org/project/pymodaq-plugins-femto/" target="_top">Femto Characterization</a>                          | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin  Viewer1D ++++++++  * **femto**: Fake detector mocking typically a spectrometer acquiring FROG traces   (but not limited to FROG)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| <a href="https://pypi.org/project/pymodaq-plugins-flim/" target="_top">Fluorescence Lifetime Imaging Microscopy</a>         | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin  ViewerND ++++++++  * **FLIM**: FLIM using piezoconcept XY stage and picoquant timeharp TH260"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| <a href="https://pypi.org/project/pymodaq-plugins-horiba/" target="_top">Horiba Spectrometers</a>                           | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin   Viewer1D ++++++++  * **Labspec6TCP**: Control of Labspec6 settings and acquisition using TCP/IP communication                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| <a href="https://pypi.org/project/pymodaq-plugins-daqmx/" target="_top">National Instrument DAQmx</a>                       | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.4</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **DAQmx**: Analog output DC, Sinus, Ramp...  Viewer0D ++++++++  * **DAQmx**: Analog acquisition, Counting  Viewer1D ++++++++  * **DAQmx**: Analog acquisition                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| <a href="https://pypi.org/project/pymodaq-plugins-newport/" target="_top">Newport Instruments</a>                           | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.3</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **Conex**: Piezo actuators from the CONEX-AGAP series" * **Newport_ESP100**: ESP100 motion controllers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| <a href="https://pypi.org/project/pymodaq-plugins-oceaninsight/" target="_top">Ocean Insight (Optics</a>                    | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin   Viewer1D ++++++++  * **Omnidriver**: Control of Spectrometer using the Omnidriver library (should be installed)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| <a href="https://pypi.org/project/pymodaq-plugins-physical-measurements/" target="_top">Physical Measurements Hardware</a>  | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.4</a>  | Below is the list of instruments included in this plugin   Viewer0D ++++++++  * **Keithley_Pico**: Pico-Amperemeter Keithley 648X Series, 6430 and 6514 * **Keithley2110**: Multimeter Keithley  2110 * **Lockin7270**: Lockin Amplifier Ametek 7270 * **LockinSR830**: LockIn Amplifier SR830  Viewer1D ++++++++  * **LecroyWaveRunner6Zi**: Oscilloscope LecroyWaveRunner 6Zi * **Tektronix**: Oscilloscope Tektronix MDO Series * **Picoscope**: Picoscope from Picotechnology  Viewer2D ++++++++  * **OpenCVCam**: Webcams control using the opencv library * **GenICam**: GeniCam compliant cameras suing the harvester libary * **TIS**: The Imaging Source TIS cameras                                                                                                                                                                           |
| <a href="https://pypi.org/project/pymodaq-plugins-physik-instrumente/" target="_top">Physik Instrumente Stages</a>          | <ul><li>Sebastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **PI**: All stages compatible with the GCS2 library * **PI_MMC**: old controller and stages using the 32 bits MMC dll (requires 32bit python)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| <a href="https://pypi.org/project/pymodaq-plugins-picoquant/" target="_top">Picoquant</a>                                   | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin   Viewer1D ++++++++  * **TH260**: Timeharp TH260 for *photon counting* and *time tagging*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| <a href="https://pypi.org/project/pymodaq-plugins-piezoconcept/" target="_top">PiezoConcept Stages</a>                      | <ul><li>Sebastien Weber</li></ul> | <a href="" target="_top">0.0.3</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **PiezoConcept** : piezoconcept stages (tested on BIO2.100) using the usual serial commands * **PiezoConceptPI**: Special firmware to emulate functions form the GCS2 library from Physik Instrumente                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| <a href="https://pypi.org/project/pymodaq-plugins/" target="_top">PyMoDAQ Plugins</a>                                       | <ul><li>Sébastien Weber</li></ul> | <a href="" target="_top">3.1.1</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * Mock actuator to test PyMoDAQ functionnalities * TCP server to communicate with other DAQ_Move or third party applications  Viewer0D ++++++++  * Mock detector to test PyMoDAQ functionnalities * Mock detector to test PyMoDAQ adaptive scan mode * TCP server to communicate with other DAQ_Viewer or third party applications  Viewer1D ++++++++  * Mock detector to test PyMoDAQ functionnalities * Mock detector to test pymodaq_spectro functionalities * TCP server to communicate with other DAQ_Viewer or third party applications  Viewer2D ++++++++  * Mock detector to test PyMoDAQ functionnalities * TCP server to communicate with other DAQ_Viewer or third party applications  ViewerND ++++++++  * Mock actuator to test PyMoDAQ functionnalities    |
| <a href="https://pypi.org/project/pymodaq-plugins-smaract/" target="_top">Smaract</a>                                       | <ul><li>David Bresteau</li></ul>  | <a href="" target="_top">0.0.3</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **SLC linear stages with sensor (S option) with MCS controller** * **SLC linear stages with sensor (S option) with MCS2 controller**   System requirements ===================  Operating system: Windows 7 or 10  Python: >=3.7  PyMoDAQ: >=3.1.2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| <a href="https://pypi.org/project/pymodaq-plugins-thorlabs/" target="_top">Thorlabs Instruments</a>                         | <ul><li>Sebastien Weber</li></ul> | <a href="" target="_top">0.0.2</a>  | Below is the list of instruments included in this plugin  Actuators +++++++++  * **Kinesis**: Kinesis serie (tested on K10CR1) * **Kinesis_Flipper**: Kinesis serie Flipper  Viewer0D ++++++++  * **Kinesis_KPA101**: Kinesis serie (position sensitive photodetector)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
