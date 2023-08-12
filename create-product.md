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
