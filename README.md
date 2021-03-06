# cdc-service
We plan to extract some core ADC endpoints from core API.
Here are some key goals:

1. Expose core ADC endpoints (*OUS, Events, Fields and Users*) with testability in mind
2. High performance (fast!!!) 
3. Deployable in AWS 
4. Authenticate using token/ssl certificate
5. Use gRPC ASP.NET Core API

*cdc-sevice is not a replacement for core api. Its a tiny subset that will run side by side which would enable us fallback to core api if needed*

![overview](cdc-service.png)
