Set-ExecutionPolicy Unrestricted -Scope Process

Run	uvicorn main:app --reload


Recap::
Import FastAPI.
Create an app instance.
Write a path operation decorator (like @app.get("/")).
Write a path operation function (like def root(): ... above).
Run the development server (like uvicorn main:app --reload).
