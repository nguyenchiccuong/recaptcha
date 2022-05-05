# recaptcha

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Issue about using ref in class style components type script
https://github.com/vuejs/vue-class-component/issues/94

dependency link
https://www.npmjs.com/package/vue-recaptcha#bind-challenge-to-button

captcha is in about page
http://localhost:8080/#/about

verify
curl --location --request POST 'https://www.google.com/recaptcha/api/siteverify?secret=6LeQu8cfAAAAALpDiYQUGFsI5kw6WeNgm2PtZiRV&response=03AGdBq25xfpZER2Tgv7MQ0cl7lJ9FR31h-hSR-Gpi4eRUOzWsv4HQHNUCR55Pbgjk_4pb9t-MlG_vKLqPtJ58nYit3Ag4KmNOG6U_M-L8y8DdSpvRdBV8HbPhe0HImENwPV3Sz02YdATigW4rP2n_NpvR_nDD1R9btoFtcQNvrKkEpdXlHcZW1giSuOEZczlMAvjC2ihacJ9IGO2s-vooGn5sO6ocfx_AFdZZgxJ_NO1-3Bm9UhzXj4aZsXZQPIh1WRTjuM4YCCjcSaEAXpfozQRApInW9DRBBogpofRI-x6KnIxJtvYNerFuqm6ZwHPhpQBbltmfrJefJkXLRR0w6FEC8F-8sKOEjG1iIeq48TgLRQWUfSPkaW7VG4AW_NJ7f51oPuhjAaj1AZ8Jzjsr-CI8T9WPlNGMprf7Vt8ix1Zvo7K-CZsnR-b9B1YXPxziVqSrC6SG49TSIY0bhuQLkJBCloQmvZ7axRMDNB8FONifLGz-nv4-b5h_kb4DeQf8L8xjMOerUnaB'