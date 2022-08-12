# rvaft-remote-inspection
Repository for the experiments using RVAFT in a remote inspection case study (submitted to FMAS 2022).

Update the "log" variable in both `rvaft.yaml` line 29 and `rvaft_monitor.py` line 143 with the absolute path to where `log_rvaft.txt` is.

File structure:
- `rvaft.yaml` monitor configuration file
- `rvaft_monitor.py` monitor
- `log_rvaft.txt` execution log


Run our code with:
```bash
rosrun rvaft_monitor.py
```
