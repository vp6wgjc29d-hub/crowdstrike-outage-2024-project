# CrowdStrike Outage 2024 - Research Notes
# By Prashanthi Seelam

## What is CrowdStrike?
CrowdStrike is a US cybersecurity company. Their main product is Falcon - an antivirus software used by big companies, airlines, banks, hospitals to protect Windows computers from hackers.

## What Happened on July 19, 2024?
At 04:09 UTC, CrowdStrike pushed a faulty update to Falcon sensor. The update was Channel File 291. This file caused Windows computers to crash with Blue Screen of Death (BSOD).

The faulty file had a bug - it tried to read empty data and caused kernel driver to crash. This is called null pointer error.

## Timeline
- 04:09 UTC - CrowdStrike pushes update Channel File 291
- 04:30 UTC - First BSOD reports from Australia
- 05:00 UTC - Airlines like 【entity-Delta¦canonical_name=Delta Air Lines】, 【entity-American Airlines¦canonical_name=American Airlines】 start reporting problems
- 06:00 UTC - Banks, hospitals, 911 services down worldwide
- 08:00 UTC - CrowdStrike confirms issue and starts fix
- 12:00 UTC - Manual fix released - delete C-00000291*.sys file in Safe Mode

## Impact
- 8.5 million Windows devices crashed worldwide
- 1000+ flights cancelled - 【entity-Delta¦canonical_name=Delta Air Lines】 lost $500M
- Hospitals could not access patient records
- Banks could not process payments
- Total loss: $5.4 billion estimated
- Worst IT outage in history

## Sources
- CrowdStrike official blog
- 【entity-Microsoft¦canonical_name=Microsoft】 outage report July 2024
- 【entity-BBC News¦canonical_name=BBC News】 - July 19 2024"


