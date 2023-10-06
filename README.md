**README.md**

## Xcode Text Macro without Username

**Description**

This Xcode macro inserts the following default header comments into all new files:

```
//  ___FILENAME___
//  ___PACKAGENAME___
//
//  Created on ___DATE___.
//  ___COPYRIGHT___
//
```

**Benefits**

* Enforces consistent header comments across your codebase.
* Saves you time from having to type out the header comments manually each time you create a new file.
* Makes your code more readable and maintainable.

**Installation**

1. Download the `IDETemplateMacros.plist` file from this repository.
2. Move the file to the following location:

```
~/Library/Developer/Xcode/UserData/
```

**Usage**

Once the macro is installed, it will be automatically applied to all new files that you create in Xcode.

**Example**

When you create a new file, Xcode will automatically insert the following header comments:

```
//  MyFile.swift
//  MyPackageName
//
//  Created on 2023-10-06 16:40:51 PST.
//  Copyright © 2023 My Name Or Company. All rights reserved.
//
```

**Command to copy file at location:**

```
cp IDETemplateMacros.plist ~/Library/Developer/Xcode/UserData/
```

**Enjoy!**
