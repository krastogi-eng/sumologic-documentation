---
id: tags-insights-signals-entitiesc-rules
---

# Using Tags with Insights, Signals, Entities, and Rules

## What are tags?

Tags are metadata you can attach to Insights, Signals, Entities, and Rules. Tags are useful for adding context to these CSE items. You can also search for and filter items by tag.

There are two types of tags: 

* **Schema keys**. These are predefined key-value pairs, which are useful for ensuring that users use  consistent values when assigning tags to items. There are two built-in schema tags: **Tactic** and **Technique**, which relate to the Mitre ATT&CK framework. 

    You can create your own schema tags as well, as described in [Create a Custom Tag Schema](../administration/create-a-custom-tag-schema.md). You can optionally configure a URL for each value in a custom tag schema. If you do, a user will be able to open that URL from the tag’s Action menu when it’s presented in the CSE UI. See [Tag Actions](tags-insights-signals-entities-rules.md) below for an example.
    
    You can assign schema key tags to custom Rules you’ve developed.  For  built-in rules, you can assign or delete new  schema tags, but you can’t change or remove the tags that come with the rule. You can also assign schema key tags to Insights, both CSE-generated and custom.    
* **Keyword tags**. These are arbitrary labels that you define yourself. You can assign keyword tags to custom Rules, Entities, and Insights, both CSE-generated and custom. You can’t remove or change the tags that come with built-in rules. 

A tag attached to a Rule is applied to Signals that the Rule generates. Similarly, tags applied to a Signal are applied to the Insights the Signal contributes to. All of the tags applied to an Insight's contributing Signals are aggregated, de-duplicated, and applied to the Insight. Note that an item is tagged when it is created. So, if you add a tag to a rule, Signals and Insights created before you updated the rule will not have that tag applied.

## Tags and types

Some items that support tags in CSE can be tagged explicitly from the
CSE UI. Some can inherit tags from another item. The table below
summarizes this behavior.

| Type                     | Supports explicit tag assignment? | Items inherit tags from...      |
|--------------------------|-----------------------------------|---------------------------------|
| Built-in rule            | yes                               | \-                              |
| Custom rule              | yes                               | \-                              |
| Custom Insight           | yes                               | \-                              |
| System-generated Insight | yes                               | Rule(s), Entity, Custom Insight |
| Entity                   | yes                               | \-                              |
| Signal                   | no                                | Rule(s), Entity                 |

## View tags

You can view tags on the pages that provide summary views of Insights, Signals, Entities, and Rules. You can also view the tags assigned to an item on the detailed page you see when you navigate to a particular Insight, Signal, Entity, or Rule. 

This is an overview of an Insight from the Insights page. Multiple schema key tags are attached to the Insight.

![insight-list-tags.png](/img/cse/insight-list-tags.png)

The screenshot below shows an Entity to which a schema tag is attached.

![entity-list-tags.png](/img/cse/entity-list-tags.png)

## Tag actions

The actions menu for a tag allows you to:

* Open an URL, if the tag is a schema tag, and an URL is configured for the selected tag value.
* Copy the raw tag to your clipboard.

    ![tag-action-menu.png](/img/cse/tag-action-menu.png)

## Find the tagging UI

The procedure for tagging Rules, Entities, and Insights is similar. The
difference is where you do the tagging. 

### UI for tagging a Rule

1. Select **Rules** from the **Content** menu.
1. Navigate to a custom rule.
1. The UI for tagging is at the bottom of the **Then Create a Signal** area of the **Rule Editor**.
1. To add a tag, follow the instructions in [Add a schema key tag](#apply-a-schema-key-tag) or [Add a keyword tag](#apply-a-keyword-tag).

![tag-a-rule.png](/img/cse/tag-a-rule.png)

### UI for tagging an Entity

1. Click the **Entities** tab at the top of the CSE UI.
1. Navigate to the Entity to which you want to attach a tag.
1. The UI for tagging is at the bottom of the **Details** pane.
1. To add a tag, follow the instructions in [Add a keyword tag](#apply-a-keyword-tag).

![tag-an-entity.png](/img/cse/tag-an-entity.png)

### UI for tagging an CSE-generated Insight

Note that in addition to tags that you manually assign to an Insight, an Insight will inherit any tags that were applied to the content that went into the Insight—the entity and the rule(s) or custom insight definitions that created the included signals—will automatically be inherited (and aggregated) by the Insight. 

1. Click the **Insight** tab at the top of the CSE UI.
1. Navigate to the Insight to which you want to attach a tag.
1. The UI for tagging is at the bottom of the **Details** pane.
1. To add a tag, follow the instructions in [Add a schema key tag](#apply-a-schema-key-tag) or [Add a keyword tag](#apply-a-keyword-tag).

![tag-an-insight.png](/img/cse/tag-an-insight.png)

### UI for tagging a custom Insight

1. Select **Custom Insights** from the Content menu.
1. Navigate to a custom Insight.
1. The UI for tagging is at the bottom of the **Then Create a Signal** area of the Insight Editor.
1. To add a tag, follow the instructions in [Add a schema key tag](#apply-a-schema-key-tag) or [Add a keyword tag](#apply-a-keyword-tag).

![custom-insight.png](/img/cse/custom-insight.png)

## Apply a schema key tag

1. Navigate to the item to which you want to add a tag, as described in the previous section. 
1. In the tagging section, click the chevron icon.

    ![chevron-icon.png](/img/cse/chevron-icon.png)
1. Click a tag under **Schema Keys.**

    ![tag-list-1.png](/img/cse/tag-list-1.png)
1. A list of values appears. 

    [values.png](/img/cse/values.png)
1. Select a tag value, and press Return to add it to the item. 

### Apply a keyword tag

1. Navigate to the Rule, Entity, or Insight to which you want to add a tag, as described in [Find the tagging UI](#find-the-tagging-ui).
1. In the tagging section, click the chevron icon.

    ![chevron-icon.png](/img/cse/chevron-icon.png)
1. A list of keyword tags that have already been assigned to items of the current type (Rule, Entity, or Insight) appears. You can select an existing tag, or add a new one. Enter text in the field to see a list of matching values.

    ![freeform-tag-list.png](/img/cse/freeform-tag-list.png)
1. To add a new tag, enter it and press Return. 

    ![add-freeform-tag.png](/img/cse/add-freeform-tag.png)
1. The tag is added to the item.

    ![freeform-added.png](/img/cse/freeform-added.png)

## Search by tag

### Search Insights, Signals, or Entities by tag

1. Click in the search area and then click the funnel icon.

    ![funnel-icon.png](/img/cse/funnel-icon.png)
1. Select **Insights**, **Signals**, or **Entities** from the **Sources** list.

    ![sources.png](/img/cse/sources.png)
1. Select **Tags** from the **Fields** list.

    ![tags-field.png](/img/cse/tags-field.png)
1. Choose **contain** or **do not contain** from the **Operators** list.

    ![operators.png](/img/cse/operators.png)
1. Select a tag from either the **Schema Keys** or **Keyword Tags** list. If you select a tag from the **Schema Keys** list, you are prompted to select a value, and items that match are listed. If you select a tag from the **Keywords list**, items that match are listed.

### Search Rules by tag

1. Select **Rules** from the **Content** menu.
1. Click in the **Filters** area and select **Tags** from the **Fields** list.

    ![search-rules-by-tag.png](/img/cse/search-rules-by-tag.png)
1. Choose **contain** or **do not contain** from the **Operators** list.

    ![operators.png](/img/cse/operators.png)
1. Select a tag from either the **Schema Keys** or **Keyword Tags** list. If you select a tag from the **Schema Keys** list, you are prompted to select a value, and items that match are listed. If you select a tag from the **Keywords Tags** list, items that match are listed. Note that if an item has a Mitre-related tag, an icon appears next to it. Click the icon to view a Mitre page on the Tactic or Technique.

    ![search-results.png](/img/cse/search-results.png)

### Filter a list view by clicking a tag

On the Insights, Signals, Rules, or Entities page, you can click a tag to filter the list. For example, if you click the **Tactic:TA0005 - Defense Evasion** tag on an Insight, like this:

![filter-list-by-tag.png](/img/cse/filter-list-by-tag.png)

the page will be filtered to show only Insights that have that tag:

![filtered-list.png](/img/cse/filtered-list.png)  
 