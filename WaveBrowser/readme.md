# Remediation Script for WaveBrowser aka WebNavigator

## Steps to remediate

- Stops browser sessions
- Removes from filesystem.
- Removes scheduled task
- Removes registry keys

### Why two scripts?
I created an automated script that works well for a single local device. However, this script doesn't work with CrowdStrike, so I created a simplified script for this reason.

### Things to know
The CrowdStrike cloud script requires you to edit the username each time you need to run it. This is due to CrowdStrike's environmental variables.  Hopefully this will get resolved soon.