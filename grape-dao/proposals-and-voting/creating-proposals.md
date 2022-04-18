---
description: Discourse and on-chain Proposals
---

# Creating Proposals

### Proposals

There are two different kinds of proposals:

* [<mark style="color:purple;">**Discourse**</mark>](https://dao.grapenetwork.org)
* <mark style="color:purple;"></mark>[<mark style="color:purple;">**realms**</mark>](https://realms.today) (on-chain)

Discourse is our main tool for preparing and discussing proposals that later can be voted on. Our aim is to prepare and discuss proposals in advance and then execute them with an on-chain vote on realms. A proper proposal should always have some kind of reference to either a Discourse \[Discussion] or a post so that the people who vote are able to understand the background of the proposal.

Since, for the time being, on-chain votes on _**realms**_ can only have a _**binary outcome**_, multiple-choice votes are done on Discourse.

### Adding a poll for voting on Discourse

You create a poll for voting with the poll builder. The poll builder can be accessed from the<img src="https://emoji.discourse-cdn.com/twitter/gear.png?v=9" alt=":gear:" data-size="line"> in the topic composer:

![](../../.gitbook/assets/adding\_poll.png)

This will appear once you have pressed ‘build poll’:

![](../../.gitbook/assets/build\_poll.png)

To show advanced options press the <img src="https://emoji.discourse-cdn.com/twitter/gear.png?v=9" alt=":gear:" data-size="line"> icon. This will show you different poll options such as poll auto close, groups allowed to vote etc.

#### Poll Options

**Type:**

* Single Choice: Default poll type. Users can select a single choice from the poll\
  (This is the default option you want to choose for a YES|NO|ABSTAIN vote).
*   Multiple Choice: Users can select multiple choices from the poll.

    The poll creator must also define the minimum and maximum number of choices a user can make. By default, the minimum will be 1, and the maximum will be the number of poll choices.
*   Number Rating: Users can select a single number.

    The poll creator must also define the min, max and step for the number rating. For example, if the min is `2`, the max is `10`, and the step is `2`, the options will be 2, 4, 6, 8, and 10.

**Results:**

* Always visible: Default poll results. Users can always see the results of the poll, regardless of if they’ve voted.
* Only after voting: Users must vote before they can see the results of the poll.
* When the poll is closed: Poll results will only be revealed once the poll is closed.
* Staff only: Only site staff will be able to see the poll results.

{% hint style="info" %}
Discourse polls can be used for a pre-selection to find a viable solution out of different options which then can be put to an on-chain vote.
{% endhint %}

### Adding a proposal on realms

Everyone who has 200.000 $GRAPE or more on realms is able to create proposals.&#x20;

![New Proposal](../../.gitbook/assets/new\_proposal.PNG)

Once in the creation screen, there are two options to proceed with setting up the proposal (\[1], see below). A short, precise title helps since the proposal will most like be shared a lot.\
The description can either be done:

1. directly in realms (simple)
2. in [<mark style="color:purple;">**Github Gist**</mark>](https://gist.github.com) (advanced)

Proposals, in general, should be **clear**, **concise**, and **informative**. They should also contain a reference link that directs a reader/voter to the proposals' origin (e.g. Discourse).&#x20;

![Preparing a proposal](../../.gitbook/assets/create\_proposal.png)

{% hint style="info" %}
If you create a proposal using Github Gist, paste only the link in the field 'Description' \[1]; putting anything else will fail on execution and the Github Gist content won't be parsed.\
Here is a [<mark style="color:purple;">**template**</mark>](https://gist.github.com/CryptoPawz/7c13f52bf9c9e8189d00b957e1d53f8f) and this is some [<mark style="color:purple;">**markup**</mark>](https://gist.github.com/ww9/44f08d44327a40d2ab309a349bebec57) (not everything will show correctly).\
[_<mark style="color:purple;">**This**</mark>_](https://realms.today/dao/GRAPE/proposal/ECvFEgo6fzTfYgQop7Vrfby7VGumSWN89dX6uUMp1fin) _is what the template proposal looks like._
{% endhint %}

In order to create a proposal without any on-chain instruction, just select 'None' and choose any wallet under 'Governance' \[2]. If you want to add any on-chain instructions, simply chose the transaction type and the correct wallet. Be extra cautious and always check twice. You can always save the draft and let a fellow DAO Member cross-check.

{% hint style="danger" %}
Once you select 'Save draft' or 'Add proposal' \[3] you neither can change the instructions nor the title or description! The only difference with a draft is that the proposal isn't live.
{% endhint %}

\
