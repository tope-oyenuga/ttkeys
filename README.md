# ttkeys
ttkeys helps with injecting secret keys securely into apps 

Possible values for AWS regions used in the ttkeysconfig file are the following:

- ap-east-1      // Asia Pacific (Hong Kong).
- ap-northeast-1 // Asia Pacific (Tokyo).
- ap-northeast-2 // Asia Pacific (Seoul).
- ap-south-1     // Asia Pacific (Mumbai).
- ap-southeast-1 // Asia Pacific (Singapore).
- ap-southeast-2 // Asia Pacific (Sydney).
- ca-central-1   // Canada (Central).
- eu-central-1   // EU (Frankfurt).
- eu-north-1     // EU (Stockholm).
- eu-west-1      // EU (Ireland).
- eu-west-2      // EU (London).
- eu-west-3      // EU (Paris).
- sa-east-1      // South America (Sao Paulo).
- us-east-1   s   // US East (N. Virginia).
- us-east-2      // US East (Ohio).
- us-west-1      // US West (N. California).
- us-west-2      // US West (Oregon).



Sample contents of ttkeysconfig.yaml file:

```
region: us-east-1
secretName: tt-test-secret
```

## install node
```
cd /usr/local
sudo tar xvf ~/node-v10.16.0-linux-x64.tar.xz --strip=1
```

## add golang to environment path
```
export PATH=$PATH:/usr/local/go/bin
```

### tar up the ttkeys executable
```
tar -zcvf ttkeys.tar.gz ttkeys
```
