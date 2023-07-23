# Princípios SOLID

Os princípios SOLID são um conjunto de diretrizes para escrever código limpo, sustentável e de fácil manutenção, criados por Robert C. Martin (também conhecido como Uncle Bob). Esses princípios visam promover a criação de software de alta qualidade, permitindo que os desenvolvedores escrevam código que seja fácil de entender, estender e modificar ao longo do tempo.

## 1. Princípio da Responsabilidade Única (SRP - Single Responsibility Principle)

Uma classe deve ter uma única responsabilidade e deve ter apenas um motivo para mudar. Em outras palavras, uma classe deve ser responsável por apenas uma tarefa específica dentro do sistema, evitando assim que ela cresça demais e se torne difícil de gerenciar.

## 2. Princípio do Aberto/Fechado (OCP - Open/Closed Principle)

Entidades de software, como classes e módulos, devem ser abertas para extensão, mas fechadas para modificação. Isso significa que você pode estender o comportamento de uma classe sem precisar modificá-la diretamente, tornando o código mais robusto e menos propenso a bugs quando novos requisitos surgirem.

## 3. Princípio da Substituição de Liskov (LSP - Liskov Substitution Principle)

As subclasses devem ser substituíveis por suas classes base sem afetar a integridade do sistema. Em outras palavras, uma classe derivada deve ser capaz de substituir a classe base sem alterar o comportamento esperado do programa.

## 4. Princípio da Segregação de Interface (ISP - Interface Segregation Principle)

As interfaces dos clientes não devem ser forçadas a depender de métodos que elas não usam. Em vez disso, é melhor ter interfaces específicas para cada cliente, contendo apenas os métodos relevantes para eles.

## 5. Princípio da Inversão de Dependência (DIP - Dependency Inversion Principle)

Dependa de abstrações, não de implementações concretas. Esse princípio incentiva a dependência em interfaces e classes abstratas em vez de depender de classes concretas. Isso torna o código mais flexível, facilitando a substituição de implementações sem afetar o restante do sistema.

Lembrando que a aplicação consistente desses princípios pode levar a um código mais limpo, coeso e de fácil manutenção, tornando-o mais adaptável às mudanças e evoluções do software ao longo do tempo.
