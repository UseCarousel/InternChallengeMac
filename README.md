# Excel Natural Language Add-in Challenge (Mac OSX)

## Overview
Create a Mac OSX Excel add-in that can generate and modify Excel tables using natural language commands. This challenge is designed to test your ability to work with potentially challenging APIs, create scalable architecture, and deliver a functional product within constraints.

Time Limit: 48 hours

## Project Requirements

### Technical Stack
- Language: Python, TypeScript, or C# (note: C# may have limitations on MacOS)
- LLM Integration: Claude (key will be provided). Documentation [here](https://docs.anthropic.com/en/api/models-list) and tool calling [here](https://docs.anthropic.com/en/docs/build-with-claude/tool-use)
- Platform: MacOS Excel

### Core Features (Required)
1. Natural Language Table Generation
   - Must be able to create tables of strings (e.g., "Create a table of fire type pokemon" would yield a table with their evolves and abilities)
   - Minimum table size support: 4x5

2. Formula Integration
   - Must support basic Excel formulas
   - Example: "Create a table of monthly temperatures and calculate the average"
   - Should handle both data input and formula generation at the end

3. Command Interface
   - Minimum: Terminal-based or local web interface/taskpane for natural language input
   - Must provide clear feedback on command execution
   - Should handle basic error cases gracefully

### Optional Features
Choose any of these to implement based on your time and interests. You are NOT expected to implement all of these:

1. Formatting
   - Cell colors, font sizes, and styles
   - Context-aware formatting
   - Borders and layout enhancement
     
2. Streaming Command Execution

   - Implement progressive execution of LLM tool calls
   - Execute each complete function call as soon as it's received, rather than waiting for the entire response
   - Create a more interactive experience where users see changes happening in real-time
   - Note: Focus on tool-call level streaming rather than character-by-character update

3. Excel-Integrated UI
   - Task pane or modal dialog within Excel
   - Real-time feedback
   - Command history

4. Contextual Awareness
   - Support for multiple sequential commands
   - Ability to reference and modify existing content
   - Understanding of current worksheet context

5. Data Visualization
   - Basic chart generation
   - Chart customization
   - Multiple chart type support

6. Innovation
   - Feel free to add features you think would be valuable!

### Possible Technical Considerations (All optional - use whichever techincal intergations you'd like)
- We recommend checking out the JS for Excel API by microsoft. This should have some basic functionality and will create a taskpane for you to interface with your data. It is linked [here](https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview)
- If you want to go above and beyond that, you could consider Applescripts, Direct XML editing, or any other technique you can find. 
- Any successful implementation of Excel features not documented in the standard API will be viewed very positively

## Getting Started

### Prerequisites
- MacOS
- Excel for Mac
- Python 3.8+ or Node.js 16+ (depending on your choice)
- Git

### Setup Instructions
1. Fork this repository
2. Create a new branch with your name: `firstname-lastname`
3. Install required dependencies (document in your README)
4. Request Claude API key from jude@usecarousel.com

### Project Structure
Create a clear project structure that demonstrates good code organization. Consider:
- Separation of concerns
- Clean architecture principles
- Maintainable and scalable design

### Submission Guidelines
1. Create a new private repository using this template ("Use this template" button on GitHub)
2. Name your repository: `excel-challenge-[YourName]`
3. Add juderzzo as a collaborator
4. Complete your implementation
5. Ensure your repository includes:
   - Clear documentation on how to run your solution
   - Any known limitations or issues
   - List of implemented features (both required and optional)
   - Brief explanation of technical decisions
   - Screenshots/recordings of the working solution (if applicable)
6. Email [your email] with your repository link when complete

## Running the Project
Your solution should be runnable with minimal setup. Include clear instructions for:
1. Environment setup
2. Dependency installation
3. Running the application
4. Example commands/usage

## Evaluation Criteria
The most important criteria to consider is the functionality of the features you'd include. A project with only the required functionality working at 95% is a better submission that a project with all of the optional functionality working at 50%. While it might be tough to eliminate every single bug, we will first consider the robustness of any features before evaluating the breadth of optional implementations. This includes: 
   - Functionality of required features
   - Code quality and organization
   - Problem-solving approach
   - Documentation quality
   - Handling of edge cases
   - Creative solutions to API limitations

Remember: This is an open-ended challenge. You are encouraged to use all available resources (the internet, other git repos, AI, whatever you think will help you). While there are required elements, how you approach them and what additional features you choose to implement is up to you. We're interested in seeing your problem-solving process and technical creativity.

## Notes
- You are not expected to implement all optional features
- Focus on creating a robust solution for the core requirements first
- Document any assumptions you make
- Include information about testing you performed
- If you run into API limitations, document your workarounds

## Questions
Feel free to reach out as often as you'd like to jude@usecarousel.com. Questions are encouraged, and will be responded to. 

Good luck!
