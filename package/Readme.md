# MSBuild NuGet Package

In order to build the package, the root `bin` folder must contain the result of running both `build.cmd` on Windows, as well as `$ perl ./build.pl` on Mac.

Then, just run:

	nuget pack MSBuild.nuspec

To update the version, just update it in `MSBuild.nuspec`.
 
