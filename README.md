# GitHub Actions for Glo

The set of GitHub Actions to automatically update your [Glo](https://www.gitkraken.com/glo) cards. Links to Glo cards from within a Pull Request description or commit message can trigger the following actions:

- Move a Glo card(s) to any column on your board
- Add a label to a Glo card(s)
- Assign a user to a Glo card(s)
- Add a comment to a Glo card(s)

## Actions

[`Parse Glo Links`](https://github.com/Axosoft/glo-action-parse-links)
Parse your Pull Request description for links to cards

[`Change Column`](https://github.com/Axosoft/glo-action-move-card)
Change the column of a card(s)

[`Add Label`](https://github.com/Axosoft/glo-action-label-card)
Add an existing label to a card(s)

[`Assign User`](https://github.com/Axosoft/glo-action-assign-card)
Assign a Glo user to a card(s)

[`Add Comment`](https://github.com/Axosoft/glo-action-comment-card)
Add a comment to a card(s)

## Usage
An example workflow to trigger moving a card in Glo when a PR is merged.

```
{...}
```

Read more at the [GitKraken Support](https://support.gitkraken.com) site 
