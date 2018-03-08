# Pattern: Shared Google Group Inbox

The goal of this pattern is to create a shared space for receiving email.

This is done by configuring an **email alias** to forward to a **private Google Group** that has been set up such that:

1. only members can view posts, but
2. any non-members can _create_ posts.

In practice, this means that new posts can be created from any incoming email sent through the alias, but that only members can view the conversations in-browser.

This benefits over email aliases forwarded directly to personal or shared GMail accounts. Specifically:

* **Permission system intended for shared management.** Google Groups expect to have multiple administrators and different degrees of access -- each person uses their own Google account to log in.
* **Record of history in easily shared space.** When new people arrive, they join the group and have full access to past communications -- no forwarding emails, or logging into obscure organizational email accounts.
* **Customizable notification levels.** Google Groups are intended to let people fine tune their notifications -- an email per message, a daily digest, or completely disable notification in favour of just visiting the web interface.

How to use:

* Have people contact you through the alias.
* When sending outgoing mail from personal gmail accounts, cc the alias.
* You may configure your personal GMail account [like so](https://webapps.stackexchange.com/questions/66228/add-new-alias-to-gmail-without-smtp-forwarding-only-address/72975#72975), but:
  * For scrappy, grassroots groups, we recommend NOT using the alias to send outgoing mail. This is for a couple reasons:
    * It may seem more "official", but that comes with much higher expectations, sometimes difficult to meet by volunteers.

    * People are nicer and more understanding when you speak to them through personal email addresses.

Examples of when this might be useful:

* **Role transition.** Assume that speakers@example.com is used for speaker booking within an organization. When the role is being passed off, the new holder of the position can be added to the group. They now receive email along with the outgoing member. They can both receive for awhile, and once things are going smoothly, the outgoing person can disable the Google Groups email notifications, without giving up ability to catch up if need be.
* **Onboarding new members.** When a new member joins and organization, if the organization's email has been going through a collaborative Google Group, then that new member can use the web interface to see how past email interactions were conducted. There is no need for them to explicitly ask veteran members to search for and send previous examples of communications. New message arrive in their inbox, and they can participate in triage.



