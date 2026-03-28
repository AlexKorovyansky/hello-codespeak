## CodeSpeak Quick Start: Build a Project From Scratch

I've created this repo as a result of passing https://codespeak.dev/blog/greenfield-project-tutorial.

The entire project is generated from [spec.cs.md](spec.cs.md) file. It means that other files are not required to store in git, I've added them just for a demonstration purpose. 

I've discovered a couple issues (where actual behavior was different from the one stated as expected in the tutorial). That's okay, because CodeSpeak in currently in early alpha. All issues have been reported to CodeSpeak team via discord.

Also, I've measured a cost of writing simple django web app with CodeSpeak 0.3.5 and Antropic Sonnet 4.6. It's $1.04.

Demo of the project and its spec:
https://alex-korovyansky.neetorecord.com/watch/b753071d5ad737923c3c

## Run the project

Install uv:
```bash
$ curl -LsSf https://astral.sh/uv/install.sh | sh
```

Install CodeSpeak:
```bash
$ uv tool install codespeak-cli
```

Log in:
```bash
$ codespeak login
```

Generated code from the spec:
```bash
$ codespeak build --spec spec.cs.md
```

Open http://127.0.0.1:8000 in browser
