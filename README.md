Experiment with automated android building.

My phone is no longer supported by the lineageos people, however they have
instructions for those who want to try it themselves:

    https://wiki.lineageos.org/devices/herolte/build

This repo codifies those instructions into an automated build.

Current Status:
- gitlab CI: The build VM only has 16Gig disk space available - and fills it
- travis CI: the job exceeds the default maximum time limit of 50 minutes
