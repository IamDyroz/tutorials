# Git Configuration

Before we start using Git, we need to specify some configurations, such as:
- Name
- Email
- Default Editor
- Line Ending

 Which can be configure in 3 different level:

 - `System` for all users
 - `Global` for all repositories of the current user
 - `Local` for current repositories

#

```
$ git config --global user.name "Dhiraj Bhattarai"

$ git config --global user.email b4dhiraj@gmail.com
```

*Note:* In first command, the double quote `" "` is used to include the space in between the name.