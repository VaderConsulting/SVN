# SVN

SVN is a saved working copy of two Visual Studio 2008 tests: HelloSVN-VBApp (VB.NET WinForms) and WindowsGame1 (C# XNA). HelloSVN-VBApp is a one-button Form1 whose Button1 click shows a "Hello SVN" message box; VS08Test.sln is bound to AnkhSVN. WindowsGame1 is the stock XNA Game Studio 3.1 Windows template: Game1 clears the back buffer to CornflowerBlue and exits on the game-pad Back button. This folder is that working copy, not a Subversion server.

**Source last updated:** 2009-07-12 · **Language:** VB.NET / C# · **Target:** .NET Framework 3.5 (Visual Studio 2008; XNA Framework 3.1) · **Output:** WinForms WinExe + XNA Windows game WinExe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `HelloSVN-VBApp` | VB.NET | WinForms WinExe | One-button Form1 that shows a "Hello SVN" message box |
| `WindowsGame1` | C# | XNA 3.1 Windows WinExe | Stock Game Studio template; Game1 draws CornflowerBlue |
| `Content` | C# (content pipeline) | XNA content project | Empty content pipeline nested under WindowsGame1 |

## How to open

Open `VS08Test/VS08Test.sln` in Visual Studio 2008 (or later with .NET Framework 3.5 targeting) for HelloSVN-VBApp. Open `WindowsGame1/WindowsGame1.sln` in Visual Studio 2008 with XNA Game Studio 3.1 for the C# Windows game. The two solutions are independent.

## Requirements

- Visual Studio 2008, .NET Framework 3.5

## Attribution and provenance

Working copy from my Historical Dev folder `SVN`. Both projects use Visual Studio template defaults: AssemblyCompany Microsoft, Copyright © Microsoft 2009. VS08Test.sln Format Version 10.00 (Visual Studio 2008) includes AnkhSVN SubversionScc; HelloSVN-VBApp targets .NET Framework 3.5 (ProductVersion 9.0.30729). WindowsGame1 targets .NET Framework 3.5 and XNA Framework 3.1 (Windows, x86).

## License

MIT. Copyright (c) 2026 VaderConsulting, for Dave Robinson's code. See `LICENSE`.
