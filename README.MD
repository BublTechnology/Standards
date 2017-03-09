# Standards

This repo holds the code style configurations for multiple tools

## JS
Our standards are an evolution of multiple sources and should be [StanardJS](http://standardjs.com/index.html) compliant.
They are currently entirely based on [ESLint](http://eslint.org/) and live in their own [repo](https://github.com/BublTechnology/eslint-config-bubl).

## Ruby

### Rubocop
To use this with rubocop make sure you need an `inherit_from` statement pointing to this yml.

Below you can see the standards combined with a todo (generated from rubocop --auto-gen-config)
```
inherit_from:
    - .rubocop_todo.yml
    - Standards/ruby/.rubocop.yml
```

