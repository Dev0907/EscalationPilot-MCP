# EscalationPilot MCP Project Structure

```
EscalationPilot-MCP/
│
├── README.md                          # Main project documentation
├── architecture.png                   # Architecture diagram (to be created)
├── architecture.txt                   # Text-based architecture diagram
├── architecture_description.md        # Diagram specifications
├── PROJECT_STRUCTURE.md              # This file
│
├── agents/                           # Agent prompt definitions
│   ├── orchestrator_prompt.txt      # Pro Agent - Master coordinator
│   ├── sentiment_prompt.txt         # Sub Agent - Sentiment analysis
│   ├── risk_prompt.txt              # Sub Agent - Risk detection
│   └── action_planner_prompt.txt    # Sub Agent - Action planning
│
└── screenshots/                     # Demo screenshots
    ├── README.md                    # Screenshot documentation
    ├── agent_setup.png             # Agent configuration demo
    ├── escalation_flow.png         # Workflow demonstration
    ├── risk_analysis.png           # Risk detection results
    └── structured_output.png       # Final report output
```

## Agent Architecture

### Pro Agent
- **Escalation Orchestrator**: Master coordinator that manages the entire workflow

### Sub Agents
- **Sentiment & Urgency Analyzer**: Detects emotional state and urgency
- **Risk Detection Agent**: Identifies fraud and legal risks
- **Escalation Action Planner**: Determines appropriate response actions

## File Purposes

- **agents/**: Contains the system prompts for each agent role
- **screenshots/**: Visual demonstrations of the system in action
- **architecture files**: Technical documentation and diagrams
- **README.md**: Investor-grade project documentation

## Implementation Notes

This structure follows enterprise software patterns:
- Clear separation of concerns
- Modular agent design
- Professional documentation
- Visual proof of concept
- Scalable architecture

Perfect for hackathon submission and potential investor presentation.