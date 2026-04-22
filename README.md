# EcoMonitor

## Identificação
Nome: Luan Mauricio Oliveira Fernandes da Silva

Curso: Ciência da Computação

---
![Tela](ecoMonitor/exemplo.png)
---
## Heurísticas de Nielsen

- **Visibilidade do Status do Sistema**: O sistema apresenta o total acumulado em tempo real, permitindo ao usuário acompanhar seu progresso de forma clara.

- **Feedback do Usuário**: Ao clicar no botão "Registrar Atividade", o sistema responde imediatamente atualizando o contador e a barra de progresso.

---

## 🧠 Explicação Técnica

O componente `EcoStatus` foi desenvolvido de forma reutilizável utilizando o recurso `[Parameter]` do Blazor.

O `[Parameter]` permite que valores sejam passados para o componente no momento em que ele é utilizado na página, como por exemplo o título da ação (`Titulo`) e o peso da ação (`Peso`).

Dessa forma, o mesmo componente pode ser reutilizado várias vezes com comportamentos diferentes, sem a necessidade de criar múltiplos componentes para cada tipo de ação.

Cada instância do componente mantém seu próprio estado interno (`total`), que é atualizado dinamicamente através do evento `@onclick`, refletindo imediatamente na interface do usuário.

---

## Guia de Execução

Para executar o projeto, siga os passos abaixo:

```bash
git clone https://github.com/SEU_USUARIO/una-blazor-lista12.git
cd una-blazor-lista12
dotnet run
