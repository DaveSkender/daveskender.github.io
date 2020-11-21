# projects

## [stock.indicators](http://daveskender.github.io/Stock.Indicators)

[![NuGet package](https://img.shields.io/nuget/v/skender.stock.indicators?color=blue&logo=NuGet&label=NuGet%20Package)](https://www.nuget.org/packages/Skender.Stock.Indicators)
[![Nuget](https://img.shields.io/nuget/dt/skender.stock.indicators?logo=NuGet&label=Downloads)](https://www.nuget.org/packages/Skender.Stock.Indicators)
[![build status](https://img.shields.io/azure-devops/build/skender/5123ca47-74f2-4d67-a5d4-c4d90b8d670a/21/master?logo=AzureDevops&label=Build%20Status)](https://dev.azure.com/skender/Stock.Indicators/_build/latest?definitionId=21&branchName=master)
[![code coverage](https://img.shields.io/azure-devops/coverage/skender/stock.indicators/21?logo=AzureDevops&label=Code%20Coverage)](https://dev.azure.com/skender/Stock.Indicators/_build/latest?definitionId=21&branchName=master&view=codecoverage-tab)

A .NET library that produces [stock indicators](http://daveskender.github.io/Stock.Indicators/docs/INDICATORS.html).  Send in historical stock price quotes and get back desired technical indicators (such as moving average, relative strength, stochastic oscillator, parabolic SAR, etc).  Nothing more.

It can be used in any kind of stock analysis software.  We had private trading algorithms and charts in mind when originally creating this open library -- to support stock, cryptocurrency, forex, and machine learning systems.  [Skender.Stock.Indicators](https://www.nuget.org/packages/Skender.Stock.Indicators) is the public NuGet package for this library.

## [stock.charts](https://github.com/DaveSkender/Stock.Charts)

A site to demonstrate usage of the [Skender.Stock.Indicators](https://www.nuget.org/packages/Skender.Stock.Indicators) Nuget package.  It is an Angular website with a .NET Web Api that auto generates a stock chart.  You can dynamically add and remove indicators on the chart.  Only a few sample [indicators](http://daveskender.github.io/Stock.Indicators/docs/INDICATORS.html) are shown in this demo.

The site is hosted on a free-tier cloud web service, so be patient while it initially wakes up from hibernation.  The package itself is [quite fast](http://daveskender.github.io/Stock.Indicators/tests/performance).

## contact info

You can also direct message [@daveskender](https://twitter.com/messages/compose?recipient_id=27475431) on Twitter.
