🧠 Perguntas rápidas

O que é CI/CD e por que é importante?
➡️ CI/CD é o processo de integrar e entregar código continuamente.
CI (Integração Contínua) testa cada alteração automaticamente;
CD (Entrega/Implantação Contínua) automatiza a entrega em produção.
É importante porque detecta erros cedo e agiliza o desenvolvimento.

Em qual pasta os workflows do GitHub ficam armazenados?
➡️ Na pasta .github/workflows.

🧩 Etapa 3 – Verificando o pipeline

O que aparece no log do GitHub Actions após a execução?
➡️ Os logs de cada etapa (checkout, setup do Python e execução do script) e a mensagem “Hello CI/CD!” impressa pelo programa.

O que acontece se alterar o código e fizer novo push?
➡️ O GitHub Actions executa automaticamente o workflow novamente com o novo código.

🧩 Etapa 4 – Introduzindo um teste automatizado

O que acontece se um teste falhar?
➡️ O workflow é marcado como falhou (failed) e o log mostra qual teste deu erro; os passos seguintes não são executados.

🧠 4. Para finalizar

Como o GitHub Actions ajuda a detectar erros cedo?
➡️ Ele executa testes automaticamente a cada push, identificando falhas antes de ir para produção.

Quais seriam exemplos reais de CI/CD em projetos web ou mobile?
➡️ Build e testes automáticos em cada commit, deploy automático em servidores web, Play Store ou App Store.

Como o deploy automático poderia ser feito a partir deste pipeline?
➡️ Adicionando um job de deploy no workflow, configurado com tokens/segredos, que envia o código para serviços como Heroku, AWS, Vercel ou Netlify após os testes passarem.
