# ansible-ec2

## How to use
```
export AWS_ACCESS_KEY_ID="NUHKOIJFOJF9GFJDO" 
export AWS_SECRET_ACCESS_KEY="LSDJKFODSJF9SDJF8UH3U3HFKW"
```

Create a inventory file
```
[local]
localhost

[webserver]
```

ansible-playbook -i ./hosts ec2-basic.yml
