# MathOps.Calculator

A simple .NET library exposing basic math operations via `MathCalculator`.

## Install

```bash
dotnet add package MathOps.Calculator
```

## Usage

```csharp
using Vishal.MathOperations;

var calculator = new MathCalculator();
int sum = calculator.Add(2, 3);        // 5
double sumD = calculator.Add(2.5, 3.1); // 5.6
```
