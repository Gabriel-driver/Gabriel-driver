# Integração com o ERP

Robôs em Python, com agenda, num servidor. Leem o SQL Server do ERP e gravam no PostgreSQL que alimenta painel, comissão, prazo e tarifa do site.

SQL dos dois lados: a origem no SQL Server e o modelo analítico no PostgreSQL.

## Como a carga se comporta

- A carga pesada roda fora do horário em que a operação consulta
- O que muda o dia inteiro atualiza em ciclo curto
- Comissão tem versão. O painel usa a regra vigente, sem somar regra antiga com regra nova
