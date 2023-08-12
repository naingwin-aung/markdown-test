# Create Product

Create a new product

![API Method](https://img.shields.io/badge/Method-POST-brightgreen.svg)

#### API Endpoint

```
/products
```

#### Headers

```
headers {

  Authorization : 'Bearer ' + SECRET_KEY

}
```

#### Body `form-data`

| Key  | Type   | Description | Require |
| :--- | :----- | :---------- | :------ |
| name | string |             | Yes     |

#### Example Request `form-data`

```json
{
  "name": "iPhone 13 Pro Max"
}
```

#### Responses

```json
{
  "code": 200,
  "success": true,
  "message": "",
  "data": {
    "name": "ABC"
  }
}
```

# Update Product

Edit & Update a Product

![API Method](https://img.shields.io/badge/Method-POST-brightgreen.svg)

#### API Endpoint

```
/products/{product_id}
```

example : `/products/3`

#### Headers

```
headers {
  Authorization : 'Bearer ' + SECRET_KEY
}
```

#### Query Params

| Key      | Value | Require |
| :------- | :---- | :------ |
| \_method | PUT   | Yes     |

#### Body `form-data`

| Key  | Type   | Description          | Require |
| :--- | :----- | :------------------- | :------ |
| name | string | Name of the category | Yes     |

#### Responses

```json
{
  "code": 200,
  "success": true,
  "message": "",
  "data": {
    "name": "Oppo"
  }
}
```
