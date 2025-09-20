# Wingify-Software-AI-assignment
Debugged &amp; improved Financial Document Analyzer: fixed broken code &amp; inefficient prompts, added deterministic PDF analysis (word count, amounts, sections, sentiment). Built FastAPI API with /analyze, integrated Celery + Redis for concurrency, and /tasks/{id} to fetch results.


I’ve completed the debug challenge and made the following improvements:
Fixed all deterministic bugs and broken code references.
Replaced inefficient prompts with a deterministic PDF analyzer (word count, currency extraction, section detection, sentiment heuristic).
Built a FastAPI service with /analyze endpoint.
Added Celery + Redis queue to handle concurrent requests.
Implemented /tasks/{task_id} endpoint to check analysis status/results.Provided a clean requirements.txt and detailed README with setup & usage instructions.
