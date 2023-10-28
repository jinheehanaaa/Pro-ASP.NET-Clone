
# CHAPTER 2
### Create Project ###
- dotnet new globaljson --sdk-version 7.0 --output FirstProject
- dotnet new mvc --no-https --output FirstProject --framework net7.0

# CHAPTER 3
### Create Project ###
- dotnet new globaljson --sdk-version 7.0 --output PartyInvites
- dotnet new mvc --no-https --output PartyInvites --framework net7.0

### nullable bool ###
- Can be true, false or null

### in-memory collection of objects ###
- Repository.cs

### Model Binding Concept ###
- HomeController.cs
- Before calling RsvpForm function, you give GuestResponse object to HTML form,
- then RsvpForm is called and they can be consumed by Repository.AddResponse Method as argument

# CHAPTER 4
### Create Project ###
- dotnet new globaljson --sdk-version 7.0 --output MySolution/MyProject
- dotnet new mvc --no-https --output MySolution/MyProject --framework net7.0
- dotnet new sln -o MySolution
- dotnet sln MySolution add MySolution/MyProject

### Managing NuGet Packages ###
- dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 7.0
- dotnet list package
- dotnet remove package Microsoft.EntityFrameworkCore.SqlServer

### Managing Tool Packages ###
- dotnet tool uninstall --global dotnet-ef
- dotnet tool install --global dotnet-ef --version 7.0
- dotnet ef --help

### Managing Client Side ###
- dotnet tool uninstall --global Microsoft.Web.LibraryManager.Cli
- dotnet tool install --global Microsoft.Web.LibraryManager.Cli --version 2.1.175
- libman init -p cdnjs
- libman install twitter-bootstrap@4.3.1 -d wwwroot/lib/twitter-bootstrap

# CHAPTER 5
### Create Project ###
- dotnet new globaljson --sdk-version 7.0 --output LanguageFeatures
- dotnet new web --no-https --output LanguageFeatures --framework net7.0
- dotnet new sln -o LanguageFeatures
- dotnet sln LanguageFeatures add LanguageFeatures

### Nullable Concept ###
-  ? = Null Conditional Operator
- ?? = Null Coalescing Operator







