# Sublime Text 2 Drupal 7 snippets. #

Install the snippets by copying them into your [User package folder](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-user-package). Sublime Text 2 will pick up the snippets without restart.

Feel free to contribute!

## Snippet shortcuts ##

### Drupal hooks ###
* Basic hook: h + *first letters of the hook name*
* Full hook:  h + *first letters of the hook name* + f
* Full + comment hook : h + *first letters of the hook name* + f + i

#### Examples ####
* **ht** => hook_theme basic implementation
* **hmfi** => hook_menu with all attributes available + comments
* **hapa** => hook_admin_paths_alter basic implementation

### Full Overview ###
* **hapa** => hook_admin_paths_alter
* **hfa** => hook_form_alter
* **hf** => hook_form
* **hm** => hook_menu
* **hma** => hook_menu_alter
* **hni** => hook_node_insert
* **hnp** => hook_node_presave
* **ht** => hook_theme
* **hff** => hook_field_formatter_info

#### Extra ####

* **hmi** => hook_menu item
* **hti** => hook_theme item
* **tokens** => hook_token_info + hook_tokens implementation + comments
* **mail** => hook_mail + implementation comment
* **hmf** => hook_menu with all atributes available
* **hmfi** => hook_menu with all atributes available + comments
* **declare** => opening php tag with a comment heading
* **info** => full implementation for your module.info file
