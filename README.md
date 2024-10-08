[# magento2-product-attributes](https://magento.stackexchange.com/questions/117694/find-the-table-for-custom-attribute-values)

```php
$product = $this->productRepository->get('q783');
$product->setData('description','hello world');
$this->productRepository->save($product);
```
