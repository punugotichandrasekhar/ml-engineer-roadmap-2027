# ML Engineer Roadmap — May 2027

A practical, portfolio-focused learning roadmap for an aspiring machine learning engineer, from October 2026 to May 2027.

## Targets
- Study approximately 20 hours weekly (Monday, Wednesday, Friday, Saturday)
- Build a consistent GitHub contribution history
- Complete end-to-end ML projects and deploy at least one model
- Practice coding, ML theory, and ML system design for interviews
- Apply to suitable ML engineer and related roles throughout preparation

## Roadmap overview
| Month | Focus | Deliverable |
|---|---|---|
| Oct 2026 | Python, Git, NumPy, pandas, SQL refresh | Python exercises + data analysis notebook |
| Nov 2026 | ML fundamentals, scikit-learn, evaluation | Reproducible classical ML project |
| Dec 2026 | PyTorch, neural networks | Deep learning mini-project |
| Jan 2027 | APIs, Docker, experiment tracking | Model served through an API |
| Feb 2027 | Cloud, CI, deployment, MLOps | Deployed end-to-end ML project |
| Mar 2027 | Specialization + portfolio project | Portfolio project v1 |
| Apr 2027 | Interview preparation + applications | Refined resume, projects, and interview notes |
| May 2027 | Final portfolio polish, interviews, applications | Job-search ready portfolio |

These are starter targets; adjust once a more detailed personal schedule is finalized.

## Structure
- `python-basics/`: exercises and scripting
- `ml-foundations/`: regression, classification, data prep, evaluation
- `deep-learning/`: PyTorch and neural networks
- `mlops/`: APIs, Docker, deployment and monitoring
- `projects/`: polished portfolio projects
- `interview-prep/`: coding, theory, system design
- `weekly-progress/`: weekly targets and results

## Windows PowerShell setup
```powershell
py --version
git --version
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python --version
```

If PowerShell blocks activation, use Command Prompt with `.venv\Scripts\activate.bat`, or run `.venv\Scripts\python.exe` directly.

## First check
```powershell
python python-basics/hello.py
```

## Git workflow
```powershell
git add .
git commit -m "Initial ML engineer roadmap setup"
git push -u origin main
```

Never commit `.venv/`, credentials, API keys or private datasets.
