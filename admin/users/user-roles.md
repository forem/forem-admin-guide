---
description: A description of different user roles across the site.
---

# User Roles

A users's role indicates the level of permissions they have across the site.

## Base Roles

### Warn

### Comment Ban

### Trusted

Trusted users are your basic community moderators. They have access to `/mod` and see a moderate icon on every post. Learn how moderation works by visiting the [moderation page](../../community-tips/moderation.md).

You can give a user the 'trusted' privileged by navigating to their profile via `admin/user -> 'manage user'` and setting their user status to `Trusted`.

## Special Roles

### Admin

Admins have access to all /admin pages on the site but do not have the ability to my site configuration changes \(i.e. admin/config\). We recommend limiting the number of people who have admin permissions and considering single resource admin privileges first.

### Single Resource Admin

Single resource admins have access to select /admin pages. For example,`single_resource_admin: users` gives access to `/admin/users` only. You can give someone as many single resource admin pages as you'd like. 

### Super Admin

Super admins have the highest level of permissions across the site, including making changes to `/admin/config/`.

### Tag Moderator

Tag Moderators are trusted users with an additional set of privileges: permission to moderate certain tags across the community. 

You can make a user a tag moderator by visiting the associated [tag page](../tags.md).

