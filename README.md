# Sat-Trac

This is project has been created by students at Four County Career
Center in Archbold, Ohio. The initial project consisted of classes to
control stepper motors from the GPIO pins of a Raspberry Pi. The motors
are used to control the Azimuth and Elevation of two VHF/UHF antennas
in order to communicate with amateur radio satellites.

The initial project uses tracking data provided through the n2yo.com API.
Second-by-second azimuth and elevation data are downloaded and the motors
are driven to the correct positions, one at a time.

The initial alpha project was written by students in the class of 2024.
They were able to simulate and test the tracking , but their 
instructor had not completed the antenna construction to actually use them for
communication.

## Improvements To Be Made
- Fix bug when passing through 360 degrees
- Increase travel speed on initial tracking
- Dynamically adjust the tracking speed for smoothness
- GUI needs modified to use a dropdown for 'easy' satellites
- Use threading on the motor controls to simultaneously track elevation and azimuth.
- Downloading and storing Two Line Elements (TLE)
- Using TLE Data to generate tracking data offline (Piorbital)

## Contributors

### Class of 24
Blake Grime  
Kyle Hageman  
Cory Mavis  
Andy Mosier  