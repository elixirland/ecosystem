# The Elixir Ecosystem

The Elixir ecosystem is a collection of libraries, tools, and services that extend the capabilities of Elixir. Here is an overview of some of the most popular and widely-used projects in the Elixir ecosystem.

## The Web

### Phoenix Framework

Phoenix is a popular web development framework for building web applications with Elixir. Server-side rendering and real-time communication, are some of its key features. Has LiveView built-in, allowing developers to build interactive, real-time applications while writing little to no JavaScript.

[Documentation](https://hexdocs.pm/phoenix/overview.html)

### Phoenix LiveView

LiveView is a library that enables rich, real-time user experiences with server-rendered HTML. It allows developers to build interactive, real-time applications while writing little to no JavaScript.

[Documentation](https://hexdocs.pm/phoenix_live_view/welcome.html)

### SurfaceUI

A server-side rendering component library that allows developers to build rich interactive user-interfaces, writing minimal custom Javascript.

[Documentation](https://hexdocs.pm/surface/Surface.html)

### LiveState

The goal of LiveState is to make highly interactive web applications easier to build. Currently, in most such applications, clients send requests and receive responses from and to a server API. This essentially results in two applications, with state being managed in both in an ad hoc way.

LiveState uses a different approach. Clients dispatch events, which are sent to the server to be handled, and receive updates from the server any time application state changes. This allows state to have a single source of truth, and greatly reduces client code complexity. It also works equally well for applications where updates to state can occur independently from a user initiated, client side event (think "real time" applications such as chat, etc).

[Documentation](https://hexdocs.pm/live_state/readme.html)

### Plug

A specification and composable modules for web application components, enabling HTTP request handling.

[Documentation](https://hexdocs.pm/plug/readme.html)

### Absinthe

A GraphQL toolkit for Elixir, an implementation of the GraphQL specification built to suit the language's capabilities and idiomatic style

[Documentation](https://hexdocs.pm/absinthe/overview.html)

## Native Applications

### Scenic

Scenic is an application framework written directly on the Elixir/Erlang/OTP stack. With it, you can build client-side applications that operate identically across all supported operating systems, including MacOS, Ubuntu, Nerves/Linux, and more.

[Documentation](https://hexdocs.pm/scenic/welcome.html)

### LiveView Native

LiveView Native allows you to build LiveView apps that have a front-end for multiple platforms. Use your LiveView back-end to create a web, mobile, wearable and/or desktop UI.

[Documentation](https://hexdocs.pm/live_view_native/readme.html)

## Machine Learning

### Nx

A multi-dimensional tensors library with multi-staged compilation to the CPU/GPU.

[Documentation](https://hexdocs.pm/nx/intro-to-nx.html)

### Axon

Nx-powered Neural Networks for Elixir.

[Documentation](https://hexdocs.pm/axon/Axon.html)

### Bumblebee

Pre-trained Neural Network models in Axon and integration with Hugging Face models

[Documentation](https://hexdocs.pm/bumblebee/Bumblebee.html)

### Explorer

Explorer brings series (one-dimensional) and dataframes (two-dimensional) for fast data exploration to Elixir.

[Documentation](https://hexdocs.pm/explorer/exploring_explorer.html)

### Scholar

Traditional machine learning tools built on top of Nx. Scholar implements several algorithms for classification, regression, clustering, dimensionality reduction, metrics, and preprocessing.

[Documentation](https://hexdocs.pm/scholar/readme.html)

## Embedded Software

### Nerves

A framework for building embedded software using Elixir, providing tools and libraries for hardware interfacing.

[Documentation](https://hexdocs.pm/nerves/getting-started.html)

## Database Tools

### Ecto

Ecto is a database wrapper and query generator for Elixir, providing a unified API for working with different databases.

[Documentation](https://hexdocs.pm/ecto/Ecto.html)

## Testing

### ExUnit

The built-in testing framework for Elixir, providing a simple and powerful API for writing and running tests.

[Documentation](https://hexdocs.pm/ex_unit/ExUnit.html)

### Wallaby

A browser automation tool for Elixir, allowing developers to simulate realistic user interactions.

[Documentation](https://hexdocs.pm/wallaby/readme.html)

## Internationalization and Localization

### GetText

GetText is an internationalization and localization library for Elixir, allowing easy translation and formatting of messages.

[Documentation](https://hexdocs.pm/gettext/Gettext.html)

### Elixir CLDR

A library for working with Unicode Common Locale Data Repository (CLDR) in Elixir applications.

[Documentation](https://hexdocs.pm/ex_cldr/readme.html)

## Code Analysis Tools

### Dialyzer

A static analysis tool for Erlang and other languages that compile to BEAM bytecode for the Erlang VM.

[Documentation](https://hexdocs.pm/dialyxir/Mix.Tasks.Dialyzer.html)

### Credo
A static code analysis tool for the Elixir language with a focus on teaching and code consistency.

[Documentation](https://hexdocs.pm/credo/overview.html)

## Other Tools

### Ash Framework

A declarative, resource-oriented application development framework for Elixir.

[Documentation](https://hexdocs.pm/ash/readme.html)

### Oban

A robust job processing library for Elixir, providing background job processing with reliability and concurrency.

[Documentation](https://hexdocs.pm/oban/Oban.html)

### Exq

An Elixir library for job processing, utilizing Redis for managing job queues and worker processes.

[Documentation](https://hexdocs.pm/exq/readme.html)

### ExDoc

A tool for generating HTML documentation for Elixir projects, transforming documentation into readable web pages.

[Documentation](https://hexdocs.pm/ex_doc/0.22.0/readme.html)

### LiveBook

A collaborative and interactive code notebook for Elixir, providing a rich environment for exploring and sharing code.

[Documentation](https://hexdocs.pm/livebook/readme.html)

### Telemetry

A lightweight library for dynamic dispatching of events, with a focus on metrics and instrumentation.

[Documentation](https://hexdocs.pm/telemetry/readme.html)
