# Slides 6 to 10 - By Jasmeen Kaur

Slide 6 - Root Cause
- File: C-00000291*.sys
- Bug: Read 21 fields but only 20 given
- Crash in csagent.sys
- 8.5M PCs got Blue Screen
- Reason: No testing before worldwide push

Slide 7 - Fix
- Safe Mode
- Delete C-00000291*.sys
- Restart
- Microsoft USB tool
- Airlines took 3 days to fix all PCs

Slide 8 - Lessons
- No QA
- No staged rollout
- One vendor failure broke world
- Kernel too powerful
- No rollback

Slide 9 - Prevention
- CrowdStrike: validation checks, staged rollout
- Microsoft: new platform outside kernel
- Companies: offline backup

Slide 10 - Conclusion
- One file broke world
- Biggest IT outage
- $5.4B loss
- Need better testing
- References: CrowdStrike RCA Aug 6 2024

Images: media/bsod.png, media/airport.jpg
