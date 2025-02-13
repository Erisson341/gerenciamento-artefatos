```mermaid
graph TD;
    A[Responsável ITIL] -->|Cria Repositório| B[Repositório GitHub];
    B -->|Armazena| C[Artefatos do Projeto];
    C -->|Inclui| D[Requisitos de Software];
    C -->|Inclui| E[Diagramas e Documentação];
    C -->|Inclui| F[Código-Fonte];
    C -->|Inclui| G[Casos de Teste];

    H[Equipe de Desenvolvimento] -->|Versiona Código| B;
    I[Equipe de Qualidade] -->|Revisa e Valida Artefatos| C;
    J[Gestores] -->|Aprovam Estratégia de Gestão| A;

