# ,table

,table is a shell script used to generate template for Markdown tables.

## Installation

Copy `,table` to anywhere where you store your scripts and give it execute permission.

```shell
chmod +x ,table
```

## Usage

```shell
,table [columns]
```

For example

```shell
,table 3
```

prints out a 3-column table with `_` values as placeholders for headers and the first row

```shell
|_|_|_|
|-|-|-|
|_|_|_|
```

## Notes

The naming convention comes from Redowan Delowar's [Pesky Little Scripts](https://rednafi.com/misc/pesky_little_scripts/) that quotes Brandon Rhodes' talk [Activation energy](https://www.youtube.com/watch?v=pybtvFFRYFs):

> All your scripts should start with a character as a prefix that doesn’t have any special meaning in the shell environment. Another requirement is that no other system command should start with your chosen character.
