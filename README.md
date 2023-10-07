# GH user

Show information about the user currently logged (or token being used) in with [GitHub CLI](https://cli.github.com).

This means either the user logged it or token being used (eg: GH_TOKEN).

> [!NOTE]
> The CLI `auth status` does the same thing as this extension with the exception of identifying the token type. 

## Why?


## Installation

### Prerequisites

- `Bash`

### gh cli extension

You can install `gh-user` as a [gh cli](https://github.com/cli/cli) extension!

```console
gh extensions install tspascoal/gh-user
```

#### Verify installation

```console	
gh user
```

## Usage

just call the extension with `gh user`

This will return:

-User:
  - Login
  - Name
  - Email
- Scopes The scopes of the token
- Token type (PAT, OAuth,etc,etc)

## License

This code is licensed under [MIT license](LICENSE).
