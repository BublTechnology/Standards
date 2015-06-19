# Standards

This repo holds the code style configurations for multiple tools

## Ruby

### Rubocop
To use this with rubocop make sure you need an `inherit_from` statement pointing to this yml.

Below you can see the standards combined with a todo (generated from rubocop --auto-gen-config)
```
inherit_from:
    - .rubocop_todo.yml
    - Standards/ruby/.rubocop.yml
```

