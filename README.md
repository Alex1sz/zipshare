# ZipShare

## Vision

ZipShare is a self-hostable image, text, and other media hosting and sharing
tool. It was born out of my frustration with needing to publish images on imgur
or twitters hosting service instead of on infrastructure I retain some level of
rights and control over.

## Architecture

ZipShare takes an API-first approach to service development. The [ZipShare
API](https://github.com/zipshare/zipshare-api) is where most features will be
built, with the [ZipShare CLI](https://github.com/zipshare/zipshare-cli) being
the first consumer of those features. Once the CLI and API have proven out the
interface for a feature, the [ZipShare
Web](https://github.com/zipshare/zipshare-web) interface will integrate the
features.

Both the CLI and Web application use the [ZipShare Ruby
Client](https://github.com/zipshare/zipshare-rb) to interact with the API.

## Roadmap

#### Alpha 1 - Hey, I can Host Things!
Allow invited users to upload media using the web app as well as the command
line. It will have very few features as we'll be absorbing the cost of setting
up testing and development infrastructure.
 * [API tasks](https://github.com/zipshare/zipshare-api/milestones/Alpha%201)
 * [Ruby Library tasks](https://github.com/zipshare/zipshare-rb/milestones/Alpha%201)
 * [CLI tasks](https://github.com/zipshare/zipshare-cli/milestones/Alpha%201)
 * [Web tasks](https://github.com/zipshare/zipshare-web/milestones/Alpha%201)

#### Alpha 2 - Let's Get Securitish
End-to-end encryption on a per-file basis with a shared-secret as well as a
application-level tokens so a user may grant and revoke access to applications
on a per-app level instead of a single shared secret. Oh, and some TLS please.
 * [API tasks](https://github.com/zipshare/zipshare-api/milestones/Alpha%202)
 * [Ruby Library tasks](https://github.com/zipshare/zipshare-rb/milestones/Alpha%202)
 * [CLI tasks](https://github.com/zipshare/zipshare-cli/milestones/Alpha%202)
 * [Web tasks](https://github.com/zipshare/zipshare-web/milestones/Alpha%202)

#### Alpha 3 - Eff You, Pay Me
Annual and monthly plans. After all, what company doesn't process payments in
some way, shape or form?
 * [API tasks](https://github.com/zipshare/zipshare-api/milestones/Alpha%203)
 * [Ruby Library tasks](https://github.com/zipshare/zipshare-rb/milestones/Alpha%203)
 * [CLI tasks](https://github.com/zipshare/zipshare-cli/milestones/Alpha%203)
 * [Web tasks](https://github.com/zipshare/zipshare-web/milestones/Alpha%203)


#### Alpha 4 - Referrals!
Hey, when people like something they tend to refer friends. Let's encourage our
users to invite other users.

 * [API tasks](https://github.com/zipshare/zipshare-api/milestones/Alpha%203)
 * [Ruby Library tasks](https://github.com/zipshare/zipshare-rb/milestones/Alpha%203)
 * [CLI tasks](https://github.com/zipshare/zipshare-cli/milestones/Alpha%203)
 * [Web tasks](https://github.com/zipshare/zipshare-web/milestones/Alpha%203)



## Contributing
Our [contribution guidelines](CONTRIBUTING.md) are summarized as:
* Work on whatever you think fits within the vision of Zipshare
* Create issues when you think of an enhancement or find a bug. Submit patches when
  you can.
* CodeUnion owns all the software.
* Be compassionate and kind to one another. Harassment or verbal abuse of any
  kind is not tolerated.
