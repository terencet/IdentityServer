To generate the sql script and for the console app to seed the database.
- Install the nuget package `Npgsql.EntityFrameworkCore.PostgreSQL`
- Update the connection string in `appsettings.json` to `Host=localhost;Database=auth2;Username=auth;Password=docker`
- Run ./schema.bat