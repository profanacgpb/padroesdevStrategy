🧩 Padrão Strategy na Prática (Exemplo JavaScript)

🧠 Problema: Calcular o valor do frete de acordo com a estratégia de transporte escolhida pelo usuário.

💻 Código Completo (com interface interativa)

Você pode copiar e colar esse código em um arquivo chamado index.html e abrir no navegador.
Ele mostra na prática como o Strategy troca comportamentos sem if/else — tudo muda dinamicamente!

🧠 Como funciona

Cada tipo de frete (Correios, Transportadora, Expressa) é uma estratégia concreta que implementa o método calcular().

A classe CalculadoraFrete não precisa saber como o cálculo é feito — ela apenas usa a estratégia passada.

O usuário muda o tipo de frete, e o cálculo muda automaticamente, sem if/else complexos no núcleo do sistema.

📈 Vantagens demonstradas
Benefício	Explicação
🔄 Extensibilidade	Fácil adicionar um novo tipo de frete (basta criar nova classe).
🧩 Reutilização	Cada estratégia pode ser usada em outros sistemas.
🧠 Clareza	Cada regra de negócio fica isolada.
🧪 Testabilidade	Testes podem ser feitos em cada estratégia separadamente.
