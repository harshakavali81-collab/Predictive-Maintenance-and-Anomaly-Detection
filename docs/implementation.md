# Predictive Maintenance and Anomaly Detection — implementation

Data generation → validation → train/test split → baseline comparison → evaluation → model serialization → FastAPI inference → unit tests.

Run `python engine.py train` then `python -m unittest discover -s tests -v`; serve `uvicorn api:app --reload`. Documentation and charts are synthetic local demonstrations, not external verification.
