# Tasks

## Linux

### Task 1

- Create two users **tux** and **octocat**.
- Create a group **friends**. Add both the users to the group.
- Create a directory `/friends`.
- Owner of the file should be **tux** and group of the directory should be **friends**
- Allow the group **friends** read permission to `/friends`.
- Allow the user **tux** write permission to `/friends`.
- Allow execute permission for all - user, group and others, on `/friends` directory.

### Task 2

- [Here is a Go application](https://gobyexample.com/http-server).
- Compile the application and store the resulting binary file at `/usr/local/bin/http-server`. (Check out the [Resources page](resources.md#go) for help with building a Go application)

_Note: The following two steps would block the shell from processing further inputs. You can exit the application by pressing `Ctrl+C`._
- Ensure the application binary is executable. Execute it using the full absolute path and verify it from a browser.
- Ensure the application is available to execute from any path using just the binary name(as opposed to the absolute path in the first step) - `http-server`. Execute it and verify from a browser.
- Ensure the application is running at all times. Verify by restarting your computer and checking if you can access the application from the browser without running any commands manually.

## Bash

### Task 1

Write a shell script to perform the Task 1 of the Linux section.

### Task 2

Write a shell script, which takes in as the only argument a string, treating it as a GitHub username. Fetch details of the user via the GitHub public API and print the output in the following format

_`name` is from `location` and has the Twitter username: `twitter_username`_

Example
```sh
$ bash github_user_details.sh mbtamuli
Mriyam Tamuli is from India and has the Twitter username: mbtamuli
```
