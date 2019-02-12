# The git config I'm used to

This is the git config I'm used to have on all my machines, VMs and shells.

Kudos to a lot of different SO users whose snippets I shamelessly copied and adapted to my needs ;-)

Comments are welcome if you see something that needs improvement or have neat aliases & Co to share!

How to use:

- clone the repository
- include the `.gitconfig` file in the repo into your global git config (e.g. `~/.gitconfig`) at the very beginning
- override values that need overriding after the include, e.g.

```
[include]
        path = gitconfig/.gitconfig
[user]
        name = John Doe
        email = john.doe@example.com
```
