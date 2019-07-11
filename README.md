# Overview [![NuGet](https://img.shields.io/nuget/v/SolaceTestClient.svg)](https://www.nuget.org/packages/SolaceTestClient) [![Build Status](https://travis-ci.com/stop-cran/SolaceTest.svg?branch=master)](https://travis-ci.com/stop-cran/SolaceTest)

The package provides a tool to test connection to [Solace Pub-Sub](https://solace.com/).

# Installation

NuGet package is available [here](https://www.nuget.org/packages/SolaceTestClient).

```
dotnet tool install --global SolaceTestClient --version 1.0.0
```

# Example

```
SolaceTestClient -h <a host> --vpn <Message VPN> -u <username> -p <password>
```

# Remarks

This tool uses [.Net Solace messaging API](https://docs.solace.com/Solace-PubSub-Messaging-APIs/dotNet-API/net-api-home.htm). It supports TCP, TCPS, HTTP and HTTPS protocols (see [docs](https://docs.solace.com/API-Developer-Online-Ref-Documentation/net/html/3d8e6034-0f60-467b-340b-aa63a4555f3a.htm)).