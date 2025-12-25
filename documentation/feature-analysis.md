# Feature Overview Generator

**Use this when:** You jumped in without specs or plans, and you want a comprehensive overview of your feature's structure, key components, and documentation gaps.

**Skill Level:** Beginner to Advanced

---

## Copy This Prompt

```markdown
Review the conversation and artifacts relating to [feature] and create a comprehensive high-level snapshot that documents the structure, use, key components, and provides suggestions for improvements.

## Feature Overview Request:

Examine the Feature-related files, config values and chat history, and provide a detailed analysis. Save this analysis as a markdown file inside of `docs/deployment`. The analysis should include:

### 1. Feature Overview
- **Feature Name and Purpose**: What does this feature do?
- **Technology Stack**: Main languages, frameworks, and tools used
- **Feature Type**: Frontend/Backend components, UI enhancement, deployment or build-tooling, documentation
- **Target Audience**: Who is this built for?
- **Current Status**: Development stage, maturity level

### 2. Architecture Summary
- **Overall Architecture**: High-level feature design
- **Key Components**: Main modules, services, scripts, or features
- **Data Flow**: How data moves through the system
- **External Dependencies**: Third-party services, APIs, databases
- **Design Patterns**: Architectural patterns used

### 3. Feature Analysis
- **Core Features**: Main functionality provided
- **User Workflows**: Primary user journeys supported
- **API Endpoints**: Available APIs and their purposes (if applicable)
- **Database Schema**: Data models and relationships (if applicable)
- **Authentication**: Security and user management approach

### 4. Development Setup
- **Prerequisites**: Required tools, versions, dependencies
- **Installation Process**: How to get the feature running locally
- **Development Workflow**: How developers work with this feature
- **Testing Strategy**: Current testing approach and coverage (if applicable)
- **Code Quality**: Linting, formatting, quality gates (if applicable)

### 5. Documentation Assessment
Current documentation status and gaps:
- **README Quality**: Is the README comprehensive?
- **Code Documentation**: Inline comments and docstrings
- **API Documentation**: Endpoint documentation (if applicable)
- **Architecture Documentation**: System design documentation
- **User Documentation**: End-user guides and tutorials

### 6. Missing Documentation Suggestions
Identify and suggest locations for:
- **Product Requirements Document (PRD)**: Suggest adding link to `/docs/requirements/PRD.md`
- **Architecture Decision Records (ADRs)**: Suggest `/docs/decisions/` directory
- **API Documentation**: Link to `/docs/api/` or external docs
- **Deployment Guide**: Link to `/docs/deployment/` or deployment section
- **Contributing Guidelines**: Link to `CONTRIBUTING.md`
- **Changelog**: Link to `CHANGELOG.md`
- **Security Policy**: Link to `SECURITY.md`

### 7. Technical Debt and Improvements
- **Code Quality Issues**: Areas needing refactoring
- **Performance Concerns**: Potential bottlenecks or optimizations
- **Security Considerations**: Security gaps or recommendations
- **Scalability Issues**: Areas that might not scale well
- **Dependency Management**: Outdated or problematic dependencies

### 8. Feature Health Metrics
- **Code Complexity**: Overall complexity assessment
- **Documentation Coverage**: How well documented the feature is
- **Maintainability Score**: How easy it is to maintain
- **Technical Debt Level**: Amount of technical debt present

### 9. Recommendations and Next Steps
Prioritized suggestions for:
- **Critical Issues**: Must-fix problems
- **Documentation Improvements**: High-impact documentation needs
- **Code Quality**: Important refactoring opportunities  
- **Feature Gaps**: Missing functionality that should be added
- **Infrastructure**: Deployment, monitoring, CI/CD improvements

## Analysis Format:

Present the analysis as a structured document that could serve as:
- **Feature onboarding guide** for new team members
- **Technical overview** for stakeholders
- **Improvement roadmap** for the development team
- **Documentation audit** highlighting gaps
- **LLM-optimized Overview** for ai-assisted development

Focus on being comprehensive but concise - provide enough detail to understand the feature quickly while highlighting the most important aspects and improvement opportunities.
```

---

## Tips for Better Results

- **Run this on your entire repository** - make sure Cursor has access to all files
- **Use sparingly** - should only be needed if your did not plan/spec ahead of time
- **Share the output** - great for onboarding new team members
- **Act on suggestions** - use the recommendations to improve your feature
- **Combine with other prompts** - use suggestions to guide other documentation prompts
