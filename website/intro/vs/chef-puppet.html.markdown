---
layout: "intro"
page_title: "Terraform vs. Chef, Puppet, etc."
sidebar_current: "vs-other-chef"
description: |-
  Configuration management tools install and manage software on a machine that already exists. Terraform is not a configuration management tool, and it allows existing tooling to focus on their strengths: bootstrapping and initializing resources.
---

# Terraform vs. Chef, Puppet, etc.

Configuration management tools install and manage software on a machine
that already exists. Terraform is not a configuration management tool,
and it allows existing tooling to focus on their strengths: bootstrapping
and initializing resources.

Terraform focuses on the higher-level abstraction of the datacenter and
associated services, while allowing you to use configuration management
tools on individual systems. It also aims to bring the same benefits of
codification of your system configuration to infrastructure management.

If you are using traditional configuration management within your compute
instances, you can use Terraform to configure bootstrapping software like
cloud-init to activate your configuration management software on first
system boot.

