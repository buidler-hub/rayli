# 📸 rayli

![](https://i.imgur.com/miVLRoK.png)

<a href="https://www.producthunt.com/posts/rayli?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-rayli" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=345756&theme=dark" alt="Rayli - generate&#0032;image&#0032;of&#0032;a&#0032;code&#0032;block&#0032;right&#0032;from&#0032;the&#0032;terminal | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a> <a href="https://www.producthunt.com/posts/rayli?utm_source=badge-top-post-badge&utm_medium=badge&utm_souce=badge-rayli" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/top-post-badge.svg?post_id=345756&theme=dark&period=daily" alt="Rayli - generate&#0032;image&#0032;of&#0032;a&#0032;code&#0032;block&#0032;right&#0032;from&#0032;the&#0032;terminal | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

📸 A command-line tool to generate code images of your local code right away from the terminal

- [Usage](#usage)
- [Commands](#commands)

# Usage

```sh-session
$ npm install -g rayli
$ rayli COMMAND
running command...
$ rayli (--version)
rayli/0.0.1 win32-x64 node-v16.13.0
$ rayli --help [COMMAND]
USAGE
  $ rayli COMMAND
...
```

# Commands

- [`rayli config`](#rayli-config)
- [`rayli config:remove`](#rayli-configremove)
- [`rayli config:show`](#rayli-configshow)
- [`rayli generate`](#rayli-generate)
- [`rayli gist`](#rayli-gist)
- [`rayli github`](#rayli-github)
- [`rayli help [COMMAND]`](#rayli-help-command)

## `rayli config`

🔐 Configure the default values

```
USAGE
  $ rayli config

DESCRIPTION
  🔐 Configure the default values

EXAMPLES
  $ rayli config
```

## `rayli config:remove`

🚚 Remove the configured values

```
USAGE
  $ rayli config:remove

DESCRIPTION
  🚚 Remove the configured values

EXAMPLES
  $ rayli config:remove
```

## `rayli config:show`

👀 Check your configured values

```
USAGE
  $ rayli config:show

DESCRIPTION
  👀 Check your configured values

EXAMPLES
  $ rayli config:show
```

## `rayli generate`

📷 Generate a beautiful image of your code snippet

```
USAGE
  $ rayli generate [-c]

FLAGS
  -c, --[no-]config  🔐 Use the default configured values

DESCRIPTION
  📷 Generate a beautiful image of your code snippet

EXAMPLES
  $ rayli generate --config
```

## `rayli gist`

🌌 Generate a beautiful image of your gist

```
USAGE
  $ rayli gist -u <value> [-c]

FLAGS
  -c, --[no-]config  🔐 Use the default configured values
  -u, --url=<value>  (required) 🔗 Link of the gist
  -r, --range=<value> 🔍 Range of the gist

DESCRIPTION
  🌌 Generate a beautiful image of your gist

EXAMPLES
  $ rayli gist --url=https://gist.github.com/Kira272921/bfce776b3ad1145f764d89c296fec605
```

## `rayli github`

🐱 Generate a beautiful image of your code hosted on GitHub

```
USAGE
  $ rayli github -u <value> [-c]

FLAGS
  -c, --[no-]config  🔐 Use the default configured values
  -u, --url=<value>  (required) 🔗 Link of the code

DESCRIPTION
  🐱 Generate a beautiful image of your code hosted on GitHub

EXAMPLES
  $ rayli github --url=https://raw.githubusercontent.com/Kira272921/snipli/main/src/commands/download.ts
```

## `rayli help [COMMAND]`

Display help for rayli.

```
USAGE
  $ rayli help [COMMAND] [-n]

ARGUMENTS
  COMMAND  Command to show help for.

FLAGS
  -n, --nested-commands  Include all nested commands in the output.

DESCRIPTION
  Display help for rayli.
```

## 🖍 Examples

![](https://i.imgur.com/jOuOc9Y.png)

![](https://i.imgur.com/XniMSiF.png)

## 🦸‍♂️ Authors

### Avneesh Agarwal

- Website: https://www.avneesh.tech/
- Twitter: [@avneesh0612](https://twitter.com/avneesh0612)
- Github: [@avneesh0612](https://github.com/avneesh0612)
- LinkedIn: [@avneesh0612](https://www.linkedin.com/in/avneesh0612)

### Kira

- Website: https://kiradev.co
- Twitter: [@kira_272921](https://twitter.com/kira_272921)
- Discord: https://links.kiradev.co/discord
