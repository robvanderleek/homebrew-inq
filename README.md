# homebrew-inq

# Development

## Create formula

Based on a PyPi release:

```shell
brew create --python https://files.pythonhosted.org/packages/...tar.gz
```

## Update formula

1. Get release URL and SHA256 from PyPi

2. Run and copy output in formula:

    ```shell
    brew update-python-resources --print-only --version 0.3.0 inq
    ```
