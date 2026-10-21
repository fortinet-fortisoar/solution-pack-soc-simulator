| [Home](../README.md) |
|----------------------|

# Customize scenario simulator

The **Scenario Simulator** widget does not have its own configuration. Everything the widget displays is read from records in the **Scenario** module, which the SOC Simulator solution pack installs. To change how a scenario appears in the widget, edit its Scenario record.

You can customize the title, description, icon, and tags of any scenario that ships with the solution pack.

>[!Warning]
>Do not modify the **Steps** field. This field contains the JSON definition that drives the simulation, including the playbook references that create the demo records. Changing it can prevent the scenario from running or from resetting correctly.

## Fields that appear in the widget

| Field | Where it appears | Notes |
| --- | --- | --- |
| Title | Card heading | Matched by the widget search box. |
| Description | Card body | Supports Markdown. Matched by the widget search box. |
| Icon | Thumbnail at the left of the card | Falls back to a placeholder image when empty. |
| Tags | Chips at the bottom of the card | Matched by the widget search box. |

## Customize a scenario

1. Go to **Resources** <picture><source media="(prefers-color-scheme: dark)" srcset="./res/chevron-right-light.png"><img src="./res/chevron-right-dark.png" alt="then"></picture> **Simulations**.

1. Select the scenario you want to change to open its detail view.

1. Click **Edit Record**.

1. Update any of the following:

   - **Title**: Enter the name that appears as the card heading.
   - **Description**: Enter the summary that appears in the card body. See [Format the description](#format-the-description).
   - **Icon**: Drag an image file into the field. See [Add or replace the icon](#add-or-replace-the-icon).
   - **Tags**: Click **+ Add Tags** at the top of the record, then enter or select a tag.

1. Click **Save**.

1. Open the widget and click the refresh button to load your changes.

>[!Note]
>The widget also updates on its own when a Scenario record changes, but a manual refresh confirms the result immediately.

## Format the description

The description is stored as Markdown and rendered as formatted text in the widget. Use the **Write** and **Preview** tabs in the editor to check the result before you save.

The widget shows the first three lines of the description and adds a **View More** link when the text is longer. Put the most important information in the opening lines so that it is visible before a user expands the card.

## Add or replace the icon

The **Icon** field is a rich text field. Drag an image file into the field, and FortiSOAR encodes it and stores it with the record.

Keep the following in mind:

- FortiSOAR blocks SVG uploads. Use a raster format such as PNG or JPEG.
- The widget renders the icon in an 81 by 81 pixel container. Use a square image at or near that size so that it is not cropped or scaled unevenly.
- When the field is empty, the widget displays a placeholder image in its place.

## What the widget displays

The widget lists up to 30 scenarios, sorted by creation date with the newest first. If your environment contains more than 30 scenarios, use the search box to find a specific one.

## Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) | [Contents](./contents.md) |
|-----------------------------------------|-------------------------------------------|---------------------|---------------------------|