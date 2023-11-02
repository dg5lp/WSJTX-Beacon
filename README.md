# WSJTX-Beacon

Initial version of the WSJTX-Beacon.
This was tested with Q65 60sec mode, but should work with other 60 sec modes too.
Main features:
- It requires WSJT-X 2.6.1
- Sends in all even periods the first macro entry, whatever is entered. I suggest call-sign + QRA-loc.
- Listens in all odd periods an if a CALL received, replies with REP, wenn REP received replies with R-REP.
- All other message-types are ignored.  If nothing or invallid message receive continues with the macro.
- Does not creates ADIF-log, all messages are in ALL.txt.
- The Beacon stores all entries in the log-window in a new daily file, located in the ./log directory of installation
How to install and start the Beacon:
- Copy the exe into a directory, start it.  Enter your callsign and the used band. The band is only for information in log.
- Press the "Start" checkbox.
Important settings in WSJT-X.
- Basically the same settings should be used as for the FT8-Helper.
- Select the correct 60s moe and sub-mode.
- Switch off Auto-Seq.
- Deselect " "Prompt me log QSO" in the WSJT-X Reporting settings.
