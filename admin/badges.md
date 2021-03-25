# Badges

### Overview

Badges appear on user profiles and are a great way to reward your community. People love collecting badges!

### How To Create A Badge

Click 'Create Badge' and you'll be led to a form with the following fields: 

* Title: name of badge
* Slug: the URL for the badge \(/badges/slug-of-badge\) so people can read about the badge.
* Description: the description that appears when a user is awarded the badge
* Badge Image: upload an image of your badge
* Credits Awarded: number of credits awarded to a user after they were awarded the badge 

### How To Award A Badge

#### Manually

Most badges are awarded manually via `/admin/badges` and `/admin/badge_achievements`  by clicking the 'award badge' button. To award a badge: 

* Badge: Select the name of badge to be awarded
* Usernames: List the usernames of each user that should receive the badge in a comma-separated format.
* Override Default Message: The default message is the badge description, but you can override that message by adding a custom one here.
* Click 'Award Badges'

#### Automatically

We have a default set of badges that get awarded automatically.

Examples types of badges from DEV:

* **Contributor Badges:** the [DEV Contributor](https://dev.to/badge/dev-contributor) badge is awarded after a PR is merged into the DEV open open-source repo
* **Anniversary Badges**: the [1-year](https://dev.to/badge/one-year-club), [2-year](https://dev.to/badge/two-year-club), [3-year](https://dev.to/badge/three-year-club) badges are awarded on the anniversaries of a community member join date
* **Streak Badges:** the [4-week](https://dev.to/badge/8-week-streak), [8-week](https://dev.to/badge/8-week-streak), and [16-week](https://dev.to/badge/16-week-streak) streak badges are awarded for publishing a post in consecutive weeks
* **Top Post by Tag Badges**: various badges are awarded for the author with the most popular article in a specific tag
* **Beloved Comment**: [this badge](https://dev.to/badge/beloved-comment) is awarded automatically for any comment that reaches a certain threshold of positive reactions

### How do I set up an automatically-awarded badge?

The following badges can be awarded automatically.  To do so, be sure to set up a badge using a matching `slug`.

For the top post by tag badges, the Forem admin will need to create a badge and associate it with a tag.

Here's a comprehensive list of the badges' slugs to recreate:

| Badge Name | Badge Slug | Note |
| :--- | :--- | :--- |
| DEV Contributor | dev-contributor | This is not generalized.  This relates strictly to the DEV Open source repo. |
| `x` Year Badge | `x`-year-club | N\A |
| `x` Streak Badge | `x`-week-streak | capped at 16 weeks, must be 2,4,8,16 |
| Tag Badge | slug of the tag | associate the badge with a tag via /admin/badges |
| Beloved Comment | beloved-comment | Automatically awards a badge if someone's comment reaches 25 likes |

