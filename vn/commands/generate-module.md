# generate:module
Tạo một module.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | Tên Module
--machine-name | Tên máy (chỉ chữ thường và gạch dưới)
--module-path | Đường dẫn của module
--description | Mô tả module
--core | Phiên bản Core
--package | Module package
--module-file | Add a .module file
--features-bundle | Define module as feature using the given Features bundle name
--composer | Thêm một file composer.json
--dependencies | Sự phụ thuộc của module chia ra bởi dấu phẩy (ví dụ context, panels)
--test | Tạo một test class
--twigtemplate | Generate theme template

## Examples
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
