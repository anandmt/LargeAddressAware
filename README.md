[![NuGet package](https://img.shields.io/nuget/v/LargeAddressAware.svg)](https://nuget.org/packages/LargeAddressAware)

# LargeAddressAware
A build tools package that adds support for making 32-bit exes LARGEADDRESSAWARE

To use, install the NuGet package and set this property in your .csproj file:

```
  <PropertyGroup>
    <LargeAddressAware>true</LargeAddressAware>
  </PropertyGroup>
```

Also make sure that the .targets file from the NuPkg is included in your build. To do this, build your project using http://msbuildlog.com and search for "LargeAddressAware" in the structured log.
