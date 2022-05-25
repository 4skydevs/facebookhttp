# Webhook Sample Applications for Graph API Developers

**Summary**: When you build an App on Facebook Platforms, the platform may notify your App of an event using Webhooks, a type of HTTPS API. This repository contains sample code of applications that implement Webhook servers.

## Introduction to Graph API and Webhooks

When you [develop an Application](https://developers.facebook.com/docs/development/) (or App) using platforms built on Facebook's [Graph API](https://developers.facebook.com/docs/graph-api/), such as [Facebook Messenger Platform](https://developers.facebook.com/docs/messenger-platform/) or [WhatsApp Business Platform's Cloud API](https://developers.facebook.com/docs/whatsapp/cloud-api/), your applications often need to receive events from those platforms.

While the Graph API is an HTTPS interface by which your App can make API calls to Facebook, [Webhooks](https://developers.facebook.com/docs/graph-api/webhooks/) are a technology that allows platforms to send events as HTTPS requests back to your App.

For example, in Facebook Messenger Platform or WhatsApp Cloud API, Webhooks are essential for receiving replies to messages that you've sent, or learning that messages have been read, couldn't be delivered, etc. While not all platforms use Webhooks for event notification, many do.

# Sample Applications

These are sample applications that you can use to get started developing Apps that use Webhooks with various Facebook Platforms.

Currently, they include Facebook's [Webhooks](https://developers.facebook.com/docs/graph-api/webhooks/) product and Instagram's [Subscriptions API](https://www.instagram.com/developer/subscriptions/).

1. [Heroku](heroku) - A sample client that receives Webhook events.
1. [Hubot](hubot) - A script that messages a chat room when a Facebook Page post is published using Webhooks.

## License

See the [license file][LICENSE].

## Copyright

(c) Meta Platforms, Inc. and affiliates.