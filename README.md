# Comparação entre XmlHttpRequest, Fetch API, Promises e Async/Await

Este repositório contém uma pesquisa e exemplos de código demonstrando diferentes formas de realizar requisições AJAX com JavaScript moderno.

## 📘 Pesquisa Comparativa

| Tecnologia         | Lançamento     | Sintaxe           | Suporte Promises | Facilidade de uso | Controle de erros  | Popularidade Atual |
|--------------------|----------------|-------------------|------------------|-------------------|--------------------|---------------------|
| **XmlHttpRequest** | 2000s          | Verbosa           | ❌ Não nativo     | Difícil            | Requer callbacks   | Baixa               |
| **Fetch API**      | 2015+ (ES6)     | Moderna           | ✅ Sim           | Simples            | Usa `.then()`/`.catch()` | Alta          |
| **Promises**       | 2015 (ES6)     | Base para Fetch   | ✅ Sim           | Clara e encadeada  | `.then().catch()`  | Alta                |
| **Async/Await**    | 2017+ (ES8)     | Muito limpa       | ✅ Sim           | Muito simples      | Usa `try/catch`    | Muito Alta          |

## 📂 Códigos

Veja os arquivos:

- `ajax3-fetch.html`
- `ajax3-promises.html`
- `ajax3-async-await.html`
- `dados.txt`

## 📊 Comparação de Desempenho e Facilidade

| Método              | Desempenho | Facilidade | Legibilidade | Uso Recomendado |
|---------------------|------------|------------|--------------|-----------------|
| `XmlHttpRequest`    | Médio      | Difícil     | Baixa        | Manutenção de legado |
| `fetch`             | Alto       | Média       | Boa          | Projetos modernos simples |
| `Promises + XHR`    | Médio      | Média       | Média        | Estudo de Promise |
| `async/await`       | Alto       | Muito fácil | Excelente    | Requisições modernas |

## 🔗 Link para entrega

📎 Acesse este repositório no GitHub:  
👉 (https://github.com/LuisBSB23/ajax-comparativo)

