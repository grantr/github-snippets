1. Download a GitHub [Personal Access Token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) to a file locally, `$HOME/github.oauth` is the file that will be used in these instructions.
1. Determine the GitHub user to run on, e.g. ['Harwayne'](https://github.com/Harwayne).
1. Determine the date to run on. By default it will pick the second most recent Monday (essentially the most recently completed Monday-Monday week). Use the `%m-%d-%y` format, e.g. '01-31-2018'.
1. Run the tool.
    ```shell
    go run main.go --token_file=$HOME/github.oauth --user=Harwayne --start=01-31-2018
    ```
