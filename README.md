# Healthz

Add Kubernetes style health checks to your Craft site.

![Healthz Logo](resources/img/plugin-logo.png)

## Requirements

This plugin requires Craft CMS 3.x / 4.x

## Installation

To install the plugin, follow these instructions.

1.  Open your terminal and go to your Craft project:

        cd /path/to/project

2.  Then tell Composer to load the plugin:

        composer require customd/healthz

3.  In the Control Panel, go to Settings → Plugins and click the “Install” button for Healthz.

## Health Check Overview

This plugin will provide an endpoint that allows health checks on Docker or Kubernetes workflows. Since Kubernetes is eating the world, it defaults to `healthz/liveness`, which is the default for Kubernetes.

## Using Health Check

Setup your Kubernetes and choose the default health check url (e.g. `healthz/liveness` or `healthz/readiness`).

Brought to you by [Jason McCallister](https://mccallister.io)
