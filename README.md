# devops-capstone-project

Customer Accounts REST microservice for the IBM DevOps Capstone Project. Built from the IBM starter template.

## Project scope

- Plan work with GitHub Issues, a Kanban board, and three sprints.
- Implement create, read, update, delete, and list REST APIs with Flask and PostgreSQL.
- Use test-driven development with at least 95% code coverage.
- Automate linting and unit tests with GitHub Actions.
- Add Talisman security headers and CORS policies.
- Containerize the service with Docker and deploy it to Kubernetes.
- Automate continuous delivery with Tekton.

## Development

Use the IBM Skills Network Cloud IDE provided by the course.

```bash
source bin/setup.sh
make install
make db
make test
make run
```

## Data model

Accounts contain id, name, email, address, phone_number, and date_joined.

## License and attribution

Licensed under Apache License 2.0. Starter code: IBM Developer Skills Network, John Rofrano. See LICENSE.
