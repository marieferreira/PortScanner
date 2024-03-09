Um port scanner é uma ferramenta com o objetivo de mapear as portas TCP e UDP.
Neste teste ele identifica o status das portas, se estão fechadas, escutando ou abertas. 

Uma varredura de porta é uma técnica de reconhecimento de rede projetada para identificar quais portas estão abertas em um computador. Isso pode permitir que o scanner identifique o aplicativo em execução no sistema à medida que determinados programas escutam em portas específicas e reagem ao tráfego de determinadas maneiras.

    ->Varredura SYN: Um pacote SYN é o primeiro passo no handshake TCP, e as portas abertas responderão com um SYN-ACK. Em uma varredura semiaberta SYN ou TCP, o scanner de porta não completa o handshake com o ACK final, portanto a conexão TCP completa não é aberta.
    
    ->Verificação de conexão TCP: Uma varredura de conexão TCP conclui o handshake TCP completo. Assim que a conexão for estabelecida, o scanner a desmontará normalmente.
    
    ->Verificação UDP: As varreduras UDP verificam as portas que escutam o tráfego UDP. Eles podem identificar DNS e outros serviços baseados em UDP.