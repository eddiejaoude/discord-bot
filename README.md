# EddieBot

The official **EddieBot** for the EddieHub [Discord server](http://discord.eddiehub.org). Join us at [Discord](http://discord.eddiehub.org) today!
<a href="https://gitpod.io/#https://github.com/EddieHubCommunity/EddieBot" target="_blank">
  <img src="https://gitpod.io/button/open-in-gitpod.svg" alt="Open RBJKS in Gitpod">
</a>

## Features

- Checking peoples' messages for inclusive language.

![Eddie bit warning](https://user-images.githubusercontent.com/624760/200577618-af25764f-a9ce-4ce8-a1f2-f8808c682c77.png)

## Config / Secrets environment variables

Copy `.env.example` to `.env` and add your private information

*Note: never commit this file, it is ignored by Git*

```
# .env file

# required: discord API token
DISCORD_TOKEN=

# required: mongo URL connection string
EDDIEBOT_MONGO_CONNECTION_STRING=

# optional
DEBUG_HOOK=

# required: discord server id
HOME_GUILD="699608417039286293"

# optional
NODE_ENV="development"

# required: channel id for logs
ADMIN_CHANNEL=
```

## Installation

**1.** Start by making a fork of the repository. Click on the "Fork" symbol at the top right corner.

**2.** Clone your new fork of the repository:

### SSH  [Github Docs](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

```bash
$ git clone git@github.com:EddieHubCommunity/EddieBot.git
```

*note: recommended*

### GitHub CLI

```bash
$ gh repo clone EddieHubCommunity/EddieBot
```

### HTTPS

```bash
$ git clone https://github.com/EddieHubCommunity/EddieBot.git
```

**3.** Set upstream command:
```bash
git remote add upstream https://github.com/EddieHubCommunity/EddieBot.git
```

**4.** Navigate to the new project directory:

```bash
cd EddieBot
```

**5.** Create a new branch:
```bash
git checkout -b <branch-name>
```

**6.** Sync your fork or a local repository with the origin repository:
- In your forked repository click on "Fetch upstream"
- Click "Fetch and merge".

### Alternatively, Git CLI way to Sync forked repository with origin repository:
```bash
git fetch upstream
```
```bash
git merge upstream/main
```

**7.** Make your changes to the source code.

**8.** Stage your changes and commit:

```bash
git add <filename>
```

```bash
git commit -m "<your-commit-message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin <branch-name>
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**11.** **Congratulations!** You've made your first contribution to [**EddieBot**](https://github.com/EddieHubCommunity/EddieBot/graphs/contributors)! 🙌🏼


### Discord Docs

- https://discord.com/developers/docs/intro#bots-and-apps

## Running the app

```bash
$ npm ci

# development
$ npm run build
$ npm start
```

## Running the tests

```bash
$ npm test
```

## Support

EddieBot is an MIT-licensed open source project. It can grow thanks to the contributors and the community members. If you'd like to join them, feel free to make a pull request and we'll review it.

Stuck? Have any questions or comments? Join us on [Discord](http://discord.eddiehub.org/) and ask for help.

## License

The EddieBot is licensed under the [MIT](https://github.com/EddieHubCommunity/EddieBot/blob/main/LICENSE) license.

## Thanks to all Contributors 💪 

Thanks a lot for spending your time helping EddieBot grow. Thanks a lot! Keep rocking 🍻

[![Contributors](https://contrib.rocks/image?repo=EddieHubCommunity/EddieBot)](https://github.com/EddieHubCommunity/EddieBot/graphs/contributors)

## Our Pledge

We take participation in our community as a harassment-free experience for everyone and we pledge to act in ways to contribute to an open, welcoming, diverse and inclusive community.  

If you have experienced or been made aware of unacceptable behaviour, please remember that you can report this.  Read our [Code of Conduct](https://github.com/EddieHubCommunity/EddieBot/blob/main/CODE_OF_CONDUCT.md).
