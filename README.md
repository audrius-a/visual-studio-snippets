# visual-studio-snippets
Custom Visual Studio code snippets

## Usage

## Test

### xUnit test method with [Fact] attribute

Shortcut: `fact`

Output:
```c#
[Fact]
public async Task MyTestMethod_ShouldReturnValue_WhenValidParameterIsGiven()
{
    // Arrange


    // Act

    // Assert
}
```


### xUnit test method with [Theory] attribute:

Shortcut: `theory`

Output:
```c#
[Theory]
[InlineData(1)]
public async Task MyTestMethod_ShouldReturnValue_WhenValidParameterIsGiven(int value)
{
    // Arrange


    // Act

    // Assert
}
```
