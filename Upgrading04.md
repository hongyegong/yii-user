
```
ALTER TABLE `tbl_profiles_fields`
ADD `widget` VARCHAR(255) NOT NULL DEFAULT '' AFTER `default` ,
ADD `widgetparams` VARCHAR(5000) NOT NULL DEFAULT '' AFTER `widget` 
```