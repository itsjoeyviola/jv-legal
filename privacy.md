# Privacy Policy — JV Tracker

**Last updated: 5 September 2026**

JV Tracker is a private, single-operator publishing tool. It is operated by Joey
Viola solely to publish his own short-form video content to his own social media
accounts, including TikTok. It is not offered to the public, has no other users,
and no one else can sign in to it.

## What this application accesses

When authorised against a TikTok account, JV Tracker uses the TikTok Content
Posting API with the `video.publish` scope. Through it the application:

- reads **creator information** returned by TikTok (account nickname, the
  privacy-level options currently available to the account, and posting limits)
  in order to display the correct options and to send settings consistent with
  them, as TikTok's UX requirements direct; and
- **uploads and publishes video files** that the operator has created, together
  with a caption the operator has written.

It requests no other scope. It does not read the operator's followers, direct
messages, comments, analytics, or any other person's content.

## What is stored, where, and for how long

- **Access and refresh tokens** are stored in a single file on the operator's own
  computer, readable only by the operator's user account (mode 600). They are
  never transmitted anywhere except to TikTok's own API endpoints.
- **Video files and captions** are stored on the operator's own computer and sent
  to TikTok in order to publish them.
- **Publish identifiers and timestamps** returned by TikTok are recorded in the
  operator's own private spreadsheet so that a video is never posted twice.

There is no server, no database, no hosting provider, and no analytics or
tracking of any kind. Nothing is stored in a cloud service controlled by this
application.

## What is not done with the data

- No data obtained from TikTok is sold, rented, licensed, or shared with any
  third party.
- No data is used for advertising, profiling, or training machine-learning models.
- No data belonging to any TikTok user other than the operator is collected,
  because the application is only ever authorised against the operator's own
  account.

## Retention and deletion

Tokens are kept only while the integration is in use and are overwritten each
time they are refreshed. The operator can revoke this application's access at any
time from **TikTok › Settings and privacy › Security and permissions › Manage app
permissions**, which immediately invalidates the stored tokens. To delete all
stored data, the operator deletes the local credentials file; because nothing is
stored anywhere else, no further action is required.

## Children

The application is not directed at children and collects no data from anyone
other than its single operator.

## Changes

Any change to this policy will be published at this URL with an updated date.

## Contact

Questions about this policy: **joseph23v@icloud.com**
