# rvaft-remote-inspection
Repository for the experiments using RVAFT in a remote inspection case study (submitted to FMAS 2022).

Update the "log" variable in both `rvaft.yaml` line 29 and `rvaft_monitor.py` line 143 with the absolute path to where `log_rvaft.txt` is.

File structure:
- `rvaft.yaml` monitor configuration file
- `rvaft_monitor.py` monitor
- `log_rvaft.txt` execution log
- `aft.rml` RML property
- `aft.py` RML oracle

Requires [ROSMonitoring](https://github.com/autonomy-and-verification-uol/ROSMonitoring) to be installed.

Run our code with (add paths where approriate to the arguments):
```bash
sh offline_monitor.sh aft.pl log_rvaft.txt
rosrun rvaft_monitor.py
```
