# AWS WorkSpaces Client in POSIX Shell

Currently, [the official AWS WorkSpaces Client for Linux](https://clients.amazonworkspaces.com/linux-install) ***sucks***.

Using this script instead is a much more comfortable experience.

## Requirements

- Chromium or Google Chrome

This script opens the AWS WorkSpaces Client on the web with Chromium/Chrome in minimal configuration.

## Run

```shell
$ ./aws-workspaces-client
```

or

```shell
$ AWS_REGION=your-aws-region CHROME=/path/to/google-chrome ./aws-workspaces-client
```
