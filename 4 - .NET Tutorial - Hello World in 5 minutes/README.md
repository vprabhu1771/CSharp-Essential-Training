# 1 - Create your app

```
Open Run Window -> CTRL + R
```

```
type cmd
```

```
type cd Desktop
```

In your command prompt, run the following command to create your app:

```csharp
dotnet new console -o MyApp -f net6.0
```

Then, navigate to the new directory created by the previous command:

```csharp
cd MyApp
```

What do these commands mean?

    The dotnet new console command creates a new console app for you.
    The -o parameter creates a directory named MyApp where your app is stored and populates it with the required files.
    The -f parameter indicates you're creating a .NET 6 application.
    The command cd MyApp changes your current directory to the one just created for the new app.



The main file in the MyApp folder is called `Program.cs`. By default, it already contains the necessary code to write "Hello, World!" to the Console. The following code shows the contents of this file when the project is created:

`Program.cs`

```csharp
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
```

# 2 - Run your app

In your command prompt, run the following command:

```csharp
dotnet run
```

Congratulations, you've built and run your first .NET app!