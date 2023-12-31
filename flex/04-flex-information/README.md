# A very common website feature

The goal of this exercise is to recreate a section that is found on many informational websites.

For this one you will need to edit the HTML a little bit too. We can't be making things _too_ easy for you. You'll want to add containers around the various elements so that you can flex them. Good luck!

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- All items are centered on the page (horizontally, not vertically).
    - Yes -> body -> text-align: center;
- The title is centered on the page.
    - Yes
- There is 32px between the title and the 'items.'
    - Yes -> .content -> margin-top: 32px;
- There is 52px between each item.
    - Yes -> .content -> gap: 52px;
- The items are arranged horizontally on the page.
    - Yes -> .content -> display: flex;  justify-content: center;
- The items are only 200px wide and the text wraps.
    - Yes -> -item -> max-width: 200px;
- The item text is centered.
