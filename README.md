# EDR-Evasion

What is an EDR. - EDR is Endpoint Detection and Response Solution. which uses following techniques to identify threats.
1. Signature Detection - Here the EDR will try to find an available hash in the known database
2. Sandboxing - Before running an executable the EDRs will run the file in a virtual machine known as sandbox looking for known malwares through dynamic analysis if some of the OS APIs are not responding to virtualization the sandbox will evantually give up will let the executable run.
3. Active Detection - It is run by loading DLLs into each process to analyze suspicious behaviours that are not found previously.
4. Event Tracing - Others are proactive mitigations but event tracing is done reactively where the EDR looks for suspicious events that are happenning (example openning cmd.exe after opening a word file etc.)

https://ethicalchaos.dev/2020/05/27/lets-create-an-edr-and-bypass-it-part-1/
https://ethicalchaos.dev/2020/06/14/lets-create-an-edr-and-bypass-it-part-2/
