# cwru-sympa-unsubscribe
Lessons in unsubscribing from lists in the CWRU Sympa Mailing List Manager.

# So You're On A Mailing List

Did you get an email from a list? Well, you're subscribed to it. Here's how you
check your subscriptions:

1. Sign in using [CWRU SSO][sso] and your Case ID
2. Visit the [CWRU Mailing List Manager][list-manager] and click the `Login`
button next to the "Single Sign-On (SSO)" option
3. View [`Your subscriptions`][list-subscriptions] to see all of the lists your
account is subscribed to

[sso]: https://login.case.edu/cas/login
[list-manager]: https://lists.case.edu/
[list-subscriptions]: https://lists.case.edu/wws/which

# You Don't Want To Receive Messages

Too many messages? Not relevant to your interests anymore? Devolving into spam?
Well, here are your solutions.

## Straight-up Unsubscribe

### Through the List Manager Web Interface

For most student-group lists and most semi-official CWRU lists, you can
unsubscribe from the list directly. From the [`Your
subscriptions`][list-subscriptions], find the list that you want to edit your
subscription to and click on the name of the list (e.g.
`example-list@case.edu`). In the left sidebar, there is an `Unsubscribe` button.
Press it to remove your subscription to the list.

Alternatively, if you already know the list you want to remove, login to the
List Manager and then edit the following URL.

```
https://lists.case.edu/wws/signoff/example-list
```

Where you replace `example-list` with the correct name of the list you want to
unsubscribe from.

### Directly via Email

Don't feel like opening the List Manager? No fear, it's possible to edit your
subscription directly from your email!

Send an email to `lists@case.edu` with the subject line `SIGNOFF example-list`.

Or, this will open your email client directly: [Example
Unsubscription](mailto:test@example.com?subject=SIGNOFF example-list)

## Can't Unsubscribe? There's a Solution: `Reception mode`

Some official lists do not permit you to unsubscribe. That doesn't mean the list
is free of annoying emails. They can be stopped, though.

In the left sidebar of a list page on the List Manager, there is a `Subscriber
Options` button. This settings page allows you to edit your `Reception mode` for
the list. By default, you will have the `normal` mode active. To stop receiving
messages from the subscribed list, change your mode to `no mail`.

The settings page URL for a list has the following format.

```
https://lists.case.edu/wws/suboptions/example-list
```
