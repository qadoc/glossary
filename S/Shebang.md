
# Shebang

在计算领域中，Shebang（也称为 Hashbang）是一个由井号和叹号构成的字符序列 `#!`，其出现在文本文件的第一行的前两个字符。 在文件中存在 Shebang 的情况下，类 Unix 操作系统的程序加载器会分析 Shebang 后的内容，将这些内容作为解释器指令，并调用该指令，并将载有 Shebang 的文件路径作为该解释器的参数。

例如，以指令 `#!/bin/sh` 开头的文件在执行时会实际调用 `/bin/sh` 程序（通常是 `Bourne shell` 或兼容的 shell，例如 bash、dash 等）来执行。这行内容也是 shell 脚本的标准起始行。

**参考资料**

1. [Shebang](https://zh.wikipedia.org/wiki/Shebang)

