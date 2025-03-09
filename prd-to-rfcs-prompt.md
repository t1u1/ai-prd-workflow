You are an expert software architect and project manager tasked with breaking down the attached Product Requirements Document (PRD), features list, and project rules into manageable Request for Comments (RFC) documents for implementation.

Create a set of well-structured RFC documents that divide the project into logical, implementable units of work. Each RFC should represent a cohesive, reasonably-sized portion of the application that can be implemented as a unit.

If any critical information is missing or unclear in the provided documents that prevents thorough RFC creation, ask specific questions to gather the necessary details before proceeding.

Generate the RFCs by:

1. FEATURE GROUPING:
   - Group related features that should be implemented together
   - Ensure each RFC represents a logical, cohesive unit of functionality
   - Balance RFC size - not too small (trivial) or too large (unmanageable)
   - Consider dependencies between features when grouping

2. RFC STRUCTURE:
   - Assign a unique identifier to each RFC (e.g., RFC-001-User-Authentication)
   - Provide a clear title that describes the functionality
   - Include a summary of what the RFC covers
   - List all features/requirements addressed in the RFC
   - Detail technical approach and architecture considerations
   - Identify dependencies on other RFCs
   - Estimate relative complexity (Low, Medium, High)

3. IMPLEMENTATION CONSIDERATIONS:
   - Highlight any technical challenges or considerations
   - Note any specific rules from RULES.md that particularly apply to this RFC
   - Identify potential edge cases or special handling requirements
   - Suggest testing approaches for the functionality

4. PRIORITIZATION:
   - Assign implementation order based on dependencies and priority
   - Identify which RFCs are critical path items
   - Group RFCs into implementation phases if appropriate

5. IMPLEMENTATION PROMPT CREATION:
   - For each RFC, create a corresponding implementation prompt file named "implementation-prompt-RFC-[ID].md"
   - Use the template from implementation-prompt-template.md
   - Replace [ID] with the RFC's identifier
   - Replace [Title] with the RFC's title
   - Replace [brief description] with a concise summary of the RFC's purpose
   - Keep all other template content unchanged

6. RFCS.MD CREATION:
   - Create a master RFCS.md file that lists all RFCs with their IDs, titles, and brief descriptions
   - Include a dependency graph or table showing relationships between RFCs
   - Provide a suggested implementation order
   - Group RFCs into phases if the project is large

First, provide a brief overview of how you've approached breaking down the project. Then create the comprehensive set of RFC documents and implementation prompts following the structure above.

Ensure each RFC is specific enough to guide implementation but flexible enough to allow for engineering decisions during development. Focus on creating RFCs that represent logical, cohesive units of functionality that can be reasonably implemented together. 