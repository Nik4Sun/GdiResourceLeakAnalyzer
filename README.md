# GdiResourceLeakAnalyzer
This analyzer can be used as a console app or can be embedded into your code to find GDI leaks by means of static analysis. This project uses <a href="https://docs.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/">Roslyn APIs</a>.<br>

To use the console app, use **GdiResourceLeakAnalyzer/CodeAnalyzer/CodeAnalyzer/**. 
A core library containing all logic is contained in **GdiResourceLeakAnalyzer/CodeAnalyzer/CodeAnalyzers**/.
