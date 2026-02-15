# Log Analysis Lab

## Objetivo
Demonstrar a análise básica de logs de autenticação para identificar atividades suspeitas.

## Cenário
Um analista de segurança revisa registros de login para detectar possíveis tentativas
de acesso não autorizado.

## Método de Análise
Os registros de autenticação foram analisados para identificar padrões de tentativas
de login com falha, observando repetição de usuários, endereços IP e intervalos de tempo.

## Resultados
Foram identificadas múltiplas tentativas de login com falha para o usuário "admin",
originadas do mesmo endereço IP externo, indicando uma possível tentativa de força bruta.

## Validação de Negócio
De acordo com boas práticas de segurança da informação, múltiplas falhas consecutivas
de autenticação devem gerar alertas de segurança para prevenir acessos não autorizados
e proteger a integridade dos sistemas.

## Conclusão
A análise de logs é essencial para a detecção precoce de ameaças e para a proteção
dos ativos digitais da organização.
