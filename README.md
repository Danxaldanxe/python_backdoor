Backdoor by **Hades.y2k**
=========================
[official.ghost@tuta.io](mailto:official.ghost@tuta.io)

Backdoor written in Python that will give reverse shell to attacker. The server will be listening on victim machine for incoming connection.

And if you target Windows machine, use _winreg module to edit Registry therefore you can add auto run key with fake procress name. For *nix machines, there is a directory called /etc/init.d which is similar to Windows Registry

###### New feature: Add password authentication. Server will accept the connection only if the password provided by attacker console is valid.

##### Features: Upload scripts for further attacks such as gaining Admin access or use as bot for DDOS. OR steal datas. use 'exit' to disconnect and you can reconnect easily. For commands in detials, type 'help' in console.

```
you might need to do port forwarding on your router
```

##### Usage for console: python console.py ip port password.

##### Bind server.py with legitimate program and send it to victim.

### Screenshots

![alt tag](http://i.imgur.com/IctitpY.png)

![alt tag](http://i.imgur.com/nkt38x0.png)
