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

É uma [ferramenta opensource](https://github.com/linkedin/qark) utilizada para encontrar vulnerabilidades em apps Android. Ela automatiza o uso de multiplos descompiladores e facilita o trabalho, trazendo mais resultados nesse processo. 

- **MobSF**

[Mobile Security Framework](https://github.com/MobSF/Mobile-Security-Framework-MobSF), é uma ferramenta automatizada e completa(funciona em todas as plataformas), voltada para pentest, análise de malware e avaliação de segurança, que permite análises estáticas e dinâmicas.


### 

### Mobile Protection for Android Users 

- Manter o dispositivo sempre atualizado
- Não salve todas as senhas no seu dispositivo, usar gerenciadores de senha 
- Não guardar dados sensíveis/pessoais em bloco de notas 
- Usar autenticação de dois fatores
- Aproveite os recursos de segurança integrados do Android
- Certifique-se de que sua rede WiFi é segura (e tenha cuidado com WiFi público)
- Faça backup dos dados do seu telefone Android
- Compre aplicativos apenas do Google Play
- Usar uma VPN

### Mobile Protection for iOS Users 

- Mantenha o sistema operacional do seu iPhone (iOS) atualizado
- Ative o recurso “encontrar meu iPhone”
- Configure uma senha maior do que a predefinição de 4 números
- Ativar autenticação de dois fatores
- Altere regularmente suas senhas do iCloud e iTunes
- Evite Wi-Fi público e use apenas Wi-Fi seguro
- Use apenas estações de carregamento de iPhone confiáveis
- Desative a Siri na tela de bloqueio do iPhone
- Revogue as permissões do aplicativo para usar a câmera, o microfone etc.

### Mobile Protection for Companies 

- Estabelecer políticas sobre o uso dos dispositivos móveis
- Segmentar dados e aplicativos em dispositivos corporativos
- Criptografe e minimize a visibilidade dos dispositivos que têm acesso à rede da empresa
- Instale software de segurança em dispositivos móveis, como MDM 
- Cultura de segurança, conscientização sobre segurança por meio de treinamentos

### Web-based threats 

Sites podem baixar malware em nossos dispositivos móveis sem nossa permissão ou conhecimento.
O phishing é uma maneira típica de os invasores nos fazerem clicar em links para sites que contêm ameaças móveis. Por exemplo, um atacante pode configurar um site que pareça legítimo (por exemplo, como nosso site bancário) para capturar nossas credenciais de login. Um software de segurança em nossos telefones pode ajudar a detectar sites maliciosos e tentativas de phishing. Também vale a pena ser mais cuidadoso e atencioso. 

### App-based threats

Atacantes criam aplicativos maliciosos que baixamos ou até compramos. Uma vez instalados, esses aplicativos podem roubar nossos dados pessoais de nossos dispositivos ou gastar nosso dinheiro com nossos aplicativos de toque e pague. É uma boa prática verificar as cobranças e as compras com cuidado. Manter o software móvel atualizado também ajuda na defesa contra aplicativos mal-intencionados, pois os fabricantes de dispositivos atualizam periodicamente seus softwares para corrigir vulnerabilidades que esses aplicativos exploram. O objetivo é proteger as informações armazenadas ou acessíveis através do dispositivo. 

### Physical threats 

Dispositivos móveis são pequenos e fáceis de roubar. Eles também se perdem com bastante frequência. Sem a segurança adequada do dispositivo, um dispositivo móvel roubado é um tesouro de informações pessoais e financeiras para um bandido. Para mitigar as ameaças físicas aos dispositivos móveis, é aconselhável estabelecer senhas fortes e configurar o dispositivo para se bloquear quando não estiver em uso, pois telefones perdidos ou roubados são os casos mais comuns de ameaças físicas. O software de rastreamento antirroubo também ajuda a recuperar um telefone perdido.

### Network threats 

Os dispositivos móveis geralmente estão conectados a pelo menos duas redes. e às vezes mais. Estes incluem conexão celular, Wi-FI, Bluetooth e GPS. Cada um desses pontos de conexão pode ser explorado. 
A falsificação de WiFi, por exemplo, é uma ameaça na qual um invasor simula o acesso a uma rede WiFi aberta e induz os usuários a se conectarem para detectar dados sensíveis que estão sendo processados por essa rede.
