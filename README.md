# Netgen Layouts Recipes

This repo holds all Symfony Flex recipes which can't be put into the official `symfony/recipes-contrib` repo
either because of incompatible license (e.g. GPL packages like Layouts & Ibexa integration), or due to being
closed source (e.g. Layouts Enterprise).

## Configure access to recipes

Update your `composer.json` file with Flex endpoint:

```json
{
    "extra": {
        "symfony": {
            "endpoint": [
                "https://api.github.com/repos/netgen-layouts/recipes/contents/index.json?ref=flex",
                "flex://defaults"
            ]
        }
    }
}
```
