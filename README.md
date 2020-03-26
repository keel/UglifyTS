复制于 https://github.com/domchen/UglifyTS

## 使用
在具备tsconfig.json的项目目录中执行
```
node /path/to/src/Program.js
```
即可以在当前目录中生成generated目录，其中有混淆之后的ts代码


# ------以下为原项目说明
## Introduction

UglifyTS is a source code obfuscation tool for TypeScript. It accepts TypeScript source files, and generates the functionally equivalent source files which are much harder to understand or reverse-engineer. This tool is usually used for source code protection.


## Installation

First make sure you have installed the latest version of [node.js](http://nodejs.org/)
(You may need to restart your computer after this step).

For use as a command line app:

```
npm install -g uglifyts
```

For programmatic use:

```
npm install uglifyts
```

## Usage

```
uglifyts [outDir] [options]
```