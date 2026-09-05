# HVAC Defrost & Controls Checklist (Educational)

Python **stdlib-only** CLI for commercial cooler/freezer defrost paths (time clock vs demand), with a step checklist and common failure notes.

> **Educational only — OEM controls vary.**  
> Verify with equipment manuals and wiring diagrams.

## Quick start

```bash
cd hvac-defrost-controls-checklist
python3 defrost_checklist.py --help
python3 defrost_checklist.py -i
```

### Freezer time-clock path

```bash
python3 defrost_checklist.py --box freezer --mode time-clock
```

### Cooler demand/adaptive path

```bash
python3 defrost_checklist.py --box cooler --mode demand
```
