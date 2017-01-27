This is nearly identical to the repository "HealthVault Library for Windows 8" located at http://healthvaultwin8.codeplex.com/

This is based on their latest public version, 0.3-beta, published Jun 2013.  There is also a NuGet package with a similar name that is
published in 2014 with a different version number.  I couldn't make this NuGet package work in my UWP app despite compiling with no errors.
So I downloaded the source and converted the two projects to target Windows 10/Universal Windows.  Surprisingly, there were a couple of 
bugs that wouldn't allow the source to compile and I fixed those.

For now, you can clone this repository into your project, add the two projects and reference them into your app and it will work.

There is now also a NuGet package available.  Search for HealthVault.UWP

Documentation on using this library is fairly non-existent but if you pore through the Javascript sample provided in the original
repository, you can figure some things out.  
