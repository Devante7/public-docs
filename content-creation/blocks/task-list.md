---
description: Task list content block
---

# Task list

Task lists allow you to create a list of items with checkboxes that you can check or uncheck. This is useful for tracking project items, shopping lists, create playbooks and more.

### Example of a task list

* [ ] &#x20;Here's a task that hasn't been done
  * [x] And here's a subtask that has been done, indented using `tab`.
  * [ ] Aaaaand, here's a subtask that hasn't been done.
* [ ] Finally, an item, unidented using `shift` + `tab`.

### Git sync representation in markdown

```markdown
- [ ] Here's a task that hasn't been done
  - [x] And here's a subtask that has been done, indented using `tab`
  - [ ] Aaaaand, here's a subtask that hasn't been done.
- [ ] Finally, an item, unidented using `shift` + `tab`.
```

{% hint style="info" %}
Please note that readers of your published space will not be able to check or uncheck these boxes. You decide which boxes are checked and unchecked when you write the content.
{% endhint %}