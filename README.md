# How to run blockmesh CLI 

## Download program file first. 
```
wget https://github.com/block-mesh/block-mesh-monorepo/releases/download/v0.0.363/blockmesh-cli-x86_64-unknown-linux-gnu.tar.gz
```

## Extract file
```
tar -xvf blockmesh-cli-x86_64-unknown-linux-gnu.tar.gz
```

## Enter blockmesh directory
```
cd target/x86_64-unknown-linux-gnu/release/
```

## Installing screen session manager
```
apt install screen
```

## Create new session called Blockmesh
```
screen -S blockmesh
```

## Run Blockmesh CLI
```
./blockmesh-cli --email "your email" --password "your password"
```

## The output will be...
```sh
2024-11-11T08:26:15.888980Z  INFO blockmesh_cli::login_mode: Login successful
2024-11-11T08:26:15.889020Z  INFO blockmesh_cli::login_mode: CLI starting
2024-11-11T08:26:15.918398Z  INFO blockmesh_cli::login_mode: Polling
.....
```
**Done!** Now press CTRL + A + D to detach screen session. **But how to enter the session again sir?**

## Enter the Blockmesh session again
```
session -r blockmesh
```

Thank you.

### Social Media
- [Telegram channel ](https://t.me/airdropStalkerChannel)
- [Follow me on X](https://x.com/nurairstalk)

