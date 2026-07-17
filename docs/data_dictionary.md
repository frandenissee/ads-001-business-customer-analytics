# Diccionario de Datos

## Descripción General

El proyecto utiliza el **Brazilian E-commerce Public Dataset by Olist**, un conjunto de datos públicos que contiene información sobre pedidos realizados entre 2016 y 2018 en una plataforma de comercio electrónico brasileña.

La información se encuentra distribuida en múltiples tablas relacionadas mediante identificadores únicos.

# Tablas del Dataset

## 1. customers

Información de los clientes.

| Campo | Descripción |
|--------|-------------|
| customer_id | Identificador único del cliente en un pedido. |
| customer_unique_id | Identificador único del cliente. Permite identificar clientes recurrentes. |
| customer_zip_code_prefix | Prefijo del código postal. |
| customer_city | Ciudad del cliente. |
| customer_state | Estado del cliente. |

## 2. orders

Información de los pedidos.

| Campo | Descripción |
|--------|-------------|
| order_id | Identificador del pedido. |
| customer_id | Cliente asociado al pedido. |
| order_status | Estado del pedido. |
| order_purchase_timestamp | Fecha y hora de compra. |
| order_approved_at | Fecha de aprobación del pago. |
| order_delivered_carrier_date | Fecha de entrega al transportista. |
| order_delivered_customer_date | Fecha de entrega al cliente. |
| order_estimated_delivery_date | Fecha estimada de entrega. |

## 3. order_items

Productos incluidos en cada pedido.

| Campo | Descripción |
|--------|-------------|
| order_id | Pedido. |
| order_item_id | Número de ítem dentro del pedido. |
| product_id | Producto vendido. |
| seller_id | Vendedor. |
| shipping_limit_date | Fecha límite de envío. |
| price | Precio del producto. |
| freight_value | Costo de envío. |

## 4. products

Información de los productos.

| Campo | Descripción |
|--------|-------------|
| product_id | Identificador único del producto. |
| product_category_name | Categoría del producto. |
| product_name_length | Cantidad de caracteres del nombre del producto. |
| product_description_length | Cantidad de caracteres de la descripción del producto. |
| product_photos_qty | Cantidad de fotos del producto. |
| product_weight_g | Peso (gramos) del producto. |
| product_length_cm | Largo (cm) del producto. |
| product_height_cm | Alto (cm) del producto. |
| product_width_cm | Ancho (cm) del producto. |

## 5. payments

Información de los pagos.

| Campo | Descripción |
|--------|-------------|
| order_id | Identificador del pedido asociado al pago. |
| payment_sequential | Número secuencial del pago dentro del mismo pedido. Un pedido puede tener más de un pago. |
| payment_type | Método de pago. |
| payment_installments | Número de cuotas. |
| payment_value | Monto pagado en la transacción. |

## 6. reviews

Reseñas realizadas por los clientes.

| Campo | Descripción |
|--------|-------------|
| review_id | Identificador único de la reseña. |
| order_id | Identificador del pedido evaluado. |
| review_score | PCalificación otorgada por el cliente, en una escala de 1 a 5. |
| review_comment_title | Título de la reseña (opcional). |
| review_comment_message | Comentario escrito por el cliente (opcional). |
| review_creation_date | Fecha en que se creó la reseña. |
| review_answer_timestamp | Fecha y hora en que la reseña fue registrada en el sistema. |

## 7. sellers

Información de los vendedores.

| Campo | Descripción |
|--------|-------------|
| seller_id | Identificador único del vendedor. |
| seller_zip_code_prefix | Prefijo del código postal del vendedor. |
| seller_city | Ciudad donde se ubica el vendedor. |
| seller_state | Estado donde se ubica el vendedor. |

## 8. geolocation

Información geográfica asociada a códigos postales.

| Campo | Descripción |
|--------|-------------|
| geolocation_zip_code_prefix | Prefijo del código postal. |
| geolocation_lat | Latitud correspondiente al código postal. |
| geolocation_lng | Longitud correspondiente al código postal. |
| geolocation_city | Ciudad asociada al código postal. |
| geolocation_state | Estado asociado al código postal. |