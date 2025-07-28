# Nest.js Starter

This is a simple starter repository for Nest.js projects.  
Use it for hackathons or external projects as a boilerplate — clone and customize as needed.

## What's Included

### GitHub Actions

- **Release Please** – automated release management
- **Dependabot** – automatic dependency updates
- **Dependabot Validation** - automatic build check for dependabot PRs
- **CI** – basic continuous integration for build, tests, lint checks

### Database

- **MySQL**
- [**TypeORM**](https://typeorm.io)

## Notice

If you're using Dependabot, ensure the following setting is enabled:

> **Settings → Actions → General → Allow GitHub Actions to create and approve pull requests**

Add `.env.development` and `.env.production` to root directory to run. Fill in appropriate values for each.

```md
DATABASE_HOST=
DATABASE_PORT=
DATABASE_USERNAME=
DATABASE_PASSWORD=
DATABASE_NAME=
```
