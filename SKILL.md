# Canonical JavaFX migration

Use the maintained [javafx API](https://github.com/normlanguage/javafx) for JavaFX integrations. Replace imports from the historical package with the matching `javafx` types and functions. Observable collections inherit the canonical `java.base` collection API.

The runnable contract is [samples/migration/main.norm](samples/migration/main.norm); its toolchain and dependency are owned by [the workflow](.github/workflows/package.yml) and [the sample module](samples/migration/module.norm).
