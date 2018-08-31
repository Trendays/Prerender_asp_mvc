1. Build solution
2. Make sure to have `NuGet.exe` and `CredentialProvider.VSS.exe` in the current folder
3. `./nuget pack .`
4. `./nuget push -Source "Trendays" -ApiKey VSTS Trendays.Prerender.io.{version}.nupkg`
