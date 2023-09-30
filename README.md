# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, past, share** code. 
A good _Cloud Engineer_ uses Codeblocks whenver possible. 

Because it allows otheres to copy and paste their cdoe to replicate or research issues.

-In order to create codeblocks in markdown you need to use three backticks (`)
-Not to be confused with quotations (')

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end
```
- Make note of where the backtick character key is located. 
- It should appear above the tab key,
- but it may vary based on your keyboard layout.

![backtick](https://github.com/AmberL23/github-docs-example/assets/142250106/410b80ab-d6bb-4a4c-a2fe-06a665ba1f96)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console. 

```bash
#!/bin/bash

# Attempting to access a non-existent file
non_existent_file="non_existent.txt"
cat $non_existent_file
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 2 - How to take screenshots

A screenshot is when you capture a part of your screen from your laptop, desktop, or phone. 

This is not to be confused with taking a photo with your phone. Do not take a photo with your phone. 

Take a screenshot from your laptop. 




## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [^2]
- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

##  Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) Supports emoji shortcodes.
Here are some examples:

| Name  | Shortcode  |Emoji |
| ---|--- | --- |
| Cloud  | `:cloud:`  | ☁️   |
| Cloud with lightning and rain  |`:cloud_with_lightning_and_rain:` | ☁️   |

## Step 5 - how to create a table 

You can use the following markdown format to create tables: 

```markdown
| Name  | Shortcode  |Emoji |
| ---|--- | --- |
| Cloud  | `:cloud:`  | ☁️   |
| Cloud with lightning and rain  |`:cloud_with_lightning_and_rain:` | ☁️   |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [^3]
- Make note of where the pipe character key is located. 
- It should appear above the enter key,
- but it may vary based on your keyboard layout.
  
![pipe-character](https://github.com/AmberL23/github-docs-example/assets/142250106/73debf90-0c84-444e-9b37-e5b5909c3edf)

[Secret Window Hidden Garden](secret-window/hidden-garden.md)

## External References 
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Getting started with Writing and Formatting (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)
- [GTM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
[^1]: [GitHub Flavored Mardown Spec](https://github.com/gfm/)
[^2]: [GFM-Tasks Lists](https://facelessuser.github.io/pymdown-extensions/extensions/tasklist/#tasklist) 
[^3]: [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)
