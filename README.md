# Welcome to PackageMaven

The goal is simple: to give Magento users an easy way to find modules that can enhance their e-commerce platforms. Beyond just listing these modules, we also run basic tests to check if they can be installed without issues.

## What's This All About?

The heart of this repository is a JSON file that acts as a data source for the [PackageMaven](https://package-maven.com) website. This website showcases a catalog of Magento modules, making it easy for users to discover tools that can help expand the functionality of their Magento stores.

## The List Explained

Each module is represented by a key-value pair, where the key is the module's Packagist name and the value is an object with the following properties:

```json
{
    "vendor/module-name": {
        "name": "Friendly Name of the Module",
        "description": "A short explanation of what the module does.",
        "packagist_source": "vendor/module-name"
    }
}
```

This format helps our website share details about each module, like what it does and where to find it.

## How to Add Your Module

If you have a Magento module that you would like to include in our list, please follow these steps:

1. **Fork this repository**: Create your own copy of the project to work on.
2. **Add your module to the list**: Edit the JSON file using the format described above. Please ensure you include:
   - The full Packagist name of your module.
   - A concise and descriptive name along with a brief explanation of its functionality.
   - The `"packagist_source"` field exactly as it appears on [Packagist](https://packagist.org/).
3. **Submit a pull request**: Once your changes are ready, submit a pull request for review.

## Data Source

Our initial set of modules was inspired by the open-source resources shared by [MageRes](https://github.com/aleron75/mageres), a fantastic community hub for Magento developers.