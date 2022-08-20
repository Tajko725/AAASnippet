# AAASnipped

## Summary

This is "code snippets" which can come in handy when writing tests in xUnit/NUnit, among others. I came up with this idea today while learning unit tests, from the fact that I didn't want to write AAA (Arrange, Act, Assert) every now and then, and I couldn't find a ready-made nuget that would have it, I decided to check on the Internet how you can write such a package and such a snippet yourself, after a few hours ready:). 
I tested it on Visual Studio 2022 Community, but on other versions it should also work.

This will save you a lot of time in creating unit methods on xUnit / NUnit framework.
![introduce movie](https://github.com/Tajko725/AAASnippet/blob/d83c3c45bda606ea661def69617a69af5a0736e1/AAASnippet/Assets/Demo.gif)

## How to install

1. Download "AAASnippet... .vsix" (Microsoft Visual Studio Extension) file from "Visual Studio Gallery" site.  
URL: https://marketplace.visualstudio.com/items?itemName=AAASnippet.AAASnippet
2. Open (double click on Explorer) the downloaded "AAASnippet... .vsix" file.
3. Then, "VSIX Installer" was launched. Please click "Install".

## How to use

### Display AAA (Arrange, Act, Assert)

- `a` [Tab]

Then, this snippet expanded following C# code.

```csharp
// Arrange


// Act


// Assert

```
### xUnit - Create Fact method with AAA

On C# source code in Visual Studio, you can insert **xUnit Fact method** by following key typing.

- `fa` [Tab]  

```csharp
[Fact]
public void MyTestMethod()
{
    // Arrange
    
    
    // Act
    
    
    // Assert
    
}
```

### xUnit - Create Fact method with DisplayName and AAA
- `fad` [Tab]

```csharp
[Fact(DisplayName = "MyTestMethod")]
public void MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### xUnit - Create Fact async method with AAA
- `fas` [Tab]

```csharp
[Fact]
public async Task MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### xUnit - Create Fact async method with DisplayName and AAA
- `fasd` [Tab]

```csharp
[Fact(DisplayName = "MyTestMethod")]
public async Task MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### xUnit - Create Theory method with AAA
- `ta` [Tab]

```csharp
[Theory]
public void MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### xUnit - Create Theory method with DisplayName and AAA
- `tad` [Tab]

```csharp
[Theory(DisplayName = "MyTestMethod")]
public void MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### xUnit - Create Theory async method with AAA
- `tas` [Tab]

```csharp
[Theory]
public async Task MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### xUnit - Create Theory async method DisplayName and AAA
- `tasd` [Tab]

```csharp
[Theory(DisplayName = "MyTestMethod")]
public async Task MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### NUnit - Create Test method with AAA
- `tta` [Tab]

```csharp
[Test]
public void MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

### NUnit - Create Test async method with AAA
- `ttas` [Tab]

```csharp
[Test]
public async Task MyTestMethod()
{
    // Arrange


    // Act


    // Assert

}
```

## Release Note

- v.1.0.0.2
  - First release, it contains `a, fa, fad, fas, fasd, ta, tad, tas, tasd, tta, ttas` snippet.

## Support
If you would like to somehow repay me for my work in the form of ramen, for example, you can find more information here (PL): [SuppMe](http://kurso-center.pl/wsparcie/)

## License

[GNU GPL v.3](LICENSE.txt)
