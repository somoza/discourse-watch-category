discourse-watch-category
========================

A simple plugin that watches a category or sub-category for all the users in the system or all the users in a particular group.

Configure by editing `plugin.rb`.

To prevent conflicts with my changes, you should fork your own copy of this repository and then follow the typical [installation steps](https://meta.discourse.org/t/install-a-plugin/19157).

The plugin runs every 3 hours. You can trigger it manually at /sidekiq/scheduler
