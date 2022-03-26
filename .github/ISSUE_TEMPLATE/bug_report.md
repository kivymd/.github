---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''
---

<!-- 
How to create a Minimal, Reproducible Example
---------------------------------------------

When asking a question, people will be better able to provide help if you provide code that they can easily understand and use to reproduce the problem. This is referred to by community members as creating a minimal, reproducible example (reprex), a minimal, complete and verifiable example (mcve), or a minimal, workable example (mwe). Regardless of how it's communicated to you, it boils down to ensuring your code that reproduces the problem follows the following guidelines:

Your code examples should be:
-----------------------------

1. Minimal – Use as little code as possible that still produces the same problem
2. Complete – Provide all parts someone else needs to reproduce your problem in the question itself
3. Reproducible – Test the code you're about to provide to make sure it reproduces the problem

The rest of this help article provides guidance on these aspects of writing a minimal, reproducible example.

Minimal
-------

The more code there is to go through, the less likely people can find your problem. Streamline your example in one of two ways:

1. Restart from scratch. Create a new program, adding in only what is needed to see the problem. Use simple, descriptive names for functions and variables – don’t copy the names you’re using in your existing code.

2.Divide and conquer. If you’re not sure what the source of the problem is, start removing code a bit at a time until the problem disappears – then add the last part back.

Minimal and readable
--------------------

Don't sacrifice clarity for brevity when creating a minimal example. Use consistent naming and indentation, and include code comments if needed. Use your code editor’s shortcut for formatting code. Also, use spaces instead of tabs – tabs might not get correctly formatted on Stack Overflow.

Complete
--------

Make sure all information necessary to reproduce the problem is included in the question itself.

DO NOT use images of code. Copy the actual text from your code editor, paste it into the question, then format it as code. This helps others more easily read and test your code.

Reproducible
------------

To help you solve your problem, others will need to verify that it exists:

Describe the problem. "It doesn't work" isn't descriptive enough to help people understand your problem. Instead, tell other readers what the expected behavior should be. Tell other readers what the exact wording of the error message is, and which line of code is producing it. Use a brief but descriptive summary of your problem as the title of your question.

Double-check that your example reproduces the problem! If you inadvertently fixed the problem while composing the example but didn't test it again, you'd want to know that before asking someone else to help.
-->

### Description of the Bug

Your text


### Code and Logs

```python
from kivy.app import App
from kivy.lang import Builder

kv = """
Screen:
    # KV-Code
"""


class MainApp(App):
    def build(self):
        self.root = Builder.load_string(kv)


if __name__ == '__main__':
    MainApp().run()
```


### Screenshots

Add images to explain us this bug. Paste urls here.

Remove this section if no images here


### Versions

* OS: 
* Python: 
* Kivy: 
* KivyMD: 
