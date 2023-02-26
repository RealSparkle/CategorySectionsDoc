# CustomCategorySection

<!--ts-->
   * [Description](#Description)
   * [Requirement](#Requirement)
   * [Installation](#Installation)
   * [Usage](#Usage)
<!--te-->

## Description

This plugin allows users to add custom section buttons inside Actors, based on their class and their property categories. These buttons allow to quickly filter actors properties.

> __Note__
> **THE PLUGIN SUPPORTS CATEGORIES CREATED BOTH FROM CODE AND FROM BLUEPRINT**

![DetailsSection](https://user-images.githubusercontent.com/122740591/221410561-7b7633be-ca86-4052-8a68-5dcddbbb7aa8.png)

## Requirement

Target version : UE5.0 ～ 5.1  
Target platform : Windows (Not tested on Mac or Linux , but should work fine)

## Installation

Install from the [Marketplace](com.epicgames.launcher://ue/marketplace/product/3daf1f4957fe4a13a4b9601554453db7).  
If the feature is not available after installing the plugin, it is possible that the plugin has not been enabled, so please check if the plugin is enabled from Edit > Plugins.

![Plugin](https://user-images.githubusercontent.com/122740591/221409848-b9bc0fe2-f981-47b1-8dd1-0641bd98ea11.png)

## Usage

Go inside ProjectSettings > Plugins > CustomCategorySection

![Settings](https://user-images.githubusercontent.com/122740591/221409859-604c6382-b957-45bd-b90a-1ef8c309fba5.png)

Add an element to the array property and select the Class you want to add custom sections for.

![ClassSelection](https://user-images.githubusercontent.com/122740591/221409975-815c4c9b-61e6-44bb-8994-aaed82d5b6b5.png)

When the class is selected a list will appear. Each checkbox represents a category that can be added.
Select all the desidered categories and restart the editor.

![CategoryList](https://user-images.githubusercontent.com/122740591/221410009-14f7ec4b-82f8-4396-80d3-bbfed5b6d130.png)

After restart is completed you will see the selected category appear in the details panel when the right class object is selected in the outliner.

![CategoryListExample](https://user-images.githubusercontent.com/122740591/221410031-be4f4ad1-6ada-4da8-844b-beb64548799c.png)
![CateogryButtonExample](https://user-images.githubusercontent.com/122740591/221410077-55816a07-e0f7-4e94-b9c2-64c78d3958fc.png)

