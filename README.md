# metodos
const express = require('express') //aqui estamos fazendo a importação da biblioteca
const app = express() //criando uma instância para a constante app

app.get('/', (req, res) => {
    const result = { name: 'ana', instagram: 'anajose' };
    return res.json(result);
  });

app.listen(8080,() =>{
    console.log("Servidor funcionando ") //o que aparece no terminal
})
