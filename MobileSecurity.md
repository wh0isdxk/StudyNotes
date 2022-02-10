# Mobile Studies 

Quando falamos sobre dispositivos móveis, logo de cara já podemos listar uma série de dados que estão presentes e/ou armazenados por lá:
- E-mails pessoais ou relacionados ao trabalho 
- Informações bancárias e chaves pix que podem ser encontradas a partir do próprio e-mail ou lista de contatos 
- Logs e informações de mensagens, assim como as próprias mensagens 
- Imagens, vídeos, áudios 
- Localização, GPS e informações de rastreio 
- Dados relacionados a saúde 
- Calendário e agenda 

Todos esses dados, separados e, principalmente juntos, apresentam uma parcela muito grande de nossas vidas e de pessoas que são próximas a nós. 
Não é a toa que grande parte dos ataques atualmente tem tido mobile como seu vetor principal. 


### Android Protection Levels (user) 

**Normal**: Esse é o padrão utilizado, permite a aplicação acessae features isoladas, que gerariam um mínimo risco as demais aplicações, ao usuário e ao sistema. E ele é garantido automaticamente pelo sistema, mas o user tem a permissão para fazer essas alterações na instalação e, hoje em dia, após também (GDPR e LGPD). 

**Perigoso**: Permite a aplicaçãp performar certas operações que podem custar ao usuário algum dano maior, como transações bancárias (compras dentro do app), ter acesso e modificar dados do usuário que podem causar algum dano, e isso precisa ser explicitamente aprovado pelo usuário em questão (tela de confirmação). 
 
**Signature**: Permite somente as aplicações que possuírem o mesmo certificado que a aplicação que declarou as permissões. 

**Signature or System**: Permite as aplicações que estiverem na imagem do sistema Android ou que forem assinadas com os mesmos certificados. 

### Ferramentas 
- **Apktool** 

Uma das ferramentas mais importantes quando se trata de pentest em Android, é usada pra engenharia reversa, criação de malware infectando apps legítimos. 

- **Dex2jar and JDGUI** 

Dex2jar converte arquivos .dex para .jar e o JDGUI decompila o .jar para o código fonte Java. 

- **Burp Suite**

Outra ferramenta super utilizada quando se fala de pentest é o Burp, e uma das possibilidades utilizando ele é de analisar o tráfego rodando o app num emulador. 

- **drozer** 

Uma tool automatizada de análises voltada para Android. 

- **Frida**

Um framework desenvolvido para instrumentação dinâmica de apps multiplataforma, permite adentrar no app e manipular um determinado comando em tempo de execução (runtime). 

- **QARK** 

É uma ferramenta opensource utilizada para encontrar vulnerabilidades em apps Android. Ela automatiza o uso de multiplos descompiladores e facilita o trabalho, trazendo mais resultados nesse processo. 
