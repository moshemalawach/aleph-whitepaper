# Introduction

The Internet was originally built to connect computers together. It has been used as a marvelous communication and data storage model. Protocols originally designed for decentralization (TCP, HTTP, SMTP... and even blockchains) are already showing their limitations.

In a purely economically driven world; simplicity, centralization, and non-standard data models tend to win out.

What is our internet today? Silos loosely connected together, users having data in each of those silos (Facebook, Google, and many others), with no simple way to port it over. [see @kyledrake]

There are a lot of attempts at breaking those silos, from connection from silo to silo (iftt, rgpd for data request, opendata programs...), to decentralized networks of silos (mastodon). We are living in a world of data silos.

In itself, that isn't bad if those silos were easily accessible and decentralized. Users don't know it, but they need to reclaim their data.

```{.mermaid caption="Typical centralized application"}
graph LR
  User --- Website
  Website --- Database
  Website --- CST("Centralized storage")

  class User,Website,Database,CST icon-node;
  class User man;
  class Website web;
  class CST server;
  class Database database;
```
