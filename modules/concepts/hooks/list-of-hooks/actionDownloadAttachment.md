---
Title: actionDownloadAttachment
hidden: true
hookTitle: 
files:
    -
        url: 'https://github.com/PrestaShop/PrestaShop/blob/8.0.x/controllers/front/AttachmentController.php'
        file: controllers/front/AttachmentController.php
locations:
    - 'front office'
type: action
hookAliases: 
array_return: false
check_exceptions: false
chain: false
origin: core
description: ''

---

{{% hookDescriptor %}}

## Call of the Hook in the origin file

```php
Hook::exec('actionDownloadAttachment', ['attachment' => &$attachment])
```