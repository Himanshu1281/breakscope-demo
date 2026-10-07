# breakscope-demo

A test repository for the [BreakScope](https://github.com/Himanshu1281/breakscope) GitHub Action.

- `main` has `api/openapi.yaml` v1 and a small React/TypeScript frontend and Python backend that use it.
- `change-api` changes the spec: `User.name` becomes `full_name`, `DELETE /users/{id}` is removed, and `email` becomes required on `POST /users`.

Open a pull request from `change-api` into `main` to see the report.
