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
