# SMARTNEST Requirements

**Author:** Suma  
**Status:** Initial design draft

## Functional requirements
- FR-01: The application shall show a menu of prototype actions.
- FR-02: The application shall display simulated temperature and light-level readings for demo rooms.
- FR-03: The application shall display the status of simulated devices.
- FR-04: The user shall be able to change a simulated device state.
- FR-05: The application shall validate device indexes and requested states.
- FR-06: The application shall clearly indicate that no physical hardware is connected.

## Non-functional requirements
- NFR-01: Use modular Java classes and encapsulated fields.
- NFR-02: Provide clear validation and error messages.
- NFR-03: Keep the starter version safe by limiting device actions to in-memory simulation.
- NFR-04: Document setup and test instructions.
- NFR-05: Do not store passwords, tokens, or private household information in the repository.

## Out of scope
- Real mains-powered appliance control.
- Real sensor readings or cloud connectivity.
- Mobile application and production authentication.
- Security-critical home automation.
