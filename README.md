﻿﻿[![NuGet Downloads][nuget-shield]][nuget-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# ![Logo][Logo]

![Screenshot1][Screenshot1-url]

## Table of Contents

## Overview

This is a template for creating .NET projects. It includes a basic structure and some common files to get you started quickly.

Change TirsvadCLI/Dotnet.Template with the name of your project.
Change NugetPackageName with the name of your nuget package.

Add Doxygen to the project and add a script to generate the documentation.

In project file for library, add the following lines:
```xml
  <PropertyGroup>
    <VersionPrefix>0.1.0</VersionPrefix>
    <PackageId>$(AssemblyName)</PackageId>
    <Title></Title>
    <Authors>Jens Tirsvad Nielsen</Authors>
    <Company>TirsvadCLI</Company>
    <PackageIcon>logo.png</PackageIcon>
    <GeneratePackageOnBuild>True</GeneratePackageOnBuild>
    <RepositoryUrl>https://github.com/TirsvadCLI/Dotnet.Template</RepositoryUrl>
    <PackageTags>Console</PackageTags>
    <PackageReadmeFile>README.md</PackageReadmeFile>
    <PackageLicenseFile>LICENSE</PackageLicenseFile>
    <Description></Description>
  </PropertyGroup>
  <PropertyGroup>
    <IncludeSymbols>true</IncludeSymbols>
    <SymbolPackageFormat>snupkg</SymbolPackageFormat>
  </PropertyGroup>
  <ItemGroup>
    <None Include="..\..\image\logo\64x64\logo.png">
      <Pack>True</Pack>
      <PackagePath>\</PackagePath>
    </None>
    <None Include="..\..\README.md">
      <Pack>True</Pack>
      <PackagePath>\</PackagePath>
    </None>
    <None Include="..\..\LICENSE">
      <Pack>True</Pack>
      <PackagePath>\</PackagePath>
    </None>
  </ItemGroup>
```

## Features

## Getting Started

### Prerequisites

### Installation

#### NuGet Package

##### Windows

```Powershell
dotnet add package NugetPackageName
```

##### Linux

```bash
dotnet add package NugetPackageName
```

#### Clone the repo

![Repo size][Repos-size-shield]

```bash
git clone git@github.com:TirsvadCLI/Dotnet.Template.git
```


##### Windows

```Powershell
```

##### Linux

```bash
```

## Usage

### Notes

## Example of code

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Bug / Issue Reporting  

If you encounter a bug or have an issue to report, please follow these steps:  

1. **Go to the Issues Page**  
  Navigate to the [GitHub Issues page][GithubIssue-url].  

2. **Click "New Issue"**  
  Click the green **"New Issue"** button to create a new issue.  

3. **Provide Details**  
  - **Title**: Write a concise and descriptive title for the issue.  
  - **Description**: Include the following details:  
    - Steps to reproduce the issue.  
    - Expected behavior.  
    - Actual behavior.  
    - Environment details (e.g., OS, .NET version, etc.).  
  - **Attachments**: Add screenshots, logs, or any other relevant files if applicable.  

4. **Submit the Issue**  
  Once all details are filled in, click **"Submit new issue"** to report it.  

## License

Distributed under the GPL-3.0 [License][license-url].

## Contact

Jens Tirsvad Nielsen - [LinkedIn][linkedin-url]

## Acknowledgments

- [dotnet](https://dotnet.microsoft.com/)

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/TirsvadCLI/Dotnet.Template?style=for-the-badge
[contributors-url]: https://github.com/TirsvadCLI/Dotnet.Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/TirsvadCLI/Dotnet.Template?style=for-the-badge
[forks-url]: https://github.com/TirsvadCLI/Dotnet.Template/network/members
[stars-shield]: https://img.shields.io/github/stars/TirsvadCLI/Dotnet.Template?style=for-the-badge
[stars-url]: https://github.com/TirsvadCLI/Dotnet.Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/TirsvadCLI/Dotnet.Template?style=for-the-badge
[issues-url]: https://github.com/TirsvadCLI/Dotnet.Template/issues
[license-shield]: https://img.shields.io/github/license/TirsvadCLI/Dotnet.Template?style=for-the-badge
[license-url]: https://github.com/TirsvadCLI/Dotnet.Template/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jens-tirsvad-nielsen-13b795b9/
[nuget-shield]: https://img.shields.io/nuget/dt/NugetPackageName?style=for-the-badge
[nuget-url]: https://www.nuget.org/packages/NugetPackageName/
[GithubIssue-url]: https://github.com/TirsvadCLI/Dotnet.Template/issues/
[Repos-size-shield]: https://img.shields.io/github/repo-size/TirsvadCLI/Dotnet.Template?style=for-the-badg

[Logo]: https://raw.githubusercontent.com/TirsvadCLI/Dotnet.Template/master/image/logo/32x32/logo.png

[Screenshot1]: https://raw.githubusercontent.com/TirsvadCLI/Dotnet.Template/master/image/small/Screenshot1.png]
[Screenshot1-url]: https://raw.githubusercontent.com/TirsvadCLI/Dotnet.Template/master/image/Screenshot1.png
