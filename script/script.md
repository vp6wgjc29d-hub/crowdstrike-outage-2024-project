# CrowdStrike Outage - Video Script
By Jasmeen Kaur

Introduction
Hello everyone, today we talk about CrowdStrike outage July 19 2024.
Biggest IT outage in history.
One small file broke 8.5 million computers.

Slide 6 - Root Cause
- File name: C-00000291*.sys
- Bug: Tried to read 21 fields but only 20 given
- Location: csagent.sys - kernel driver
- Error: Blue Screen
- Result: 8.5 Million PCs down

Slide 7 - How it was Fixed
- Boot Windows in Safe Mode
- Go to folder: C:\Windows\System32\drivers\CrowdStrike
- Delete file C-00000291*.sys
- Restart PC
- 【entity-Microsoft¦canonical_name=Microsoft】 released USB recovery tool
- Airlines fixed 1000s laptops by hand - took 3 days

Slide 8 - Lessons Learned
1. No testing before push
2. No staged rollout
3. Single point of failure
4. Kernel access too powerful
5. No rollback plan

Slide 9 - Prevention
- CrowdStrike: Now does validation and staged rollout
- 【entity-【entity-Microsoft¦canonical_name=Microsoft】¦canonical_name=【entity-Microsoft¦canonical_name=Microsoft】】: New security platform outside kernel
- Companies: Making offline backup plans

Slide 10 - Conclusion
One small file broke whole world.
Loss: 5.4 Billion dollars.
We need better testing and backup plans.
Thank you!
