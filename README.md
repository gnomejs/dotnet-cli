# @gnome/dotnet-cli

<div height=30" vertical-align="top">
<image src="https://raw.githubusercontent.com/gnomejs/gnomejs/main/assets/icon.png"
    alt="logo" width="60" valign="middle" />
<span>Work less. Do more. </span>
</div>

## Overview

The `dotnet-cli` module provides a simple way to execute
dotnet commands.

The module relies upon the @gnome/exec module and
has the same basic usage as the `Command` and `ShellCommand` class.

## Basic Usage

```typescript
import { dotnet } from "@gnome/dotnet-cli";
 
const result = dotnet("--version");
console.log(result.code);
console.log(result.text());

```

[MIT License](./LICENSE.md)
