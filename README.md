# CustomCategorySection

![Plugin](https://user-images.githubusercontent.com/122740591/221409848-b9bc0fe2-f981-47b1-8dd1-0641bd98ea11.png)

<!--ts-->
   * [Description](#Description)
   * [Requirement](#Requirement)
   * [Installation](#Installation)
   * [Usage](#Usage)
<!--te-->

## Description

This plugin adds a menu to the file menu to open recently opened assets as well as level assets.

## Requirement

Target version : UE5.0 ～ 5.1  
Target platform : Windows (Doesn't tested on Mac or Linux , but should works fine)

## Installation

Install from the INSERTLINK.  
If the feature is not available after installing the plugin, it is possible that the plugin has not been enabled, so please check if the plugin is enabled from Edit > Plugins.

## Usage

Go inside ProjectSettings > Plugins > CustomCategorySection

![Settings](https://user-images.githubusercontent.com/122740591/221409859-604c6382-b957-45bd-b90a-1ef8c309fba5.png)

Add an element to the arry property and select the Class you want to add custom sections.

![ClassSelection](https://user-images.githubusercontent.com/122740591/221409975-815c4c9b-61e6-44bb-8994-aaed82d5b6b5.png)

When class is selected a list of checkbox appear. Each checkbox represent a category that can be added.
Select all the desidered categories and restart the editor.

![CategoryList](https://user-images.githubusercontent.com/122740591/221410009-14f7ec4b-82f8-4396-80d3-bbfed5b6d130.png)

After restart is completed you will see the selected category appear in the details panel when the right class object is selected in the outliner.

![CategoryListExample](https://user-images.githubusercontent.com/122740591/221410031-be4f4ad1-6ada-4da8-844b-beb64548799c.png)
![CateogryButtonExample](https://user-images.githubusercontent.com/122740591/221410077-55816a07-e0f7-4e94-b9c2-64c78d3958fc.png)

