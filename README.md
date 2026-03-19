ScannerExpert - Simulador de Deep Scan

Este projeto simula uma varredura de sistema (Deep Scan) via terminal, mostrando mensagens de progresso em tempo real. O objetivo é aplicar um conceito importante de UX, que é manter o usuário informado sobre o que está acontecendo durante o processamento.

Objetivo

Demonstrar na prática a 1ª Heurística de Nielsen, chamada Visibilidade do Status do Sistema. Essa heurística diz que o sistema deve sempre informar ao usuário o que está acontecendo, com feedback adequado e em tempo razoável.

Como funciona

O programa simula uma análise de hardware passando por várias etapas, como verificação de CPU, leitura de memória RAM, sincronização de sistema, validação de permissões e finalização. Durante a execução, ele mostra mensagens como [PROCESSANDO...] e utiliza Thread.Sleep() para simular o tempo de processamento.

Por que isso é importante

Se o sistema não mostrar nada, o usuário pode achar que travou ou parou de funcionar. Já com mensagens de progresso, o usuário entende que o sistema ainda está rodando, gera mais confiança e melhora a experiência de uso.

Evidência

O arquivo "minha-evidencia.png" mostra o terminal durante a execução, comprovando que o sistema informa o status em tempo real.

Tecnologias utilizadas

C# e .NET (Console Application)

Conclusão

Mesmo em aplicações simples de terminal, informar o que está acontecendo é essencial. Pequenos feedbacks fazem muita diferença na experiência do usuário.
