# PAQUETE DE PRUEBA NICOLAS

### PAQUETES CUSTOM DE REACT

## EJEMPLO

```
import {ProductCard,ProductImage,ProductTitle,ProductButtons} from 'nm-product-card';
```

```
<ProductCard
          key={product.id}
          product={product}
          initialValues={{
            count: 4,
            // maxCount: 10,
          }}
  >
  {({ reset, count, increaseBy, isMaxCountReached }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```
