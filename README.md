# Society_Mngt-26-Jun-2026

You are tasked with adding a new frontend feature to [Project Name] while minimizing changes to the existing codebase. This feature development should be focused on the user interface layer, making **only** the necessary additions and modifications required to implement the specific frontend functionality.

**IMPORTANT: Make only the changes that are absolutely necessary to implement this frontend feature. Do not refactor, optimize, or modify existing code unless it is directly required for the new feature to work. Your goal is to add functionality with minimal disruption to the existing system.**

**FRONTEND OVERVIEW**

- **What's the specific frontend feature being added?** *Describe what the feature does from a user interface perspective and which users it benefits.*
- **What user interactions or workflows will this enable?** *Detail the specific user actions, flows, and expected behaviors.*
- **What pages/views/components will contain this feature?** *Identify where in the application this feature will appear.*

**DESIGN SYSTEM & COMPONENTS**

- **What design system components should be used?** *List specific components with exact filepaths (e.g., `src/components/Button/Button.tsx`).*
- **Which component variants, props, or configurations should be applied?** *Specify exact usage patterns from your design system documentation.*
- **What new components need to be created?** *List any custom components not available in the existing design system.*
- **How should components be composed together?** *Describe the component hierarchy and relationships.*

**API INTEGRATION & DATA FLOW**

- **What endpoint definitions will this feature use?** *List specific endpoints with their paths and methods.*
- **How should UI actions map to API calls?** *Explicitly define which user interactions trigger which endpoints.*
- **What's the data flow pattern?** *Specify when to fetch, how to cache, when to refresh, and state management approach.*
- **How should API errors be handled in the UI?** *Define error states, user messaging, and recovery flows.*

**SYSTEM BOUNDARIES**

- **What boundaries should we set for Blitzy during this frontend addition?** *Define limits (e.g., "only add/modify files in /src/features/[feature-name]" or "do not modify shared components").*
- **What existing UI functionality must remain completely untouched?** *Identify critical UI features that must continue working exactly as they do today.*
- **What's explicitly IN and OUT of scope for this frontend feature?** *Clarify boundaries to prevent scope creep.*

**MINIMAL CHANGE CLAUSE & DISCIPLINE GUIDELINES**

- **IMPORTANT: Make only the changes that are absolutely necessary to implement this frontend feature. Do not refactor, optimize, or modify existing code unless it is directly required for the new feature to work. Your goal is to add functionality with minimal disruption to the existing system.**
- **IMPORTANT: Follow these guidelines to ensure focused frontend development:**
    - Make only the minimal necessary changes to implement the feature
    - Do not modify components that are not directly related to this feature
    - Do not refactor existing components unless absolutely required
    - Do not change existing component interfaces or props unless specified
    - Isolate new code in dedicated files/components when possible
    - Use existing design system components wherever possible before creating new ones
    - When multiple implementation approaches exist, choose the one that requires the least modification to existing code
This project is for Society process management excluding security.
Added line

You are tasked with refactoring [Project Name] from its current implementation to [target implementation]. This refactor should maintain essential functionality while implementing the desired improvements and changes.

*Please provide specific technical references throughout (file paths, module names, class names, function signatures, API endpoints, etc.)*

**CORE OBJECTIVES**

*Define the business and technical goals driving this refactoring initiative.*

- **What are the primary goals of this refactoring initiative?**
- **What defines success for this refactor?**

**TARGET STATE DESCRIPTION**

*Provide a high-level description of what the refactored system should look like architecturally and functionally.*

- **Describe the target state of the refactored system**:
    - Technology stack (languages, frameworks, libraries, databases)
    - Overall architecture and design patterns
    - Key modules, components, and their relationships
    - External integrations and dependencies
    - Configuration and deployment approach
    - Any other architectural or technical considerations

**TECHNICAL IMPLEMENTATION DETAILS**

*Specify the detailed technical preferences, specific modules, APIs, and implementation approaches for achieving the target state.*

- **Which existing modules, classes, or components need to be modified, and how should they be changed?**
- **What external service integrations need to be implemented or updated?**
- **Are there any internal packages, libraries, or frameworks that the target state system depends on?**
- **What are the key interfaces, APIs, or contracts that need to be implemented?**
- **What are the most technically complex or challenging aspects of this refactor?**

**SYSTEM BOUNDARIES & CONSTRAINTS**

*Define what should remain unchanged and what functionality must be preserved during the refactor.*

- **What specific components, files, modules, or systems should not be touched during this refactor?**
- **What existing functionality must be preserved exactly as-is?**

**NON-FUNCTIONAL REQUIREMENTS**

*Specify quality attributes, operational requirements, and testing approaches for the refactored system.*

- **What performance, security, or compliance requirements must be maintained?**
- **What testing approach will ensure quality throughout the refactor?**
- **Are there specific operational requirements that must be considered?**
- **What areas of the plan would you like increased visibility into from the Agent Action Plan?**

**PRIVATE DEPENDENCIES + RUNNING THE CODE**

- **When building this project, do we need access to any internal dependencies, packages, or libraries?** *If yes, provide those within the repo(s) and reference these in the prompt.*
- **Are there any secrets, environment variables, or configurations required to compile and run the project successfully?** *List all non-sensitive configurations in the repository and reference where these are. For sensitive configurations, reach out to your AI Solutions Consultant directly to share securely.*
- **Do you have a complete, step-by-step set of build instructions that takes a developer from a clean machine to running the project?** *Provide build instructions directly here in the prompt. Additionally, if these instructions exist in documentation within your repo, indicate where this documentation lives. If submodules are used, confirm that their setup is documented in the parent repository.*

**MINIMAL CHANGE CLAUSE & REFACTOR DISCIPLINE GUIDELINES** *(Recommended for most Refactors)*

- IMPORTANT: Make only the changes that are absolutely necessary to implement this refactor.
    - Maintain existing functionality exactly as-is and do not modify code beyond what is directly required for the technology transition. Your goal is to preserve current behavior while updating the underlying technology with minimal risk and disruption.
- IMPORTANT: Follow these Refactor Discipline Guidelines to ensure safe technology transition:
- Make only the minimal necessary changes to implement the refactor
- Preserve existing functionality and behavior exactly as-is
- Do not modify code that is not directly impacted by the technology transition
- Do not enhance or optimize code beyond the requirements of the migration
- Isolate new implementations in dedicated files/modules when possible
- Document all technology-specific changes with clear comments.
- 
