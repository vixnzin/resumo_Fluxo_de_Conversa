# Desafio: Criando um Copilot com Microsoft Copilot Studio

## Sobre o desafio

O objetivo deste desafio foi explorar e dominar a criação de um Copilot personalizado utilizando a plataforma Microsoft Copilot Studio, permitindo a construção de fluxos de conversas inteligentes e interativos, voltados para atender necessidades específicas dos usuários. O foco principal foi desenvolver um assistente conversacional que pudesse guiar o usuário com respostas contextualizadas e personalizadas, usando recursos avançados de inteligência artificial integrados na ferramenta.

## Etapas que segui

1. **Criação do Copilot inicial**  
   Comecei criando um Copilot em branco através do portal oficial do Microsoft Copilot Studio ([https://copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)). A interface é bastante intuitiva, permitindo escolher templates ou iniciar do zero. Optei por iniciar um projeto completamente do zero para entender o funcionamento detalhado da plataforma.

2. **Construção e customização do fluxo de conversa**  
   Para testar a dinâmica da ferramenta, criei um tópico simples que simula uma conversa básica. Nesse fluxo, configurei mensagens de boas-vindas, perguntas direcionadas e respostas condicionais que variam conforme as respostas do usuário. Por exemplo, criei condições para que, se o usuário informasse que estava com dúvidas técnicas, o Copilot direcionasse a conversa para um roteiro de solução técnica, enquanto para dúvidas gerais, a conversa tomava outro caminho.

3. **Personalização das mensagens de erro**  
   Uma das etapas importantes foi definir mensagens claras e amigáveis para quando o Copilot não entendesse o que o usuário perguntou ou quando algum tópico não estivesse coberto. Criei mensagens de erro personalizadas para evitar que a experiência do usuário fosse interrompida de forma abrupta. Por exemplo, configurei o Copilot para responder:  
   > “Desculpe, não entendi sua pergunta. Poderia reformular ou tentar um tema diferente?”

4. **Ajuste da qualidade das respostas com GenAI**  
   A ferramenta permite manipular o parâmetro de qualidade da resposta gerada pela inteligência artificial (GenAI). Fiz diversos testes aumentando e diminuindo esse parâmetro para perceber como isso afetava o tempo de resposta, a complexidade e a precisão das informações fornecidas pelo Copilot. Percebi que respostas de maior qualidade são mais detalhadas e precisas, mas podem demorar um pouco mais para serem geradas, enquanto respostas de qualidade menor são mais rápidas, porém mais superficiais.

5. **Testes e refinamento**  
   Após configurar o fluxo, realizei testes simulando interações reais para validar a coerência das respostas, a fluidez da conversa e a experiência do usuário. Com base nesses testes, ajustei as mensagens e as transições entre tópicos para tornar o diálogo mais natural e intuitivo.

## O que aprendi

- **Criação de fluxos conversacionais personalizados:** Compreendi como estruturar tópicos e subtópicos para que o assistente possa guiar o usuário em diferentes cenários, respeitando o contexto e os interesses dele.
- **Importância da comunicação clara em mensagens de erro:** Mensagens amigáveis e orientativas evitam a frustração do usuário e podem incentivar a continuidade da conversa, mesmo quando há limitações no reconhecimento das perguntas.
- **Controle fino da qualidade da geração de texto:** Ajustar o nível de detalhamento e precisão das respostas impacta diretamente na experiência do usuário e nos recursos computacionais utilizados, sendo essencial balancear esses aspectos conforme a aplicação desejada.
- **Funcionamento e potencial da Microsoft Copilot Studio:** A plataforma oferece ferramentas poderosas para construção de assistentes inteligentes, integrando facilmente recursos de IA e facilitando o desenvolvimento de conversas complexas sem necessidade de codificação avançada.
- **Testes iterativos são cruciais:** Apenas experimentando com fluxos reais e interações simuladas foi possível aprimorar a usabilidade e a naturalidade do assistente.

## Link útil

- Documentação oficial do Microsoft Copilot Studio:  
  [https://learn.microsoft.com/pt-br/microsoft-copilot-studio/](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/)
