[# magento2-product-attributes](https://magento.stackexchange.com/questions/117694/find-the-table-for-custom-attribute-values)
https://stackoverflow.com/questions/5291572/in-magento-is-there-a-way-to-remove-attribute-from-configurable-product-after-a


```php
$product = $this->productRepository->get('q783');
$product->setData('description','hello world');
$this->productRepository->save($product);
```
