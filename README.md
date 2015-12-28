# TeamCityClient
TeamCity v9 client using ServiceStack.Client with demo AppHost, still a work in progress.

### AMI Setup
1. Install TeamCity
2. Install [TeamCity.Node](https://github.com/jonnyzzz/TeamCity.Node) plugin
3. Add Default NuGet verison in TeamCity admin.
4. Add IIS + ASP.NET Role
5. Use Web Platform Installer to Add Web Deploy
6. Enable Web Deploy through IIS
7. Install NodeJS + NPM
8. npm install bower -g 
9. Install Git (v1.9.5 as v2.6.3 currently bugged causing "No working directory found")
10. Add `MSDeployPath` Environment variable
11. Create `CIWizard` user, add to `Administrators` group, disable RDP -> For IIS Management + CIWizard AppPool Account
12. Create `wizard_deploy` 'IIS Manager' user.
13. Add `ss.msdeploy.username` and `ss.msdeploy.password`


