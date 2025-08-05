# 🔍 Teste Exploratório – Site Kabum

**Desenvolvido por:** Erick Oliveira  
**Data:** 04/08/2025
**Contexto:**  
Este teste exploratório foi realizado como parte do curso prático de QA, com o objetivo de avaliar funcionalidades, usabilidade e respostas do sistema no site [Kabum](https://www.kabum.com.br).

## 🎯 Cenário:

O usuário acessa a página de login e realiza uma busca por produtos. O objetivo é identificar comportamentos esperados, falhas ou oportunidades de melhoria, **sem um roteiro pré-definido**.

---

## ✅ Observações levantadas:

1. **Campo de CPF (login):** Ao tentar digitar um espaço, o sistema não aceita e move automaticamente o cursor para o final do campo.  
   🔎 *Comportamento de validação funcional correto.*

2. **Tecla Enter funciona para login:** Após preencher CPF e senha, é possível pressionar Enter e efetuar o login normalmente.  
   🔎 *Boa usabilidade.*

3. **Erro de senha inválida:** O sistema exibe uma mensagem clara e destacada em vermelho:  
   `"E-mail, CPF/CNPJ ou senha incorretos."`  
   🔎 *Ótimo feedback para o usuário.*

4. **Campos persistem após recarregar:** Ao atualizar a página, os campos de login permanecem preenchidos.  
   🔎 *Boa experiência do usuário.*

5. **Pesquisa com erro de digitação:** Ao procurar por “Poaba Mãe” (erro de digitação de “Placa Mãe”), o site exibe:  
   `"Lamentamos, nenhum produto encontrado com esse critério de pesquisa."`  
   🔎 *Resposta adequada, mas poderia haver sugestões de correção automática.*

---

## 📝 Conclusão:

O sistema apresentou comportamento estável e respostas adequadas às interações testadas. Houve validações bem implementadas, mensagens claras e boa usabilidade.  
Sugestão de melhoria: implementar correção automática ou sugestões na barra de busca em caso de digitação incorreta.
