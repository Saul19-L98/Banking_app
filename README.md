# Banking app

Banking is an app that allow payments between users.

## Usage

```python
#Only 4 users available

# User: js | password: 1111
const account1 = {
    owner: 'Jonas Schmedtmann',
    movements: [200, 450, -400, 3000, -650, -130, 70, 1300],
    interestRate: 1.2, // %
    pin: 1111,
    movementsDates: [
        '2020-11-18T21:31:17.178Z',
        '2020-12-23T07:42:02.383Z',
        '2021-01-28T09:15:04.904Z',
        '2021-04-01T10:17:24.185Z',
        '2021-05-08T14:11:59.604Z',
        '2021-05-27T17:01:17.194Z',
        '2021-07-11T23:36:17.929Z',
        '2021-07-12T10:51:36.790Z',
    ],
    currency: 'EUR',
    locale: 'pt-PT', // de-DE
};

# User: jd | password: 2222
const account2 = {
    owner: 'Jessica Davis',
    movements: [5000, 3400, -150, -790, -3210, -1000, 8500, -30],
    interestRate: 1.5,
    pin: 2222,
    movementsDates: [
        '2020-11-01T13:15:33.035Z',
        '2020-11-30T09:48:16.867Z',
        '2020-12-25T06:04:23.907Z',
        '2021-01-25T14:18:46.235Z',
        '2021-02-05T16:33:06.386Z',
        '2021-04-10T14:43:26.374Z',
        '2021-06-25T18:49:59.371Z',
        '2021-07-26T12:01:20.894Z',
    ],
    currency: 'USD',
    locale: 'en-US',
};

# User: stw | password: 3333
const account3 = {
    owner: 'Steven Thomas Williams',
    movements: [200, -200, 340, -300, -20, 50, 400, -460],
    interestRate: 0.7,
    pin: 3333,
    movementsDates: [
        '2021-01-01T13:15:33.035Z',
        '2021-02-30T09:48:16.867Z',
        '2021-03-25T06:04:23.907Z',
        '2021-04-25T14:18:46.235Z',
        '2021-06-05T16:33:06.386Z',
        '2021-07-10T14:43:26.374Z',
        '2021-07-25T18:49:59.371Z',
        '2021-07-26T19:01:20.894Z',
    ],
    currency: 'EGP',
    locale: 'ar-EG',
};

# User: ss | password: 4444
const account4 = {
    owner: 'Sarah Smith',
    movements: [430, 1000, 700, 50, 90],
    interestRate: 1,
    pin: 4444,
    movementsDates: [
        '2021-06-01T13:15:33.035Z',
        '2021-06-30T09:48:16.867Z',
        '2021-02-25T06:04:23.907Z',
        '2021-03-25T14:18:46.235Z',
        '2021-07-05T16:33:06.386Z',
        '2021-07-10T14:43:26.374Z',
        '2021-07-25T18:49:59.371Z',
        '2021-07-26T12:01:20.894Z',
    ],
    currency: 'BRL',
    locale: 'pt-br',
};
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
