# OidcTest
This is a very basic ASP.Net Core MVC application (.NET 6) with OIDC included to test simple login functionality. You just need to update your configuration with
- OpenIdConnect:Authority (./well-known/openid-configuration will be concatenated to this value to get metadata via OpenId Connect Discovery)
- OpenIdConnect:ClientId
- OpenIdConnect:ClientSecret
