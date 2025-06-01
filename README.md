# DXC Recruitment PFE Project

This project aims to automate the recruitment process using AI.

## Modules
- CV Information Extraction (NER with spaCy)
- CV-Job Matching (XGBoost, Optuna, SHAP)
- Personalized Interview Question Generation (DeepSeek LLM)

## Tech Stack
- Backend: FastAPI
- Frontend: Angular (to be developed in `frontend_angular`)
- Database: PostgreSQL
- MLOps: MLflow, Docker

## Setup
1. Ensure Poetry is installed.
2. Clone the repository (if applicable).
3. Create a `.env` file from `.env.example` (if provided) or the documentation and fill in your details.
4. Navigate to the project root (`DXC 4`) and run `poetry install` to install dependencies.
5. Initialize the database (e.g., using Alembic migrations).
6. Run the FastAPI application: `poetry run uvicorn dxc_recruitment_pfe.api.main:app --reload`
