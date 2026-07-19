# Database Structure

## users
- id
- name
- phone
- email
- password
- type (customer / trader / admin)
- created_at

## stores
- id
- owner_id
- store_name
- address
- phone
- logo
- rating

## categories
- id
- name
- image

## brands
- id
- name
- logo

## car_models
- id
- brand_id
- model
- year

## products
- id
- store_id
- category_id
- brand_id
- car_model_id
- title
- description
- price
- quantity
- image

## orders
- id
- user_id
- total
- payment
- status

## order_items
- id
- order_id
- product_id
- quantity
- price

## favorites
- id
- user_id
- product_id

## notifications
- id
- user_id
- title
- body