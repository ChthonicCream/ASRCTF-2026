Challenge Title: `hollow_proc`<br>
Author: `nmluan`<br>

Description:<br>
Threat response pulled a memory dump from WORKSTATION-7F2A after an EDR
alert fired on anomalous svchost.exe behaviour at 03:14 UTC. The process
was dead by the time the analyst got there, but the dump was clean.<br>

The acquisition tool bakes a process list and VAD snapshot directly into
the dump for offline triage. Something in there is not what it claims to be.<br>

Recover the flag hidden in the captured memory.<br>

Distributed file: svchost_420.dmp<br>
