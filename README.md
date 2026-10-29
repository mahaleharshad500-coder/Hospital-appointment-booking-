# Hospital Appointment System (MediFlow)

New ASP.NET Core MVC (.NET 8) web project using SQLite. No MySQL or XAMPP.

## Run in VS Code
1. Install .NET 8 SDK and open this folder in VS Code.
2. In Terminal:
   dotnet restore
   dotnet run --urls "http://localhost:5100"
3. Open http://localhost:5100 in Chrome.
4. Add a doctor and patient, then book an appointment.

Database file `hospital.db` is created automatically on first run.

This is a college demonstration, not a production medical system. It has no login, role security, or patient data protections. It does not migrate your previous MySQL data. Source generated without .NET SDK compile verification.
