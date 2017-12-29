# magento2.admin_theme
Custom Magento 2 Admin Theme

1. app/design/adminhtml/Wm21w/light/theme.xml

`<theme xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="urn:magento:framework:Config/etc/theme.xsd">
     <title>Wm21w Light Theme</title> <!-- your theme's name -->
     <parent>Magento/backend</parent> <!-- the parent theme. Example: Magento/backend -->
 </theme>
 `

2. app/design/adminhtml/Wm21w/light/registration.php

`<?php
 \Magento\Framework\Component\ComponentRegistrar::register(
     \Magento\Framework\Component\ComponentRegistrar::THEME,
     'adminhtml/Wm21w/light',
     __DIR__
 );`
 
 3. app/design/adminhtml/Wm21w/light/web/images/21-logo.svg