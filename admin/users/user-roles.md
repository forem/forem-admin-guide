---
description: A description of different user roles across the site.
---

# User Roles

A users's role indicates the level of permissions they have across the site.

## Base Roles

### Ban

Users with the 'ban' role no longer have the privilege to publish posts or comments across the site. Typically, a user is banned when they have broken the code of conduct or terms multiple times.

### Comment Ban

Users with the 'comment ban' role are users that no longer have the privilege to comment on posts. This role is typically reserved for users who struggle to communicate appropriately on comments but for some reason, publish completely appropriate posts.

### Pro

Users with the 'pro' role are users with access to additional analytics on their posts when they visit their dashboard. Additional analytics include traffic sources, and weekly and monthly engagement summaries. 

### Regular Member

A regular member is a user in good standing. They have access to all basic privileges \(publishing posts, writing comments, etc\) but they do not have higher access such as community moderation or site administration. 

### Trusted

Users with the 'trusted' role are your basic community moderators. They have access to `/mod` and see a moderate icon on every post. Learn how moderation works by visiting the [moderation page](../../community-tips/moderation.md).

Our next level of moderators are Tag Moderators. These are trusted users with an additional set of privileges: permission to moderate specific tags across the community. You can make a user a tag moderator by visiting the associated [tag admin page](../tags.md).

### Warn

Users with the 'warn' role are users that admins flag to one another because of their previous behavior across site. These are typically users that have broken the code of conduct previously with a minor offense. While we didn't ban their role the first time, we want to make sure their previous actions are taken into consideration if they break the code of conduct again. 

Users with the 'warn' role have all the same privileges as users with good standing.

Changing a users's status to the warn role does not automatically send an email to the user \(though, we do recommend that you consider letting them know they are in a 'warned' state\). 

## Special Roles

### Admin

Admins have access to all /admin pages on the site but do not have the ability to make site configuration changes \(i.e. admin/config\). We recommend limiting the number of people who have admin permissions and considering single resource admin privileges first.

### Single Resource Admin

Single resource admins have access to select /admin pages. For example,`single_resource_admin: users` gives access to `/admin/users` only. You can give someone as many single resource admin pages as you'd like. 

### Super Admin

Super admins have the highest level of permissions across the site, including making changes to `/admin/config/`.

