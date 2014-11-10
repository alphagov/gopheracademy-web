# Putting the 'Go' into 'government'

## Background

We're a Ruby shop, wanted to try new things (R&D, learning)

## What made Go attractive in the first place

Performance, ease of writing core features

## What made Go easy to pick up

- Simple language
- Easy to follow conventions (gofmt, GOPATH mean we're writing the same code as
  each other)
- Easy to use what would be more complex in other languages (mocking HTTP,
  threading, message passing)

## What made Go easy to deploy

- Compiled language means no special operational requirements (eg learning about
  Unicorn for deploying Rails)
- Deployment was easy - compile the binary and just ship it
- Core platform features (JSON logging into Kibana, healtchecks for load
  balancers) trivial to implement in Go

## What made Go easy to keep working with

- Interest from others
- Strength of core library
- Implementing new systems easy - see TTLHashSet and our RabbitMQ-backed mirror

## Where we're going next

We're working on how to manage versioned dependencies - for some of our core
systems we need to guarantee the deployed versions of code. Look for more about
our experiences on the GDS Technology blog.
