# GroupBox

[![CI](https://github.com/wieslawsoltes/GroupBox.Avalonia/actions/workflows/build.yml/badge.svg)](https://github.com/wieslawsoltes/GroupBox.Avalonia/actions/workflows/build.yml)

[![NuGet](https://img.shields.io/nuget/v/GroupBox.Avalonia.svg)](https://www.nuget.org/packages/GroupBox.Avalonia)
[![NuGet](https://img.shields.io/nuget/dt/GroupBox.Avalonia.svg)](https://www.nuget.org/packages/GroupBox.Avalonia)

[![GitHub release](https://img.shields.io/github/release/wieslawsoltes/GroupBox.Avalonia.svg)](https://github.com/wieslawsoltes/GroupBox.Avalonia)
[![Github All Releases](https://img.shields.io/github/downloads/wieslawsoltes/GroupBox.Avalonia/total.svg)](https://github.com/wieslawsoltes/GroupBox.Avalonia)
[![Github Releases](https://img.shields.io/github/downloads/wieslawsoltes/GroupBox.Avalonia/latest/total.svg)](https://github.com/wieslawsoltes/GroupBox.Avalonia)

A GroupBox control for Avalonia.

![image](https://github.com/user-attachments/assets/41e89f7d-3046-4cd4-b72f-c8604411c510)

## Usage

Add `<StyleInclude Source="avares://GroupBox.Avalonia/GroupBox.axaml" />` to your application styles.

```xaml
<Application.Styles>
  <FluentTheme />
  <StyleInclude Source="avares://GroupBox.Avalonia/GroupBox.axaml" />
</Application.Styles>
```

```xaml
<GroupBox Header="GroupBox">
  <StackPanel>
    <RadioButton Content="RadioButton1" />
    <RadioButton Content="RadioButton2" />
  </StackPanel>
</GroupBox>
```

## License

GroupBox.Avalonia is licensed under the [MIT license](LICENSE.TXT).
