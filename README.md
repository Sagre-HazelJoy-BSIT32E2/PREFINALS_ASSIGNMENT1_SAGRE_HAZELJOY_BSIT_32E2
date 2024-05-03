Project Overview:
Objective:
The objective of this project is to create a .NET Core Web API utilizing JWT (JSON Web Token) authentication and adhering to Onion Architecture principles. The solution comprises two projects: AuthServer, responsible for user authentication and JWT token generation, and ProtectedApi, exposing endpoints accessible only to authorized users.

Requirements:
Solution Creation: A solution named PREFINALS_AUTH_SAGRE_HAZELJOY containing two projects: AuthServer and ProtectedApi.
Dependencies Installation: Required NuGet packages installed in the AuthServer project for authentication and token handling.
Configuration: Setup of JWT signing key and app settings for authentication in the AuthServer.
Onion Architecture Implementation: Core, Infrastructure, and Presentation layers structured following the Onion Architecture principles in the AuthServer.
Protected API Configuration: JWT bearer token authentication setup in the ProtectedApi project to enforce authorization.
Protected Controller Implementation: Creation of a controller in ProtectedApi with endpoints accessible only to authenticated users.
Bonus:
Role-Based Authorization: Implementation of role-based authorization in the AuthServer.
Self-Assessment:
Onion Architecture:
Conceptual Understanding:
Onion Architecture: Yes.
MVC Pattern: Yes.
Web API: Yes.
Application & Bottlenecks:
Onion Architecture:
Benefits: Separation of concerns, testability, maintainability.
Bottlenecks (Encountered): No.
MVC:
Components: Model (data handling), View (user interface), Controller (logic handling).
Bottlenecks (Encountered): Yes. Tight coupling between Model and Controller can lead to difficulties in unit testing and managing logic changes.
Web API:
Differences from MVC: Yes. Web APIs focus on data exchange over HTTP, while MVC emphasizes user interface and interaction.
Bottlenecks (Encountered): No.
