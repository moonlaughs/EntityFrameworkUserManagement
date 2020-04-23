# EntityFrameworkUserManagemnet

![.NET Core](https://github.com/moonlaughs/EntityFrameworkUserManagement/workflows/.NET%20Core/badge.svg)

1. Create .Net Core Application with API
2. Add Docker
3. Create Database
4. Install packages in package manager
    PM> Install-Package Microsoft.EntityFrameworkCore.SqlServer
    PM> Install-Package Microsoft.EntityFrameworkCore.Tools
    PM> Install-Package Microsoft.EntityFrameworkCore.SqlServer.Design
    PM> Scaffold-DbContext 'Data Source=(localdb)\MSSQLLocalDB;Initial Catalog=UserManagement;Integrated Security=True;Connect Timeout=30;Encrypt=False;TrustServerCertificate=False;ApplicationIntent=ReadWrite;MultiSubnetFailover=False' Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models
    
5. Create New Scuffolded Item Controller
6. In UsersController change to: private readonly UserManagementContext _context = new UserManagementContext();

Created :D
