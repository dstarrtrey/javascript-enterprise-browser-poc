Overview
========
This is the Feature Demo for Enterprise Browser. It uses AJAX to pull in the demo files so must be run from a WebServer. Therefore the installation instructions show how to enable the RE1 web browser in EB.

Installation
========
Android
------
1. Add this section to the Config.xml:

  ```xml
  <WebServer>
    <Enabled value="1" />
    <Port value="8082" />
    <WebFolder value="/fd/" />
    <Public value="1" />
  </WebServer>
  ```
2. Change the start page value to:

  ```xml
  <StartPage value="http://127.0.0.1:8082/feature-demo.html" name="Menu"/>
  ```
3. Copy the contents of this directory to a new folder called "fd" (case sensitive) on the root of the devices SDCard, or if it doesn't have an SDCard then copy it to the root of the internal memory partition.
4. Start Enterprise Browser

Windows
------
1.  Add this section to the Config.xml:

  ```xml
  <WebServer>
    <Enabled value="1" />
    <Port value="8082" />
    <WebFolder value="\fd\" />
    <Public value="1" />
  </WebServer>
  ```
2. Change the start page value to:

  ```xml
  <StartPage value="http://127.0.0.1:8082/feature-demo.html" name="Menu"/>
  ```
3. Copy the contents of this directory to a new folder called "fd" on the root of the device.
4. Start Enterprise Browser
