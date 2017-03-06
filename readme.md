## SSH Auto
This project based on [Warp](https://github.com/jpalardy/warp), I added ability for users who needs password to login and tired on copied & pasted.

### Installation
Download Warp and Follow steps on [Warp](https://github.com/jpalardy/warp)

### Configuration file
This `~/.warp` file is a little bit different, you are able put ssh password.

```
# GOOGLE
-- production useast
ec2-user@app10.useast1.ec2.example.com
ec2-user@app12.useast1.ec2.example.com password-here
```

This requires expect installed.

- Linux : ` yum install expect` or `apt-get install expect`
- Mac: `brew install homebrew/dupes/expect`






