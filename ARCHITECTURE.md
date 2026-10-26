
# Architecture

## Current prototype
Browser UI (HTML + CSS)
        |
        v
JavaScript interaction layer
        |
        +-- Fictional train records
        +-- Demand sample data
        +-- Rule-based demo recommendation
        +-- Maintenance and alert rendering
        |
        v
DOM updates in the browser

## Design
- Presentation: HTML and CSS
- Application logic: JavaScript
- Data: in-memory arrays
- Visualization: CSS-based bar charts
- Persistence: none
- External APIs: none

## Future architecture
Frontend -> API service -> validated scheduling engine
                           -> database
                           -> forecasting model

Any future production version would need secure access controls, reliable data integration, timetable and safety constraints, monitoring, and expert validation.
