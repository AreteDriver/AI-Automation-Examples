# AI-Install-QA

Prototype repo to showcase **AI-driven install QA** using AR glasses and automation.

## Concept
- AR glasses guide team members step by step
- VIN scan + walkaround unlock vehicle
- Install steps tracked and signed off
- Torque specs, parts usage, and SOP validation enforced
- Short drive cycle validates final state before release

## Tech
- Python backend for scheduling and QA rules
- OR-Tools for install bay optimization
- Streamlit dashboard for visualization
- CI checks with pytest + flake8 + black

## Quickstart
```bash
pip install -r requirements.txt
python src/main.py
```