# BannedApiAnalyzers

```
<PackageReference Include="Microsoft.CodeAnalysis.BannedApiAnalyzers" Version="3.3.3">
    <PrivateAssets>all</PrivateAssets>
    <IncludeAssets>runtime; build; native; contentfiles; analyzers</IncludeAssets>
</PackageReference>
```

```
<ItemGroup>
    <AdditionalFiles Include="BannedSymbols.txt" />
</ItemGroup>
```

BannedSymbols.txt

```
M:System.String.Split(System.Char,System.Int32);Use Span instead
M:System.String.Split(System.Char,System.StringSplitOptions);Use Span instead
M:System.String.Split(System.Char[]);Use Span instead
M:System.String.Split(System.Char[],System.Int32);Use Span instead
M:System.String.Split(System.Char[],System.StringSplitOptions);Use Span instead
M:System.String.Split(System.Char[],System.Int32,System.StringSplitOptions);Use Span instead
M:System.String.Split(System.String,System.StringSplitOptions);Use Span instead
M:System.String.Split(System.String,System.Int32,System.StringSplitOptions);Use Span instead
M:System.String.Split(System.String[],System.StringSplitOptions);Use Span instead
M:System.String.Split(System.String[],System.Int32,System.StringSplitOptions);Use Span instead
M:System.String.Substring(System.Int32);Use Span instead
M:System.String.Substring(System.Int32,System.Int32);Use Span instead
```