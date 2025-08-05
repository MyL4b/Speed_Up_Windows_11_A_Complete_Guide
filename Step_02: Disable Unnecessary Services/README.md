<h1 align="center">Disabling unnecessary background services</h1>
Disabling unnecessary background services can improve boot time, reduce background activity, and make your system run more smoothly.

### How to Disable Services:
1. Press Win + R to open the Run dialog.
2. Type services.msc and press Enter.
3. In the Services window, locate the service by typing the first few letters of its name.
4. Double-click the desired service to open its properties.
5. In the Startup type dropdown, select Disabled.
6. Under Service status, click Stop (if the service is currently running).
7. Click OK to apply the changes.
8. Repeat these steps for any other services you wish to disable.
---


### Services to stop:
| Service                        | Description                                                   |
|-------------------------------|---------------------------------------------------------------|
| **Windows Search**             | *Indexes files, emails, and other content on your PC to make searching faster.*  |
| **Themes**                    | *Manages visual styles and themes for Windows, including Aero and custom skins.*  |
| **Download Maps Manager**      | *Handles downloading and updating offline maps for Windows Maps.*  |
| **Geolocation Service**        | *Provides location data to apps using GPS, Wi-Fi, or IP location.*  |
| **Sys Main**                   | *Analyzes system usage and preloads frequently used apps into memory.*  |
| **Game Input Service**         | *Supports game controllers and input devices for UWP (Universal Windows Platform) games.*  |
| **Xbox Live Networking Service** | *Manages network communication for Xbox Live features and multiplayer gaming.*  |
| **Xbox Live Auth Manager**     | *Handles Xbox Live sign-ins and account authentication.*  |
| **Xbox Accessory Management Service** | *Supports Xbox controller firmware updates and configuration.*  |
| **Xbox Live Game Save**        | *Syncs game saves to the Xbox cloud.*  |
| **Connected User Experience and Telemetry** | *Collects and sends diagnostic and usage data to Microsoft.* |
| **Elan Service**               | *Manages Elan touchpad functions on laptops.*  |
| **Microsoft Edge Update Service** | *Automatically updates Microsoft Edge in the background.*  |
| **Update Orchestor Service**  | *Coordinates and manages Windows Update components.*  |
| **Print Spooler**              | *Manages print jobs sent to your printer.*  |
| **Diagnostic Policy Service** | *Detects and troubleshoots problems with Windows components.*  |
| **Windows Error Reporting Service** | *Collects and sends error reports to Microsoft.*  |
| **Backround Intelligent Transfer Service** | *Transfers files in the background for Windows Update and other apps.*  |
| **Intel System Usage Report** | *Sends system usage data to Intel for analytics.*  |
| **Performance Logs&Alerts**   | *Collects system performance data and triggers alerts when thresholds are exceeded.*  |
| **Retail Demo Service**        | *Used in retail display versions of Windows to showcase features.*  |
| **Windows Update**             | *Automatically downloads and installs Windows updates.*  |
| **Windows Event log**          | *Logs system, security, and application events.*  |
