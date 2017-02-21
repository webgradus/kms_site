---
layout: page
title: About
permalink: /about
---
KMS is a modern and flexible Ruby on Rails content management system with modular approach. It utilizes the most latest features from Rails and PostgreSQL (such as json column type, for example). Mostly inspired by LocomotiveCMS, but in contrast with it KMS relies on robust PostgreSQL database and doesn't provide all-in-one solution. The basic idea behind KMS: minimal core, extendable via extensions (engines). So you can take only what you need.

The most powerful feature behind KMS is templating engine called Liquor. If you're familiar with Shopify's Liquid templating engine, then you already know [Liquor](https://github.com/evilmartians/liquor). In Liquor it's a little bit easier to extend its core as well as it has really simple Rails integration.

KMS can be easily extended so you can write your own specific code and expose it to KMS. Extensions relies on Ruby on Rails Engines approach so they are just micro RoR apps utilizing KMS core services. And what is really perfect there are a lot of useful extensions already written. The most useful is [KMS Models](https://github.com/webgradus/kms_models) - this one allows you to define "models" on-the-fly (reserving a name for collection in Liquor, adding fields, creating model elements, iterating in your HTML).
