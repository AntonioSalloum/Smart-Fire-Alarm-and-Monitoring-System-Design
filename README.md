# Fire and Security Alarm Monitoring System — SRS
- Software Requirements Specification for a system that monitors and controls fire and security alarms in a large building. Built for CSI 308 (Software Engineering and Systems Design).
This is a requirements & design project, not an implementation. The deliverable is the SRS document and supporting diagrams below.

- What the system does:
- The building is split into zones, each with its own alarms.
- Alarms are normally checked by a manned control area, but if unmanned, serious alarms automatically call emergency services.
- On a confirmed fire alarm: exit lights turn on, an audible alarm sounds, and sprinklers activate — but only in rooms with no people in them.
- On a security alarm: internal doors lock automatically. Whole zones can be isolated this way.
- False alarms are common, so alarms must be confirmed (e.g. by multiple sensors) before alerting emergency services.


# Diagrams

- DiagramFileUse Case Diagramdiagrams/use-case-diagram.pngContext Diagramdiagrams/context-diagram.pngSequence Diagram — In Case of Alertdiagrams/sequence-incase-of-alert.pngState Machine Diagramdiagrams/state-machine-diagram.png

# SRS Contents
- Case Description
- Software Process Model
- Requirements Specifications
- Architectural Design (diagrams above)
- Software Testing
- Conclusions and Future Work


# Full document: 
- SRS.docx
# Course:
- CSI 308 – Software Engineering and Systems Design, AUST, Fall 2025–2026