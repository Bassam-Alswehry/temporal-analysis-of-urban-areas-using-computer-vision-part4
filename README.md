# Temporal Analysis of Urban Areas — Part 4
##Interactive Visual Change Detection Tool (Gradio)
This part focuses on providing an interactive, user-facing AI tool that allows direct visual comparison between two images and generates interpretable, decision-ready outputs.

## Goal
Enable users to upload two images and instantly receive:
- A visual explanation of detected changes
- A structured decision-oriented output derived from computer vision analysis
The emphasis is on clarity, usability, and interpretability, not raw analytics.

## Key Outputs
- Visual change heatmaps highlighting structural differences
- Clear HUD overlays summarizing change severity and metrics
- Decision-oriented outputs (priority and recommended action)
- Structured payloads suitable for logging and downstream processing

## Role in the Project
This part represents the interactive tool layer, bridging the gap between:
- Core temporal change analysis (Part 1)
- Visual explanation logic (Part 2)
- Decision intelligence dashboards (Part 3)
It serves as the primary interface through which users interact with the system.

## Interaction Flow
- User uploads two images (Before / After)
- The AI engine analyzes structural changes
- Visual explanations and decision outputs are generated
- Results are logged for further analysis and enterprise use

## Technologies
- Python
- OpenCV
- NumPy
- Gradio
