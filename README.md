# Product Card Component

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Este paquete contiene Componente De Prueba para el proyecto de Shopping

By Seba Morgado

## Ejemplo
    ```
    import { ProductCard,ProductImage,ProductButtons ,ProductTitle } from 'sm-product-card';
    
    ```

  ```
   <ProductCard 
                product={ product }
                initialValues = {{
                    count: 4,
                    // maxCount: 10,
                }}
            >
                {
                    ({reset,isMaxCountReached,increaseByOne,maxCount,count}) => (
                        <>
                            <ProductImage  />
                            <ProductTitle />
                            <ProductButtons />
                        </>
                    )
                }
 
            </ProductCard>
  ``` 