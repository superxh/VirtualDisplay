# VirtualDisplay
A compiled virtual display driver modified from Microsoft's sample driver -- IndirectDisplay

## Usage

1. Navigate to *VirtualDisplay/x64/Release*

2. Double click *IddSampleDriver.cer* and install the certificate manually to 

   *Certificates (Local Computer) > Trusted Root Certification Authorities*

3. Right click and run *IddSampleApp.exe* as administrator

4. Check windows device manager and install the driver for the unknown device

   Driver location: *VirtualDisplay/x64/Release/IddSampleDriver*

5. Now you could find the virtual display in your windows settings

6. Enjoy! 🐸

## Autostart

1. Create an .bat file

   ```
   START /MIN CMD.EXE /C C:\your_dir\IddSampleApp.exe
   ```

2. Set the provided .bat file a scheduled task with tasks scheduler

3. Enjoy! 🐸
