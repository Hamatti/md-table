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
