# Debounce vs Throttle vs Rate Limit

An interactive real-time visualization comparing three common strategies for handling high-frequency event streams: **debounce**, **throttle**, and **rate limit**.

## [Live Demo](https://rotorsoft.github.io/rate-limit-animation/)

## What it shows

A continuous stream of random events flows across four lanes:

- **Raw Events** — the unfiltered input stream
- **Debounce** — fires only after a configurable quiet period with no new events
- **Throttle** — allows at most one event per configurable time interval
- **Rate Limit** — allows N events per sliding time window

Each lane renders dots for handled and ignored events, animated connectors showing timing relationships, and shaded zones representing active windows. Sliders let you tune each strategy's parameters in real time.

## Running locally

Open `index.html` in any modern browser. No build step or dependencies required.
