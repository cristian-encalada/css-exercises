# A very common website feature

The goal of this exercise is to recreate a section that is found on many informational websites.

For this one you will need to edit the HTML a little bit too. We can't be making things _too_ easy for you. You'll want to add containers around the various elements so that you can flex them. Good luck!

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- [x] All items are centered on the page (horizontally, not vertically).
    - body -> text-align: center;
- [x] The title is centered on the page.
- [x] There is 32px between the title and the 'items.'
    - .content -> margin-top: 32px;
- [x] There is 52px between each item.
    - .content -> gap: 52px;
- [x] The items are arranged horizontally on the page.
    - .content -> display: flex;  justify-content: center;
- [x] The items are only 200px wide and the text wraps.
    - .item -> max-width: 200px;
- [x] The item text is centered.
