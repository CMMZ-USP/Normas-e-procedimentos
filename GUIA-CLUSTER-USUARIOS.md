# Guia de uso do cluster (versão pública)

> Versão para usuários. Detalhes técnicos e de rede ficam no repositório
> privado de infraestrutura.

## Solicitar conta
[PREENCHER: como pedir, quem aprova, validade da conta.]

## Onde guardar dados

| Área | Uso | Cota | Backup | Limpeza automática |
|---|---|---|---|---|
| home | scripts e configurações | [ ] | sim/não | não |
| projeto | dados do projeto | [ ] | sim/não | não |
| scratch | arquivos temporários de processamento | [ ] | não | após [N] dias |

## Submeter trabalhos
[PREENCHER: gerenciador de filas, filas disponíveis, limites, exemplo de script de submissão.]

## Software disponível
[PREENCHER: módulos, conda, containers; como pedir instalação.]

## Boas práticas
- Não rode processamento pesado no nó de acesso.
- Comprima ou apague intermediários ao terminar.
- Seus dados são sua responsabilidade: mantenha cópia do que for essencial
  e deposite dados brutos em SRA/ENA ao publicar.

## Encerramento da conta
[PREENCHER: o que acontece com os dados quando o vínculo termina.]
