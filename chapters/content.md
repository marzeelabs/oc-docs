---
layout: page
title: "Chapter 2: Content"
description: ""
---
{% include JB/setup %}

Content that can be entered in your website is organized in different types:

* [Article](#article)
* Event
* Featured content
* [Institution](#institution)
* Page
* Project
* Work Package
* [Researcher Profiles](#profile)

Every content item has a set of fields specific for that content type. For example an `institution` has name and address, while an `event` has a title, a date, an address and some tags.

## Creating content

Click `My Workbench` > `Create content`

Now, click one of the content types to start adding a new content item. We recommend starting with `Institution`.

#### Content Moderation

By default, any content item will be placed in a `Draft` state and the content will not be publicly available yet. You can iterate on a draft until you are happy with the final result and then set the state to `Published`.

#### Content Revisions

Every time a new content item is saved, the changes are saved as well so that we can keep a revision history for every content item. This allows you to restore previous revisions or track who changed what in a content item.

## Content Types

### <a id="institution">Institution</a>

An institution is an organization that is involved in the consortium, be it a university, a company, or any other type of organization.

### <a id="profile">Researcher Profiles</a>

Strictly speaking, a researcher profile is more than just content. Every profile is associated to a real user on the site, who can log in on the site and change her or his profile. Initially, you as editor will add these profiles and link them up to the correct institution (this is why you need to create institutions first).

Click `My Workbench` > `Researcher Profiles` > `+ Add researcher profile`

And add your first user on the website (e.g. the project coordinator). You need to enter data for the following fields

* Username: chose something like `jsmith` for John Smith
* E-mail address: this is the address that can be used to access the website
* Password: you can use a dummy password for now, since you won't (yet) allow other users to log in to the site.
* Status: this is `Blocked` by default. Leave this for now, as we won't allow these users to log in (yet)
* Researcher Profile: this is the part that will be shown publicly on the researcher's page
 * Project Role: typically shown below the photo of the user
 * ..
 * Photo: upload a high-resolution profile picture here, preferably all in the same style. We'll take care of resizing it correctly
 * Email: this is not necessarily the same email address as that one you entered above, but this will be shown publicly. We'll take care that person doesn't receive spam because of that!
 * ...
 * Institution: this will make a link with the previously entered Institution.
 * Address: provide an accurate address here. We'll geocode this address to use it on a map.

