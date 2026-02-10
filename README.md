Collaboration Guidelines
1. Branching Strategy
• Main Branch: Always stable. No direct commits.

• Feature Branches: Use `feature/name`, `fix/issue-id`, or `chore/task-name`.

• Merge Policy: All changes must go through a Pull Request (PR).

2. Commit Message Standards
We follow Conventional Commits:

• `feat:` A new feature.

• `fix:` A bug fix.

• `docs:` Documentation only changes.

• `style:` Changes that do not affect the meaning of the code (white-space, formatting, etc).

• `refactor:` A code change that neither fixes a bug nor adds a feature.

3. Pull Request (PR) Process
• Self-Review: Review your own code before requesting others.

• Description: Explain the why and how. Link to relevant issues (e.g., `Closes #123`).

• Reviews: At least one approval is required. Address all comments before merging.

• Keep it Small: Focus on one logical change per PR.

4. Code Review Etiquette
• Be Constructive: Provide clear feedback and suggestions.

• Stay Objective: Focus on the code, not the person.

• Communication: Use "Draft PRs" for early feedback on work-in-progress.

5. Documentation
• Update the `README.md` if setup steps or dependencies change.

• Comment complex logic within the code.

#installation guide for project dependencies management
   #installation of pipx
   python -m pip install --user pipx
   python -m pipx ensurepath
   
   #installation of poetry
    pipx install poetry

   #intialize the poetry
    poetry init
   
   #creating virtual environment
    poetry install

   #activation virtual environmen
    path/Scripts/activate.ps1


#installing dependencies
 poetry add Django,djangorestframework

#project creation
 poetry run django-admin startproject <project name>

#creating apps
 poetry run python manage.py startapp <project name>