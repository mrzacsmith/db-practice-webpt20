# DB Practice

## Usage

### libraries

- more
  - one
  - two
- less

```javascript
const formatMoney = (number, currency) => {
  return new Intl.NumberFormat('en-US', {
    style: 'currency',
    currency,
  }).format(number)
}

console.log(`The amount is ${formatMoney(5842.2, 'USD')}`)
console.log(`The amount is ${formatMoney(5842.2, 'EUR')}`)
console.log(`The amount is ${formatMoney(5842.2, 'JPY')}`)

// The amount is $5,842.20
// The amount is €5,842.20
// The amount is ¥5,842
```

POST /api/cars

`https:sdlksjfljsdflsd`

```javascript
{
  "email": "bob@bob.com",
  "pass": "123232"
}

```

| VERB        | Auth  |                          Returns | happy |
| :---------- | :---: | -------------------------------: | :---- |
| POSTTTTTTTT | False | all cars!!! !!!!!!!!!!!!!!!!!!!! | No    |
