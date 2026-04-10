# Smart Elevator Control System - Database Design
This project outlines a scalable database architecture for LiftGrid Systems to manage intelligent elevator platforms across large-scale commercial infrastructures.
Key Functionalities:
> Infrastructure Management: Supports multiple buildings, shafts, and floor configurations.
> Dynamic Ride Allocation: Maps real-time floor_requests to specific elevators and records completed ride_logs.
> Operational Monitoring: Tracks current elevator status (idle, moving, maintenance) separately from static configuration.
> Maintenance Logs: Keeps a historical record of repairs and technician notes without overwriting elevator history.
> Many-to-Many Logic: Handles complex floor-to-elevator servicing via a dedicated mapping entity.

Tech Stack:
Design Tool: Eraser.io
Notation: Crow's Foot ERD
