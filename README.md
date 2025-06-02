# GUIA DE EXECUÇÃO MANUAL - TESTES JFROG
## Caderno de Testes Completo - 41 Casos de Teste

---

## INFORMAÇÕES GERAIS

**Software:** JFrog Artifactory  
**Total de Casos de Teste:** 41  
**Categorias:** 7  
**Data de Criação do Guia:** Junho 2025  

---

## INSTRUÇÕES GERAIS DE EXECUÇÃO

### Pré-requisitos Globais
1. **Acesso ao JFrog Artifactory** com permissões administrativas
2. **Navegador web** atualizado (Chrome, Firefox, Edge)
3. **Conexão com internet** estável
4. **Ferramentas de linha de comando** (curl, wget) para testes de API
5. **Artefatos de teste** preparados para upload/download
6. **Usuários de teste** configurados para diferentes níveis de acesso

### Como Usar Este Guia
- Cada teste possui numeração sequencial (1-41)
- Execute os testes na ordem apresentada quando possível
- Marque o resultado como **OK** ou **Not OK** conforme critérios
- Anote observações relevantes durante a execução
- Tempo estimado é fornecido para planejamento

### Critérios de Avaliação
- **OK:** Teste passou conforme critérios estabelecidos
- **Not OK:** Teste falhou ou não atendeu aos critérios
- **N/A:** Teste não aplicável ao ambiente atual

---

## REPOSITÓRIO

### Teste 01 - 1.1.

**Categoria:** Repositório  
**Tempo Estimado:** 300 minutos  
**Avaliador:** TIC/AID/ARQTIC/ARQNUV e
TIC/OI/ADG/IDN  

#### Descrição do Teste
O produto é capaz de hospedar e gerenciar artefatos usando as seguintes tecnologias?
-apk (alpine)
-apt (debian / ubuntu);
-bower
-Conan(C++);
-Conda;
-Docker;
-GitLFS;
-Go;
-Helms
-Maven;
-npm;
-NuGet;
-OCI.
-PyPi;
-R;
-RAW;
-RubyGems;
-yum;

#### Pré-condições
As tecnologias citadas nos requitos devem estar disponíveis na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Faça login com credenciais administrativas
3. Navegue para **Administration** → **Repositories**
4. Selecione **Local**, **Remote** ou **Virtual** conforme necessário

**Ações a Realizar:**
1. O produto é capaz de hospedar e gerenciar artefatos usando as seguintes tecnologias?
-apk (alpine)
-apt (debian / ubuntu);
-bower
-Conan(C++);
-Conda;
-Docker;
-GitLFS;
-Go;
-Helms
-Maven;
-npm;
-NuGet;
-OCI.
-PyPi;
-R;
-RAW;
-RubyGems;
-yum;
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Os artefatos baixados devem estar armazenados na ferramenta e disponíveis para download.

#### Resultado Esperado
Artefatos de cada teconologia armazenados no produto

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 02 - 1.2.

**Categoria:** Repositório  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de fazer proxying e caching de repositórios externos nas tecnologias mencionadas no teste 1.1?

#### Pré-condições
Não especificadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Faça login com credenciais administrativas
3. Navegue para **Administration** → **Repositories**
4. Selecione **Local**, **Remote** ou **Virtual** conforme necessário

**Ações a Realizar:**
1. O produto é capaz de fazer proxying e caching de repositórios externos nas tecnologias mencionadas no teste 1.1?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Os artefatos baixados externamente devem estar disponíveis para download via proxy e pelo cache.

#### Resultado Esperado
Artefatos de repositórios externos disponíveis via produto

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 03 - 1.3.

**Categoria:** Repositório  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto possui políticas de manutenção, retenção e limpeza, configuráveis por idade dos artefatos, espaço em disco ocupado pelos repositórios, ou por outros critérios?

#### Pré-condições
Ter alguns artefatos baixados

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Faça login com credenciais administrativas
3. Navegue para **Administration** → **Repositories**
4. Selecione **Local**, **Remote** ou **Virtual** conforme necessário

**Ações a Realizar:**
1. O produto possui políticas de manutenção, retenção e limpeza, configuráveis por idade dos artefatos, espaço em disco ocupado pelos repositórios, ou por outros critérios?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Execução da rotina ou por agendamento ou por demanda sem falha

#### Resultado Esperado
Políticas de manutentação criadas e sua aplicação demonstradas

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 04 - 1.4.

**Categoria:** Repositório  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
É possível movimentar artefatos de um repositório para outro?

#### Pré-condições
Ter alguns artefatos baixados

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Faça login com credenciais administrativas
3. Navegue para **Administration** → **Repositories**
4. Selecione **Local**, **Remote** ou **Virtual** conforme necessário

**Ações a Realizar:**
1. É possível movimentar artefatos de um repositório para outro?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmar que os artefatos foram movimentados para o repositório de destino

#### Resultado Esperado
Artefato movimentado de um repositório para outro na ferramenta

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 05 - 1.5.

**Categoria:** Repositório  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto permite crescimento ilimitado, em quaisquer critérios, para os repositórios?

#### Pré-condições
Não especificadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Faça login com credenciais administrativas
3. Navegue para **Administration** → **Repositories**
4. Selecione **Local**, **Remote** ou **Virtual** conforme necessário

**Ações a Realizar:**
1. O produto permite crescimento ilimitado, em quaisquer critérios, para os repositórios?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
O resultado da demonstração do crescimento deve ter sido concluído com êxito

#### Resultado Esperado
Demonstração de que não restrição para crescimento da solução

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 06 - 1.6

**Categoria:** Repositório  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
Há restrição a quantidade de acessos por mês aos repositórios?

#### Pré-condições
Log ativado sobre o total de acessos na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Faça login com credenciais administrativas
3. Navegue para **Administration** → **Repositories**
4. Selecione **Local**, **Remote** ou **Virtual** conforme necessário

**Ações a Realizar:**
1. Há restrição a quantidade de acessos por mês aos repositórios?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Verificação no log que não houve restrição de acessos

#### Resultado Esperado
Demonstração de qua não há restrição de acessos

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## API

### Teste 07 - 2.1.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto possui API REST?

#### Pré-condições
API ativada

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. O produto possui API REST?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
API retornando algum json ou xml bem como executando alguma ação no servidor sem necessidade de acesso ao site para fazê-lo

#### Resultado Esperado
Demonstração de uso da API RESTful

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 08 - 2.2.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A API possui documentação disponível e acessível para todos os potenciais usuários?

#### Pré-condições
Documentação disponível da API

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. A API possui documentação disponível e acessível para todos os potenciais usuários?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmar que a documentação encontra-se disponível para os potenciais usuários

#### Resultado Esperado
Apresentação da documentação

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 09 - 2.3.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto disponibiliza APIs que viabilize a construção de automações para execução das políticas mencionadas no requisito F-1.3?

#### Pré-condições
Exemplos de código disponíveis

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. O produto disponibiliza APIs que viabilize a construção de automações para execução das políticas mencionadas no requisito F-1.3?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Execução de chamadas na API e obtenção de respostas que sejam possíveis de confirmação.

#### Resultado Esperado
Demonstração de uso da API RESTful

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 10 - 2.4.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto apresenta os resultados da funcionalidade do requisito F-7.1 através de APIs?

#### Pré-condições
Artefato de exemplo contendo vulnerabilidade de segurança

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. O produto apresenta os resultados da funcionalidade do requisito F-7.1 através de APIs?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Apresentação da vulnerabilidade do artefato via API

#### Resultado Esperado
Demonstração de uso da API RESTful

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 11 - 2.5.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto possui uma API que permita escrever no repositório que certo artefato possui vulnerabilidades, portanto seu uso deve ser evitado?

#### Pré-condições
Exemplos de código disponíveis

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. O produto possui uma API que permita escrever no repositório que certo artefato possui vulnerabilidades, portanto seu uso deve ser evitado?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Execução de chamadas na API e obtenção de respostas que sejam possíveis de confirmação.

#### Resultado Esperado
Demonstração de uso da API RESTful

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 12 - 2.6.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A solução oferece a capacidade de publicar artefatos na solução via API?

#### Pré-condições
Exemplos de código disponíveis

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. A solução oferece a capacidade de publicar artefatos na solução via API?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Execução de chamadas na API e obtenção de respostas que sejam possíveis de confirmação.

#### Resultado Esperado
Demonstração de uso da API RESTful

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 13 - 2.7.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A solução fornece à ferramenta de CI/CD GitHub Actions informações sobre restrição de uso de artefatos (vide requisitos F-2.1, F-6.4, F-6.5, F-6.6, F-6.7), possibilitando, por exemplo, a interrupção do pipeline?

#### Pré-condições
Exemplos de código disponíveis

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. A solução fornece à ferramenta de CI/CD GitHub Actions informações sobre restrição de uso de artefatos (vide requisitos F-2.1, F-6.4, F-6.5, F-6.6, F-6.7), possibilitando, por exemplo, a interrupção do pipeline?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmação que um pipeline em GitHub Actions foi interrompido devido a restrição que foi definida

#### Resultado Esperado
Pipeline interrompido por uso de artefato restrito

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 14 - 2.8.

**Categoria:** API  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A solução fornece à ferramenta de CI/CD GitHub Actions a capacidade de publicar artefatos na solução?

#### Pré-condições
Artefato sendo gerado pelo GitHub Actions e apontando para um repositório da ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **User Management** → **Access Tokens**
3. Gere um token de acesso se necessário
4. Use ferramentas como curl, Postman ou navegador para testar APIs
5. Consulte a documentação da API em: `<URL_JFROG>/ui/api/`

**Ações a Realizar:**
1. A solução fornece à ferramenta de CI/CD GitHub Actions a capacidade de publicar artefatos na solução?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Verificação que o artefato está disponível na ferramenta e que foi gerada pelo pipeline GitHub Actions

#### Resultado Esperado
Artefato publicado por meio de pipeline GitHub Actions

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## SEGURANÇA

### Teste 15 - 3.1

**Categoria:** Segurança  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
É possível verificar a integridade dos artefatos obtidos dos repositórios através de soma de verificação que utilize algoritmo da família SHA-2 ou SHA-3, conforme especificado pelo NIST ?

#### Pré-condições
Algum artefato gerado e seu respectivo SHA

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Security**
3. Acesse as seções: **General**, **Certificates**, **SSH Server**
4. Verifique configurações de segurança e políticas

**Ações a Realizar:**
1. É possível verificar a integridade dos artefatos obtidos dos repositórios através de soma de verificação que utilize algoritmo da família SHA-2 ou SHA-3, conforme especificado pelo NIST ?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmação que na ferramenta o artefato foi armazenado de forma integra conforme o SHA

#### Resultado Esperado
Demonstração de verificação de integridade de artefatos

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 16 - 3.2

**Categoria:** Segurança  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
Todo repositório deve garantir que todo artefato possui um identificador externo e tal identificador é único em todo o repositório?

#### Pré-condições
Ter artefatos criados com seus respectivos identificadores únicos

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Security**
3. Acesse as seções: **General**, **Certificates**, **SSH Server**
4. Verifique configurações de segurança e políticas

**Ações a Realizar:**
1. Todo repositório deve garantir que todo artefato possui um identificador externo e tal identificador é único em todo o repositório?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Conferência de artefato único com seu respectivo identificador

#### Resultado Esperado
Demonstrar que não é possível ter dois ou mais artefatos com o mesmo identificador

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 17 - 3.3

**Categoria:** Segurança  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
Um artefato marcado como RELEASE, uma vez submetido a um repositório com seu identificador externo, NÃO PODERÁ ser submetido novamente ao mesmo repositório com outro conteúdo binário usando o mesmo identificado externo.

#### Pré-condições
Ter o artefato marcado como RELEASE no repositório e outro na mesma versão para tentar subir no mesmo repositório

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Security**
3. Acesse as seções: **General**, **Certificates**, **SSH Server**
4. Verifique configurações de segurança e políticas

**Ações a Realizar:**
1. Um artefato marcado como RELEASE, uma vez submetido a um repositório com seu identificador externo, NÃO PODERÁ ser submetido novamente ao mesmo repositório com outro conteúdo binário usando o mesmo identificado externo.
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmar que a tentativa de subir um artefato marcado como RELEASE na mesma versão para o mesmo repositório é impedido de subir causando erro no processo

#### Resultado Esperado
Demonstrar a unicidade de artefatos releases

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 18 - 3.4

**Categoria:** Segurança  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
Um artefato sem a marcação de RELEASE, uma vez submetido a um repositório com seu identificador externo, PODERÁ ser submetido novamente ao mesmo repositório com outro conteúdo binário usando o mesmo identificado externo.

#### Pré-condições
Ter o artefato sem estar marcado como RELEASE no repositório e outro na mesma versão para tentar subir no mesmo repositório

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Security**
3. Acesse as seções: **General**, **Certificates**, **SSH Server**
4. Verifique configurações de segurança e políticas

**Ações a Realizar:**
1. Um artefato sem a marcação de RELEASE, uma vez submetido a um repositório com seu identificador externo, PODERÁ ser submetido novamente ao mesmo repositório com outro conteúdo binário usando o mesmo identificado externo.
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmar que a tentativa de subir um artefato sem estar marcado como RELEASE na mesma versão para o mesmo repositório sobe com sucesso no processo

#### Resultado Esperado
Demonstrar possibilidade de sobreposição de artefatos que não são releases

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 19 - 3.5

**Categoria:** Segurança  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
Um artefato pode ser marcado (identificado) ou não com um status de liberação RELEASE.

#### Pré-condições
Artefatos disponíveis na ferramenta com marcações diversas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Security**
3. Acesse as seções: **General**, **Certificates**, **SSH Server**
4. Verifique configurações de segurança e políticas

**Ações a Realizar:**
1. Um artefato pode ser marcado (identificado) ou não com um status de liberação RELEASE.
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmação dos tipos de marcação disponíveis

#### Resultado Esperado
Demonstrar a marcação de artefatos releases

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## AUTENTICAÇÃO

### Teste 20 - 4.1.

**Categoria:** Autenticação  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A solução permite criar políticas de controle de acesso baseadas em um ou mais metadados para permitir ou restringir o acesso de leitura a um conjunto de artefatos?

#### Pré-condições
Políticas criadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Configure **LDAP**, **SAML**, **OAuth** conforme necessário
4. Teste login com diferentes métodos de autenticação

**Ações a Realizar:**
1. A solução permite criar políticas de controle de acesso baseadas em um ou mais metadados para permitir ou restringir o acesso de leitura a um conjunto de artefatos?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmação que a política foi criada e que restringe acesso a artefatos com base em metadados

#### Resultado Esperado
Políticas de acesso criadas

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 21 - 4.2.

**Categoria:** Autenticação  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A solução permite criar políticas de limpeza e remoção de artefatos que permitam realizar o saneamento dos repositórios utilizando como critério um ou mais metadados que o artefato possua?

#### Pré-condições
Políticas criadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Configure **LDAP**, **SAML**, **OAuth** conforme necessário
4. Teste login com diferentes métodos de autenticação

**Ações a Realizar:**
1. A solução permite criar políticas de limpeza e remoção de artefatos que permitam realizar o saneamento dos repositórios utilizando como critério um ou mais metadados que o artefato possua?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Confirmação do saneamento com base em metadados configuradas por políticas

#### Resultado Esperado
Políticas criadas

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## AUTORIZAÇÃO

### Teste 22 - 5.1.

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto exige autenticação obrigatória para acesso aos repositórios?

#### Pré-condições
Autenticação SAML ou LDAP e autorização nos repositórios devidamente configurados

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto exige autenticação obrigatória para acesso aos repositórios?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Tentativa de download de artefatos privado sendo negado caso usuário não autenticado e autorizado tente baixá-los

#### Resultado Esperado
Bloqueio de acesso à usuários não autenticados

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 23 - 5.2.

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto controla o acesso às funções de que dispõe através de papéis de usuário conforme especificações abaixo? 
Direitos de acesso são atribuídos a papéis, e os usuários também podem ser atribuídos a papéis. 
Os usuários atribuídos a um papel têm direitos de usar as funções associadas a tal papel. 
Um usuário pode ser atribuido a mais de um papel.

#### Pré-condições
Papéis configurados

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto controla o acesso às funções de que dispõe através de papéis de usuário conforme especificações abaixo? 
Direitos de acesso são atribuídos a papéis, e os usuários também podem ser atribuídos a papéis. 
Os usuários atribuídos a um papel têm direitos de usar as funções associadas a tal papel. 
Um usuário pode ser atribuido a mais de um papel.
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Tentativa de acesso a repositórios ou execução de atividades na ferramenta sendo permitidas ou negadas conforme os papéis definidos.

#### Resultado Esperado
Controle de autorização

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 24 - 5.3.

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto tem ao menos 1 papel com direitos de criar, ler, alterar ou excluir usuários, grupos de usuários, papéis e de conceder direitos de uso de funções a papéis?

#### Pré-condições
Papel configurado

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto tem ao menos 1 papel com direitos de criar, ler, alterar ou excluir usuários, grupos de usuários, papéis e de conceder direitos de uso de funções a papéis?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validação da criação do perfil para criar, ler, alterar ou excluir papéis.

#### Resultado Esperado
Direitos do perfil demonstrados

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 25 - 5.4.

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto tem ao menos 1 papel com direitos de criar, ler, alterar ou excluir políticas de controle de acesso a repositórios ou artefatos?

#### Pré-condições
Papel configurado

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto tem ao menos 1 papel com direitos de criar, ler, alterar ou excluir políticas de controle de acesso a repositórios ou artefatos?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validação da criação do perfil para criar, ler, alterar ou excluir políticas de controle de acesso ou artefatos.

#### Resultado Esperado
Direitos do perfil demonstrados

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 26 - 5.5.

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A solução oferece a possibilidade de atribuir aos papéis as permissões de criação, leitura, alteração, exclusão ou execução de relatórios sobre os repositórios e artefatos mantidos nele?

#### Pré-condições
Papel configurado

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. A solução oferece a possibilidade de atribuir aos papéis as permissões de criação, leitura, alteração, exclusão ou execução de relatórios sobre os repositórios e artefatos mantidos nele?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validação da criação do perfil para criar, ler, alterar ou excluir  relatórios sobre os repositórios e artefatos mantidos neles.

#### Resultado Esperado
Papel com permissões de relatórios criado

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 27 - 5.6

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto permite atribuir aos papéis as permissões de publicar artefatos em repositórios controlados pelo produto?

#### Pré-condições
Papel configurado

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto permite atribuir aos papéis as permissões de publicar artefatos em repositórios controlados pelo produto?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validação da atribuição de algum papel que permita publicar atefatos em repositórios controlados pelo produto.

#### Resultado Esperado
Papel com permissões de publicação criado

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 28 - 5.7

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto permite atribuir aos papéis a permissão de criar, ler, alterar, excluir ou executar políticas de limpeza e remoção de artefatos?

#### Pré-condições
Papel configurado

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto permite atribuir aos papéis a permissão de criar, ler, alterar, excluir ou executar políticas de limpeza e remoção de artefatos?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validação da criação do perfil para criar, ler, alterar ou excluir políticas de limpeza e remoção de artefatos.

#### Resultado Esperado
Papel com permissão de limpeza e remoção criado

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 29 - 5.8

**Categoria:** Autorização  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto permite a configuração de papéis vindo de entidades externas como grupos de LDAP, Entra ID (Azure AD) ou SAML?

#### Pré-condições
Integração com LDAP, Entra ID (Azure AD) ou SAML capturando grupos e mapeando com os papeis na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **Identity and Access**
3. Acesse **Users**, **Groups**, **Permissions**
4. Configure e teste diferentes níveis de acesso

**Ações a Realizar:**
1. O produto permite a configuração de papéis vindo de entidades externas como grupos de LDAP, Entra ID (Azure AD) ou SAML?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Verificação do mapeamento na ferramenta do perfil conforme os papéis configurados nos grupos externos.

#### Resultado Esperado
Inclusão do usuário de teste em algum grupo externo da ferramenta e sendo mapeado nela por intermédio do LDAP,  SALM ou Entra ID.

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## INTEGRAÇÃO

### Teste 30 - 6.1.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
A API REST é capaz de fornecer o SBOM dos artefatos mantidos no repositório?

#### Pré-condições
Ter o SBOM disponível para consumo via API

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. A API REST é capaz de fornecer o SBOM dos artefatos mantidos no repositório?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar o consumo do SBOM via API

#### Resultado Esperado
SBOM de artefatos criado via API

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 31 - 6.2.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de fornecer listas de materiais (Software Bill of Materials, SBOM, vide https://owasp.org/www-community/Component_Analysis) dos artefatos?

#### Pré-condições
Ter o SBOM disponível para consumo via API

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. O produto é capaz de fornecer listas de materiais (Software Bill of Materials, SBOM, vide https://owasp.org/www-community/Component_Analysis) dos artefatos?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar o consumo do SBOM via API

#### Resultado Esperado
SBOM criado via Aplicação

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 32 - 6.3.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
Os SBOMs estão em um dos seguintes formatos: CycloneDX (https://cyclonedx.org/) ou SPDX (https://spdx.dev/)?

#### Pré-condições
Ter o SBOM disponível para consumo via API

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. Os SBOMs estão em um dos seguintes formatos: CycloneDX (https://cyclonedx.org/) ou SPDX (https://spdx.dev/)?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar o retorno nos formatos CycloneDX ou SPDX

#### Resultado Esperado
SBOM criado em ums dos formatos

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 33 - 6.4.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de prover ao menos as seguintes informações sobre cada artefato: nome, fornecedor, versão, dependências de outros artefatos e carimbo do tempo referente a data de montagem do artefato (https://www.ntia.gov/files/ntia/publications/sbom_minimum_elements_report.pdf)?

#### Pré-condições
Artefatos disponíveis na ferramenta com as informações de SBOM disponíveis

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. O produto é capaz de prover ao menos as seguintes informações sobre cada artefato: nome, fornecedor, versão, dependências de outros artefatos e carimbo do tempo referente a data de montagem do artefato (https://www.ntia.gov/files/ntia/publications/sbom_minimum_elements_report.pdf)?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar as informações de artefatos conforme publicação da NTIA

#### Resultado Esperado
Demonstrar informações sobre artefatos

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 34 - 6.5.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de analisar e identificar vulnerabilidades de segurança em artefatos e bibliotecas open-source, utilizando bases de dados de referência, como, por exemplo, VulnDB ou NVD NIST?

#### Pré-condições
Artefatos open-source na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. O produto é capaz de analisar e identificar vulnerabilidades de segurança em artefatos e bibliotecas open-source, utilizando bases de dados de referência, como, por exemplo, VulnDB ou NVD NIST?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar que o artefato está na base de dados de referência VulDB ou NVD NIST.

#### Resultado Esperado
Artefatos com vulnerabilidade detectados

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 35 - 6.6.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de analisar e identificar violações de licenças em artefatos e bibliotecas open-source, utilizando bases de dados de referência, como, por exemplo, VulnDB ou NVD NIST?

#### Pré-condições
Artefatos open-source na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. O produto é capaz de analisar e identificar violações de licenças em artefatos e bibliotecas open-source, utilizando bases de dados de referência, como, por exemplo, VulnDB ou NVD NIST?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar que o artefato está em conformidade com a licença de uso com base na referência VulDB ou NVD NIST.

#### Resultado Esperado
Artefatos com violação de licenças detectados

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 36 - 6.7.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de impedir o uso (download) de artefatos que violarem políticas de uso configuradas na solução?

#### Pré-condições
Políticas criadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. O produto é capaz de impedir o uso (download) de artefatos que violarem políticas de uso configuradas na solução?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar que a tentativa de upload de artefato não licenciado é bloqueada conforme política definida.

#### Resultado Esperado
Artefato com vulnerabilidade bloqueado

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 37 - 6.8.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
É possível implementar políticas que impeçam o uso de artefatos que possuam vulnerabilidades como as identificadas através da função descrita em F-6.4?

#### Pré-condições
Políticas criadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. É possível implementar políticas que impeçam o uso de artefatos que possuam vulnerabilidades como as identificadas através da função descrita em F-6.4?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar que a tentativa de upload de artefato com vulnerabilidade é bloqueada conforme política definida.

#### Resultado Esperado
Política de restrição implementada

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 38 - 6.9.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
É possível implementar políticas que impeçam o uso de artefatos cujas licenças sejam incompatíveis com as especificadas nas políticas de uso de artefatos?

#### Pré-condições
Políticas criadas

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. É possível implementar políticas que impeçam o uso de artefatos cujas licenças sejam incompatíveis com as especificadas nas políticas de uso de artefatos?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar que a tentativa de uso de artefato cujas licenças sejam incompatíveis com as política definidas sejam impedidas no consumo.

#### Resultado Esperado
Política de restrição implementada

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 39 - 6.10.

**Categoria:** Integração  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de analisar e identificar quais licenças dos artefatos e bibliotecas open-source são utilizadas, tendo como bases de dados de referência, por exemplo, VulnDB ou NVD NIST?

#### Pré-condições
Artafatos opensource disponíveis na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue para **Administration** → **General** → **Configuration**
3. Configure integrações externas conforme necessário
4. Teste conectividade e sincronização

**Ações a Realizar:**
1. O produto é capaz de analisar e identificar quais licenças dos artefatos e bibliotecas open-source são utilizadas, tendo como bases de dados de referência, por exemplo, VulnDB ou NVD NIST?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar que a ferramenta identifica as licenças dos artefatos tendo como base o VulnDB e NVD NIST.

#### Resultado Esperado
Informações de uso de componentes apresentada

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## INTERFACE

### Teste 40 - 7.1.

**Categoria:** Interface  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto é capaz de realizar varredura de vulnerabilidades nos artefatos (e imagens de containers)?

#### Pré-condições
Artafatos disponíveis na ferramenta

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue pelas diferentes seções da interface
3. Teste funcionalidades de UI/UX
4. Verifique responsividade e usabilidade

**Ações a Realizar:**
1. O produto é capaz de realizar varredura de vulnerabilidades nos artefatos (e imagens de containers)?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Validar o relatório gerado sobre a varredura de vulnerabilidade detectadas nos artefatos

#### Resultado Esperado
Resultado de varreduras apresentado

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

### Teste 41 - 7.2.

**Categoria:** Interface  
**Tempo Estimado:**  minutos  
**Avaliador:**   

#### Descrição do Teste
O produto apresenta os resultados da funcionalidade do requisito F 7.1 através da interface gráfica do produto?

#### Pré-condições
Artefato exemplo com vulnerabilidade de segurança

**Navegação no JFrog:**
1. Acesse a interface web do JFrog Artifactory
2. Navegue pelas diferentes seções da interface
3. Teste funcionalidades de UI/UX
4. Verifique responsividade e usabilidade

**Ações a Realizar:**
1. O produto apresenta os resultados da funcionalidade do requisito F 7.1 através da interface gráfica do produto?
2. Siga as pré-condições estabelecidas
3. Execute as operações necessárias conforme o teste
4. Verifique os resultados obtidos
5. Compare com os critérios de aceitação

#### Critérios de Aceitação (OK/Not OK)
Exibiição de detalhes do artefato com a vulnerabilidade

#### Resultado Esperado
Resultado de varreduras apresentado

#### Resultado do Teste
- [ ] **OK** - Teste passou
- [ ] **Not OK** - Teste falhou
- [ ] **N/A** - Não aplicável

**Observações:**
_[Espaço para anotações durante a execução]_

---

## RESUMO DE EXECUÇÃO

### Checklist Geral
- [ ] Todos os 41 testes foram executados
- [ ] Resultados documentados adequadamente
- [ ] Problemas identificados foram reportados
- [ ] Evidências coletadas quando necessário

### Estatísticas Finais
- **Total de Testes:** 41
- **Testes OK:** ___
- **Testes Not OK:** ___
- **Testes N/A:** ___
- **Taxa de Sucesso:** ___%

### Observações Gerais
_[Espaço para comentários gerais sobre a execução dos testes]_

---

**Documento gerado automaticamente em:** Junho 2025  
**Baseado em:** Adendo G - Caderno de Testes.xlsx  
**Versão:** 1.0  
