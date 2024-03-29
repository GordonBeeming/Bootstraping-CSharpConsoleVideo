# Default C# project for a standard C# Video

A couple of files that I generally create each video I make, starting from a console app.

Videos are mostly posted to [youtube.com/@gordonbeeming](https://www.youtube.com/@gordonbeeming)

Don't forget to comment, like, and subscribe if you do drop by 😎

## Installing the template

To install the template, run the following command:

```bash 
dotnet new install GordonBeeming.Bootstraping.CSharpConsoleVideo
```

You'll see an update similar to this 

```bash
Template Name                              Short Name                            Language  Tags
-----------------------------------------  ------------------------------------  --------  -----------------------------
Console app files to bootstrap a C# video  gb-bootstraping-csharp-console-video  [C#]      .NET/CSharp/Console/Benchmark
```

## Using the template

Once installed, you can easily use the files by using the following command:

```bash
dotnet new gb-bootstraping-csharp-console-video
```

If you have any of the files already, you'll need to run the command with a `--force` argument.

## Checking for template updates only

If you already have the template installed you can run the following command to see if there is an update available

```bash
dotnet new update --check-only
```

To update all templates, remove the `--check-only` argument, to update this template only, run the install command again.

## Updating files to be included in the template

Updating files is simple... just add them and they should be published as `Bootstraping.CSharpConsoleVideo.nuspec` includes all files off the repository root.
