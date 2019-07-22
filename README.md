# EchoIP
https://echo-ip.starworks.cc

# How does it works?
```csharp
string clientIp = context.Connection.RemoteIpAddress.ToString();
await context.Response.WriteAsync(clientIp);
```
