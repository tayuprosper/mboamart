# Info on models.
## Note: these are the structures for the following entities
### Vendor:
```python
class Vendor():
    vendor_name: [str]
    phone_number: [str]
    email_address: [str]
    username: [str]
    password: [str]
#     product_type: str["Tech & Electronics", "Fashion & Lifestyle", "Food & Groceries", "Home & Essentials", "Books & Learning", "Health & Fitness", "Kids & Baby", "Tools & Auto", "Arts & Entertainment"
# ]  # product type must be one of these
    # data_reg: datetime   #do not include on form auto generated by server

    # request goes to /create_vendor
```
### Customer
```python
class Customer():
     customer_name: [str]
    phone_number: [str]
    email_address: [str]
    username: [str]

    # request goes to /create_customer
```

- These are the field needed when created customer of vendo

### Creating product:
```python
class Product():
    product_name: [str]
    p_description: [str]
    price: [int]
    img_link: [str]
# request goes to /create_product

```

### Note: please keep nameing of input fields consistent with the above