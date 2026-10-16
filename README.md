# Software Defined Networking coursework

Computer-networking experiments, including finite-state-machine policy enforcement for SDN.
The original course workspace is under [Master/](Master/README.md).

## Workspace map

| Folder | Topic |
| --- | --- |
| `Master/assignment-2/` | Mininet topology and traffic measurements. |
| `Master/assignment-3/` | Parking-lot topology experiments. |
| `Master/assignment-4/` | Learning switch and test topology. |
| `Master/assignment-5/` | Bufferbloat, queue monitoring, and plots. |
| `Master/assignment-6/` | TCP Fast Open client/server experiments. |
| `Master/assignment-7/` | POX and Pyretic firewall/switch policies. |
| `Master/assignment-8/` | DDoS policy with a finite-state machine and sFlow events. |
| `Master/assignment-9/` | Multipath TCP topology and handoff experiments. |

## Environment

The scripts target an older Linux networking lab with Mininet, controller frameworks, traffic tools, and plotting dependencies.
Several files use Python 2 syntax and will not run unchanged under Python 3.
Some experiments require kernel features, root privileges, or external Pyretic/PyResonance modules absent from this repository.
There is no current one-command installation or cross-platform compatibility guarantee.
Inspect an experiment and recreate its dependencies in an isolated Linux VM before running networking or system-configuration scripts.
Captured results and figures are historical evidence, not a current benchmark.
