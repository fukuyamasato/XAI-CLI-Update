# XAI-CLI-Update
# Delete old files
```
rm sentry-node-cli-linux.zip sentry-node-cli-linux
```
# Download Latest Release
```
sudo apt update
curl -L -o sentry-node-cli-linux.zip https://github.com/xai-foundation/sentry/releases/latest/download/sentry-node-cli-linux.zip
```
#Unzip New Release
```
unzip sentry-node-cli-linux.zip
```
#Delete Old Screen and Create New One (You can see your old screen with "screen -ls" command)
```
screen -X -S <youroldscreen> quit
```
```
screen -S xai
```
```
./sentry-node-cli-linux
```
# Add Operator
```
add-operator
```
- **1-Type in the public address of the wallet you want to designate as the operator**
- **2-Type in the private key of the wallet that purchased the Sentry Key**

# Boot Operator
```
boot-operator
```
- **Type in the private key of the wallet you would like to designate as the Operator. Then hit 'Enter'**
- **CTRL+A+D to detach from screen**
# Check your node
```
screen -r xai
```
