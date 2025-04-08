# ZR Embeddable View Paragraph Installation Guide

To install the ZR Embeddable View Paragraph, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Ahead of running `composer require zr/RECIPE_NAME` - ensure the below has been added to the root `composer.json` **installer-paths**
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to set the minimum stability for composer to dev
    ```sh
	composer config minimum-stability dev
    ```
5. Run the following command to execute the ZR Embeddable View Paragraph installation:

    ```sh
    ddev drush recipe recipes/custom/zr-para-embedded-view
    ```

This command will execute the ZR Embeddable View Paragraph installation.
