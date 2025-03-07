---
id: quickstart
title: Sumo Logic Traces Quickstart
sidebar_label: Traces Quickstart
description: See how your application is behaving with trace analytics.
---

import useBaseUrl from '@docusaurus/useBaseUrl';

You can observe apps and microservices at the level of individual requests to pinpoint issues with particular microservices. Powered by OpenTelemetry, our tracing capabilities provide an open and flexible standard for the observability of microservice transactions without vendor lock-in.

## What You'll Need

| Account Type | Account Level |
|--|--|
| Credits | Enterprise Operations and Enterprise Suite. Essentials get up to 5 GB a day. |

If your Sumo Logic service package has been upgraded to include Traces, you will see a **Traces** tab available in Sumo Logic.

<img src={useBaseUrl('/img/traces/traces-menu-option.png')} alt="traces menu option" width="250"/>

## Microlesson

The [Tracing micro lesson](https://www.youtube.com/watch?v=BTqufvTJ4vE&list=PLuHsjJUxgM1fRFUzFZuQcZ2GCW-jtiOxa&index=33&t=37s) helps you get started with Tracing.

<Iframe url="https://www.youtube.com/embed/BTqufvTJ4vE"
        width="854px"
        height="480px"
        id="myId"
        className="video-container"
        display="initial"
        position="relative"
        allow="accelerometer; autoplay=1; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
        />

import Iframe from 'react-iframe';

Trace data is visualized through filtered trace lists and icicle charts allowing you to find and troubleshoot faulty transactions easily. See how easy it is to [view and investigate traces](working-with-tracing-data/view-and-investigate-traces.md).

Traces are collected with [SumoLogic Kubernetes Collection](https://github.com/open-telemetry/opentelemetry-collector) through an [HTTP Traces Source](get-started-transaction-tracing/http-traces-source.md). HTTP Trace Sources are set up automatically with Sumo Logic Kubernetes Collection version 1.1.0+. 

## Next Steps

See [Getting Started with Transaction Tracing](/docs/apm/traces/get-started-transaction-tracing) for details on how to set up your collection environment.
