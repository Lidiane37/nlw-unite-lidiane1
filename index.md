# HTML
*Linguagem de marcação de Hipertesto*
*tags*
*div- agrupa outras tags*

# Javascript
```Javascript

//variáveis
const mensagem 'Oi tudo bem?'
//tipos de dados
//number
//funcao
//string
alert(mensagem)
//Se eu recortar uma tag html no html como por exemplo uma tabela e colar dentro ``aspas o teremos uma função que executa esta tabela
//arrow functio
const criarNovoParticipante = ()=>{
  return `
  <tr>
      <td>
        <strong> Diego Fernandes</strong><br>
        <small>diego.gmail.com
        </td>
      <td>há 3 dias</td>
      <td>há 3 minutos</td>
    </tr>`
  
}
const atualizarLista =()=>{
// pegar informação do html
//substituir informação do html
document.querySelector('tbody')
.innerHTML=criarNovoParticipante()
}

atualizarLista()

//estudar depois
//objeto
//objeto
const participante={
  nome: "Marck Brito",
  email:"marck@gmail.com,",
  DataInscricao:new Date(2024,2, 22,22,19,20),
  dataCheck: new Date(2024,2,25,22,00),


}
//array
let participate =[
  {
  nome: "Marck Brito",
  email:"marck@gmail.com,",
  DataInscricao:new Date(2024,2, 22,22,19,20),
  dataCheck: new Date(2024,2,25,22,00),
}
]


}
//array
let participate =[
  {
  nome: "Marck Brito",
  email:"marck@gmail.com,",
  DataInscricao:new Date(2024,2, 22,22,19,20),
  dataCheck: new Date(2024,2,25,22,00),
}
]