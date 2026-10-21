# Dataset

This project uses the **Brazilian E-Commerce Public Dataset by Olist** (about 100K orders placed between 2016 and 2018), published on Kaggle:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset is released by Olist under the CC BY-NC-SA 4.0 licence. All credit for the data goes to Olist.

## What is stored in this folder

| File | Description |
|---|---|
| `olist_sellers_dataset.csv` | Seller IDs, ZIP code prefix, city and state |
| `product_category_name_translation.csv` | Product category names in Portuguese and English |
| `olist_geolocation_dataset.rar` | Compressed geolocation file (ZIP code prefix to latitude and longitude) |

The larger files (orders, order items, customers, products, payments and reviews) are not stored in this repository because of their size. Download them from the Kaggle page above and place them in this folder to reproduce the staging step.

## The 9 source files

1. `olist_orders_dataset.csv`
2. `olist_order_items_dataset.csv`
3. `olist_order_payments_dataset.csv`
4. `olist_order_reviews_dataset.csv`
5. `olist_customers_dataset.csv`
6. `olist_sellers_dataset.csv`
7. `olist_products_dataset.csv`
8. `olist_geolocation_dataset.csv`
9. `product_category_name_translation.csv`
