### ReachView changelog

#### v0.4.7

* Updated RTKLIB binaries to 2.4.3 b16 and added a couple of patches by rtklibexplorer

#### v0.4.6

* Updated **prnaccel** and **arlockcnt** values in default config files for better RTK results

#### v0.4.5

* Added log delete confirmation popup
* Added button to delete logs by day
* Correction logs are now present in the logs tab

#### v0.4.4

* Added RTKLIB integrity check on startup, which fixes the bug with logs not downloading properly
* Updated rtkrcv for better performance with dynamic filter on. 
* Updated rtkrcv send to more complete NMEA GGA to the base
* Improve startup time

#### v0.4.3

* Updated repository readme

#### v0.4.2

* Fixed lat-lon mix up in the status header

#### v0.4.1

* Fixed a bug with two solutions set to file
* Fixed a bug with conversion cancellation
* JS console inside the app now shows full RTKLIB status

#### v0.4.0

* Added support for UBX time marks when converting logs to RINEX

#### v0.3.4

* Fixed an issue with Solution output 2 not working by itself

#### v0.3.3

* Updated RINEX conversion timer to be more reailistic

#### v0.3.2

* Added space meter to the logs tab
* RINEX logs now include SNR, doppler frequency and more
* Minimized probability of Reach forgetting its state

#### v0.3.1

* Added Dynamic filter option to the rover's general tab.
* Fixed an issue where bluetooth.service file could be corrupted
* Added USB baud rate option

#### v0.3.0

* Added ERB protocol support for Pixhawk integration

#### v0.2.2

* Fixed not starting properly without an internet connection

#### v0.2.1

* Fixed an issue where users with older ReachView version could not update correctly

#### v0.2.0

* Added support for bluetooth scanning and pairing via ReachView
* Enabled bluetooth solution and log output

#### v0.1.4

* Added Emlid favicon to the app

#### v0.1.3

* ReachView will now show a blocking warning message when Reach is disconnected

#### v0.1.2

* Added more headers to disable caching in browsers

#### v0.1.1

* Set system time according to NTP(if available) or GPS on startup
* ReachView will start processing/logging until time is set

#### v0.1.0

* Updated log tab looks
* Added reboot and turn off wi-fi buttons to settings tab
* Added image version to settings tab
* Added RINEX version chooser to settings tab
* Serial ports are now are now chosen from a select control
* Bugfixes

#### v0.0.5

* Automatic log conversion to RINEX
* Fixed the issue, where base mode would not restart immediately
* Small visual updates and bugfixes

#### v0.0.4

* Default receiver settings have been changed
* You can now set used GNSS systems and solution frequency for both base and rover modes
* Multiple bugfixes and improvements

#### v0.0.3

* Moved the chart engine from [Chart.js](http://www.chartjs.org/) to [d3.js](http://d3js.org/)
* Added a separate "settings tab" with the update button and network information
* Pressing the update button now triggers an animation
* Minor visual updates to all tabs

#### v0.0.2

* Fixed internal issue preventing the units from getting "<font color="yellow">Float</font>" or "<font color="green">Fix</font>" solution statuses in RTK modes

#### v0.0.1

* First release

### Reach image changelog

#### v1.2

* Fixed the issue with unreliable Wi-Fi setup(mostly known as "Password does not match issue")
* Added various self-tests for corrupt internal software

#### v1.1

* Fixed the issue preventing Reach from booting with a radio connected to a DF-13 connector
* Changes to boot setup process

#### v1.0

* First release
