# react-typescript-test-01

Is a test deployment package on NPM

## AJ Rivera

### Example

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'do-product-card';

```

```
    <ProductCard 
    product={ product }
    initialValues={{
        count: 6,
        // maxCount: 10,
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy  }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>

```
