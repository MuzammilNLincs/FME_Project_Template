# FME Project Template

## 📌 Purpose
This repository serves as a template for FME (Feature Manipulation Engine) projects.

## 🛠️ How to Use
1. Clone this repository.
2. Add your FME workspaces (.fmw files) to the `workspaces` directory.
3. Add any scripts or automation tools to the `scripts` directory.
4. Update this README with project-specific information.

## 📁 Structure
- `workspaces/`: Contains FME workspace files (.fmw).
- `scripts/`: Contains scripts for automation or data processing.
- `docs/`: Documentation and usage notes.

```
FME_Project_Template/
├── workspaces/                         # FME workspace files (.fmw)
├── scripts/                            # Automation or helper scripts
├── input/                              # Input datasets for testing or production
├── output/                             # Output results from FME workspaces
├── docs/
│   └── README.md                       # General usage and best practices
├── .gitignore                          # FME-specific ignore rules
└── .github/
    ├── pull_request_template.md        # Default PR checklist
    └── PULL_REQUEST_TEMPLATE/
        ├── new-workspace.md           # Template for new workspace PRs
        └── update-workspace.md        # Template for workspace updates
```

## 🧪 Testing
Use test datasets located in `/test/` (if applicable).

## 📌 Notes
- Follow the branching strategy: `main`, `dev`, `feature/*`.
- Use semantic versioning for releases.
