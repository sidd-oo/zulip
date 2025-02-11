# Restrict permissions of new members

{!admin-only.md!}

In large Zulip organizations where
[anyone can join](/help/allow-anyone-to-join-without-an-invitation), it can
be useful to restrict what new members can do, to make it easier to cope
with spammers and confused users.

Members are **new members** from when they join till when their account ages
past a certain **waiting period** threshold. After that they are **full members**.
You can configure how long the waiting period is, as well as which actions require
being a full member.

Various actions support restricting access to full members, including
[creating streams](/help/configure-who-can-create-streams),
[inviting users to the organization](/help/invite-new-users),
[adding custom emoji](/help/custom-emoji#change-who-can-add-custom-emoji),
and many more.

## Set waiting period for new members

{start_tabs}

{settings_tab|organization-permissions}

1. Under **Joining the organization**, configure
   **Waiting period before new members turn into full members**.

{!save-changes.md!}

{end_tabs}

## Related articles

- [Roles and permissions](/help/roles-and-permissions)
