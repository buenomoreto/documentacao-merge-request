### **Qual o tipo de alteração essa PR produz?**
 - [x] 🐛Bug
 - [x] 🚀Feat
 - [x] 💅 Style
 - [x] 📝 Refactor
 - [x] 🚧 Build & Deploy
 - [x] Chore (console.log, versionamento de componentes e modelos, eslint, gitignore, mudança de dominio) - [x] Other... Descreva: 

### **Envolve mudança de versão ou adição de algum pacote? Quais?**
-----
Atualizados: 
- @wapstore/carrinho-lateral: responsável por abstrair o recurso de excluir e alterar a quantidade de produto no carrinho. **v1.0.4 -> v1.0.5** 
- @wapstore/estados-produto: responsável por adicionar produto ao carrinho e lidar com os estados disponivel/sobconsulta/indisponivel **v0.0.9 -> v1.0.1** 

### **Qual é o comportamento atual?**
-----
Quando adicionado um produto no carrinho lateral ou quando é retirado não é emitido os respectivos eventos GTM "addToCart", "removeFromCart". 

### **Qual é o novo comportamento?**
-----
**Quando adicionado um produto no carrinho lateral é emitido o evento GTM "addToCart" e quando é removido é emitido o evento GTM "removeFromCart".** 

### **Este PR introduz uma mudança significativa?**
-----
Não, apenas atualiza a versão dos pacotes @wapstore/carrinho-lateral e @wapstore/estados-produto. 

### **Outra informação**
-----
Tarefa: N/A 
Issue da solicitação: N/A 

Terminologias merges
====================

### **"update":** 
- usado quando você atualiza ou modifica algo existente, como uma biblioteca ou um arquivo de configuração.  
-----
### **"refactor":** 
- usado quando você faz alterações no código para melhorar sua estrutura ou desempenho, sem alterar seu comportamento.  
-----
### **"remove":** 
- usado quando você remove algo, como um arquivo ou um trecho de código.  
-----
### **"merge":** 
- usado quando você mescla duas ou mais branches do Git. 
-----
### **"revert":**
- usado quando você reverte uma alteração anterior.  
-----
### **"test":** 
- usado quando você adiciona ou atualiza testes de unidade ou integração.  
-----
### **"docs":**
- usado quando você adiciona ou atualiza documentação.  
-----
### **"style":** 
- usado quando você faz alterações de formatação ou estilo, como espaçamento ou indentação.
-----
### **"Padrão de commit":** 
- [Feat][user-auth]: Adiciona autenticação de usuário 
- Prefixo, Escopo, Descrição

