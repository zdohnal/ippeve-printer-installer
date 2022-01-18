# IPP Everywhere Printer Installer
CLI script for local IPP Everywhere queue installation from a remote print server

## Requirements
- CUPS - 2.2 or newer, running service or socket units - for installing a queue locally
- CUPS command line tools:
  - lpadmin - for creating/deleting a print queue
  - lpstat - for listing print queues from server
- awk - for parsing lpstat output
- grep - for filtering a specific queue or pattern
- remote print server capable of IPP Everywhere - with CUPS 2.2 or newer
