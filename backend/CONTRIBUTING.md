# Contributing to Gignex Backend

Thank you for your interest in contributing to the Gignex Backend API!

## Development Guidelines

1. **Fork & Clone**: Fork the repository and clone it to your local machine.
2. **Install**: Run `npm install` to grab the required packages.
3. **Branching**: Use feature branches. Example: `git checkout -b fix/api-latency`.
4. **Code Style**:
   - Use ES Modules (`import`/`export`).
   - Keep route handlers clean; delegate complex logic to controllers or services.
   - Comment heavily around the mock data generation logic.
5. **Testing**:
   - Manually verify API responses using tools like Postman or `curl`.
   - Ensure the server runs without errors via `npm start`.
6. **Pull Requests**:
   - Keep PRs focused on a single feature or fix.
   - Describe what changed and how to test it.

Happy coding! 🚀
