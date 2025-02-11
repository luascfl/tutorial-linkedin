# tutorial-linkedin
Este repositório contém uma coleção de bookmarklets e scripts em JavaScript projetados para automatizar várias tarefas no LinkedIn. Essas ferramentas visam melhorar a eficiência dos usuários, mas devem ser usadas de forma responsável e ética, respeitando os Termos de Serviço do LinkedIn. **O uso excessivo ou inadequado pode resultar na suspensão da conta.**
## Visão Geral do Projeto
Este projeto não é uma única aplicação, mas sim uma coleção de scripts independentes que abordam necessidades específicas de automação no LinkedIn. Cada script está contido em seu próprio subdiretório e inclui seu próprio README e licença. Os scripts incluem funcionalidades como:
* **Automatização da Configuração de Notificações:** Configurar as preferências de notificação do LinkedIn.
* **Exclusão de Alertas do LinkedIn:** Excluir notificações de alertas de emprego em massa.
* **Seguir Empresas:** Seguir automaticamente empresas no LinkedIn.
* **Conectar-se com Pessoas:** Automatizar solicitações de conexão.
* **Atualizar Alertas de Emprego:** Modificar as configurações de notificação para alertas de emprego existentes.
* **Excluir Notificações do LinkedIn:** Excluir várias notificações do LinkedIn de uma só vez.

## Estrutura do Projeto
O projeto está organizado em submódulos, cada um representando uma tarefa de automação distinta:
* **`auto-confignotifications-linkedin`**:  Automatiza a configuração das preferências de notificação do LinkedIn.
* **`auto-connect-linkedin`**: Automatiza solicitações de conexão no LinkedIn.
* **`auto-deletealerts-linkedin`**: Automatiza a exclusão de alertas de emprego no LinkedIn. Inclui uma versão em bookmarklet.
* **`auto-deletenotifications-linkedin`**: Fornece um bookmarklet para exclusão em massa de notificações do LinkedIn. Inclui versões em inglês e português.
* **`auto-followcompany-linkedin`**: Automatiza o acompanhamento de empresas no LinkedIn.
* **`auto-updatejobalerts-linkedin`**: Automatiza a atualização das configurações de alertas de emprego existentes no LinkedIn. Inclui uma versão em bookmarklet.
Cada submódulo contém seu próprio `README.md`, arquivo `LICENSE` e o(s) script(s) em JavaScript.

## Instalação e Uso
Cada submódulo fornece suas próprias instruções detalhadas de instalação e uso dentro do respectivo arquivo `README.md`. Em geral, os scripts são projetados para serem injetados no console de desenvolvedor do navegador ou usados como bookmarklets. Consulte os `READMEs` individuais de cada submódulo para obter instruções específicas.
Aqui está um resumo da abordagem geral para cada tipo de script:
**Bookmarklets:**
1. Selecione todo o código JavaScript do arquivo `.js` designado dentro do submódulo relevante (por exemplo, `auto-deletealerts-linkedin\Bookmarklet (Selecione o código e arraste para a barra de favoritos) Deletar alertas do LinkedIn.js`).
2. Crie um novo favorito no seu navegador.
3. Cole o código JavaScript no campo URL do novo favorito.
4. Dê ao favorito um nome descritivo (por exemplo, "Excluir Alertas do LinkedIn").
5. Navegue até a página do LinkedIn apropriada.
6. Clique no bookmarklet.
**Scripts do Console de Desenvolvedor:**
1. Abra as ferramentas de desenvolvimento do seu navegador (geralmente pressionando F12).
2. Navegue até a aba "Console".
3. Copie o código JavaScript do arquivo `.js` designado dentro do submódulo relevante (por exemplo, `auto-confignotifications-linkedin\Código para replicar configurações de notificações LinkedIn.js`).
4. Cole o código no console e pressione Enter.
**Notas Importantes:**
* Esses scripts interagem diretamente com a estrutura HTML do LinkedIn. Alterações no site do LinkedIn podem quebrar os scripts.
* Use esses scripts de forma responsável e dentro dos Termos de Serviço do LinkedIn. O uso excessivo pode resultar na suspensão da conta.
* Sempre monitore o console do navegador em busca de mensagens de erro. Essas mensagens fornecerão informações sobre quaisquer problemas encontrados durante a execução do script.

## Contribuição
Contribuições são bem-vindas. Consulte o `README.md` individual de cada submódulo para obter diretrizes específicas de contribuição, se houver.
## Licença
Cada submódulo está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` dentro de cada submódulo para obter detalhes. Este README principal do repositório não implica nenhuma licença para a coleção como um todo além das licenças individuais de cada submódulo.