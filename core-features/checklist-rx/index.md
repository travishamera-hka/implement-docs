# {{ NgDocPage.title }}

## Setup Checklists
![Setup Checklists](./assets/img/checklist1.png)

ChecklistRx uses the checklists items from one card to create new cards use to document or track work as a full task.  For example this is typically ustilized with Meeting Management to generate new task cards from action items.  Any checklist item can be used to generate a new card using this tool.

1. Setting values like due dates and assignees will carry through automatically to the generated card, as well as the first feature assigned to the originating card.

![ChecklistRx button on card menu](./assets/img/checklist2a.png)

Access the ChecklistRx option using the button on the card tools menu.

## Configure Card Creation

![Use ChecklistRx to configure card creation](./assets/img/checklist2b.png)![Use ChecklistRx to configure card creation](/assets/img/checklist2c.png)

The tool provides an interface to select which checklist items should be used to generate new cards and configure information to be populated on the new cards as follows:

2. Check the box for each checklist item to create a card from.  The card name should already be populated.
3. The target list may be autoselected if the title of the checklist is configured in `*SettingsRx`.  Otherwise, set the target list here (this can be changed if auto-selected)
4. The parent feature will default to the first feature of the originating card (if set).  Leave as defaulted, delselect, or select a different feature.
5. Set a label for the new card
6. Define a member to be assigned if applicable (may be set by default if a member was assigned to the checklist item)
7. The start date default to the current date the card is being created
8. The due date defaults to a specific number of days from the current date.  This setting can be adjust in the `*SettingsRx` tool.  You can also override this to a different date here.
9. Placement determines whether the new card should be placed to the top or bottom of the target list.
10. Click the arrow button to generate all selected checklist items as configured.  A countdown will be shown on the screen as each checklist item is processed.  Do not navigate away from this screen until the countdown is complete as it may halt the checklist creation process.

## Cards Created and Linked

![Links to Cards from Checklist](./assets/img/checklist3.png)

11. Each checklist item will be updated to identify that it was converted to a card and includes a link to the generated card.

![Card Created from Checklist](./assets/img/checklist4.png)

The new card will include values from any of the configurations made when the card was generated.

![Links from Cards back to Checklist](./assets/img/checklist5.png)

12. Each generated card will also include a link back to the original card with the checklist item used to create the card.