# WSJTX-Beacon

Initial version of the WSJTX-Beacon.
This was tested with Q65 60sec mode, but should work with other 60 sec modes too.
Main features:
- Sends in all even periods the first macro, whatever is entered. I suggest call-sign + QRA-loc.
- Listens in all odd periods an if a CALL received, replies with REP, wenn REP received replies with R-REP.
- All other message-types are ignored.  If nothing or invallid message receive continues with the macro.
- Does not creates ADIF-log, all messages are in ALL.txt.
- The Beacon stores all entries in the log-window in a new daily file, located in the ./log directory of installation
