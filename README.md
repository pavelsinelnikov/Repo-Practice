#Gotcha's

If I'm missing roslyn/cs.exe when I run it (CTRL + F5), then

    1. Open __Tools>NuGet Package Manager>Package Manager Console...__
    1. Type `update-package Microsoft.CodeDom.Providers.DotNetCompilerPlatform -r`
    1. If you are still having problems, also type the following in the Package Manager Console:
        1. `update-package -reinstall`  