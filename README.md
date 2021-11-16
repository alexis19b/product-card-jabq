# Product-Card-jabq

Este es un paquete de pruebas de despliegue en NPM

### Jesus Briceño

## Ejemplo

```
import {ProductImage, ProductTitle, ProductButtons, ProductCard} from 'product-card-jabq'

```

```
<ProductCard
    product={product}
    initialValues={{
    count:4,

    }} 
  >
  {
  ( { reset, count, increaseBy, isMaxCountReached })=>(
  <>
    <ProductImage />
    <ProductTitle  />
    <ProductButtons />
  />
  )
  }
</ProductCard>
```
