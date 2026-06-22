# Generation Notes

Mode: ai

Model: groq / llama-3.1-8b-instant

Fallback reason: OpenAI limit reached. Automatically switched to Groq.

Architecture: Content Writing Team

Template path: templates/multi-agent-ai/content-writing-team

Short description:

AI-powered content creation and review assistant for marketing teams

Architecture notes:

- Use containerization (Docker) for each microservice
- Implement API gateway for secure communication between microservices
- Use a message broker (e.g., RabbitMQ) for asynchronous communication

Project planner agent workflow:

- Architecture Agent: Define app boundaries, data flow, runtime stack, and integration points. Outputs: Use containerization (Docker) for each microservice; Implement API gateway for secure communication between microservices; Use a message broker (e.g., RabbitMQ) for asynchronous communication
- Backend Agent: Design FastAPI modules, service contracts, validation, and error handling. Outputs: Content Creation Agent: Generates marketing content using NLP and machine learning algorithms; Content Review Agent: Reviews generated content for quality and consistency; Approval Agent: Handles approval process for reviewed content
- Frontend Agent: Design React screens, state flow, controls, and user feedback states. Outputs: Content Creation Interface: Allows users to input content requirements and generate content; Content Review Interface: Displays reviewed content for approval
- Database Agent: Design persistence models, sample data, indexes, and audit records. Outputs: Run history; Source document metadata; Generated workflow audit records
- Testing Agent: Define contract tests, smoke tests, and generated project validation. Outputs: Unit testing, integration testing, and end-to-end testing using Pytest and Docker
- DevOps Agent: Define environment variables, Docker workflow, and repository packaging. Outputs: Docker-ready project; Environment sample file; GitHub repository upload
- Reviewer Agent: Review the generated plan for completeness, security, and portfolio quality. Outputs: Content Creation: Generate marketing content using NLP and machine learning algorithms; Content Review: Review generated content for quality and consistency; Approval: Handle approval process for reviewed content
