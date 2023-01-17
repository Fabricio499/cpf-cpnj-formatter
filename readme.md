# CPF and CNPJ formatter 📦

## how to install ?
```bash
npm install cpf-cpnj-formatter
```
```bash
yarn add cpf-cpnj-formatter
```


## usage
```js
import { mask } from 'cpf-cpnj-formatter'
```

```js
// CPF
mask(21490841040) //~> 214.908.410-40
mask('78734612033') //~> 787.346.120-33

// CNPJ
mask(12738586000175) //~> 12.738.586/0001-75
mask('32957821000107') //~> 32.957.821/0001-07
``` 
<hr>
