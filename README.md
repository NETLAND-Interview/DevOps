# DevOps Challenge

## Project Structure

- Solution folder: `ChallengeSolution`
  - Project folder: `ChallengeProject`

### ChallengeProject

1. **WebAPI Application**: 
 - Create a .NET 8 WebAPI application within `ChallengeProject`.
 - The API should have 2-3 available actions.
 - Include Swagger for API documentation.
 - The WebAPI should be containerized.

2. **Unit Tests**:
 - Create a separate project named `ChallengeProject.Tests`.
 - Implement 2-3 simple unit tests.

## Environments and CI/CD Pipelines

1. **Development Environment**:
 - Automatically build and test the project after every commit to branches other than `main`.
 - Deploy the solution to `http://localhost:<random port assigned to branch>`.

2. **Production Environment**:
 - Automatically build and test the project after every commit to the `main` branch.
 - Deploy the solution to `http://localhost:8080`.

## Instructions

1. **Install GitLab Runner**:
 - The candidate must install GitLab Runner on their own computer.

2. **Deployment**:
 - The solution must be deployed on the candidate's own computer.

## Optional Task (For Extra Points)

1. **Implement Caching with Redis**:
 - Integrate Redis caching into the WebAPI application.
 - Deploy two containers: one for the WebAPI and one for Redis.
 - Ensure the WebAPI interacts with the Redis container for caching purposes.

Ensure your GitLab CI/CD configuration reflects these requirements and provides clear visibility into the build and deployment process.

Good luck!
 
