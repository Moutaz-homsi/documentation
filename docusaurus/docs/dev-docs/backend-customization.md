---
title: Back-end customization
description: All elements of Strapi's back end, like routes, policies, middlewares, controllers, services, models, requests, responses, and webhooks, can be customized.
canonicalUrl: https://docs.strapi.io/developer-docs/latest/development/backend-customization.html
---

# Back-end customization

Strapi runs an HTTP server based on [Koa](https://koajs.com/), a back end JavaScript framework.

:::strapi What is Koa?
If you are not familiar with the Koa back end framework, we highly recommend you to read the [Koa's documentation introduction](http://koajs.com/#introduction).
:::

Each part of Strapi's back end can be customized:

- the [requests](/dev-docs/development/backend-customization/requests-responses#requests) received by the Strapi server,

- the [routes](/dev-docs/development/backend-customization/routes) that handle the requests and trigger the execution of their controller handlers,

- the [policies](/dev-docs/development/backend-customization/policies) that can block access to a route,

- the [middlewares](/dev-docs/development/backend-customization/middlewares) that can control the request flow and the request before moving forward,

- the [controllers](/dev-docs/development/backend-customization/controllers) that execute code once a route has been reached,

- the [services](/dev-docs/development/backend-customization/services) that are used to build custom logic reusable by controllers,

- the [models](/dev-docs/development/backend-customization/models) that are a representation of the content data structure,

- the [responses](/dev-docs/development/backend-customization/requests-responses#responses) sent to the application that sent the request,

- and the [webhooks](/dev-docs/development/backend-customization/webhooks) that are used to notify other applications of events that occurred.