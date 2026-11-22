# DF-ARC-007 — Candidatos de hardware e controle de cotação
**Pesquisa em 22/11/2026.** Documento de apoio, **não constitui proposta comercial nem homologação definitiva**.

## Candidatos localizados
| Categoria | Necessidade do projeto | Candidato / referência identificável | Indicação de preço encontrada | Fonte | Condição |
|---|---|---|---|---|---|
| RAM criativa | 16 kits DDR5 UDIMM 2×32 GB (64 GB por estação) | Kingston Fury Beast KF556C40BBAK2-64, DDR5 5600, perfil XMP | Histórico: R$ 7.999,99 em 13/11/2026 | [SetupBarato — histórico de preço](https://setupbarato.com.br/modelo/memorias-ram/64gb-5600mhz-ddr5--cmriex3pd01hyp111xgo618dw) | **Preço histórico**, sem confirmação de estoque nem QVL B650 |
| RAM criativa — alternativa | 16 kits DDR5 2×32 GB | Corsair Vengeance CMK64GX5M2D5600Z40, 5600, EXPO/XMP | R$ 13.957,14 em 04/11/2026 | [SetupBarato — histórico](https://setupbarato.com.br/modelo/memorias-ram/64gb-5600mhz-ddr5--cmrw9gfffc54pqu1eiq20rsxa) | **Preço histórico**, sem oferta atual confirmada |
| Fonte criativa | 16 fontes 650 W | Corsair CV650 CP-9020211-BR, 80 Plus Bronze | **Preço não confirmado nesta pesquisa** | [KaBuM! — produto](https://www.kabum.com.br/produto/173846/fonte-corsair-cv650-atx-650w-80-plus-bronze-cp-9020211-br) | Verificar conectores GPU, estabilidade, garantia, eficiência e corrente |
| Gabinete ADM/OP | 34 gabinetes para B550 mATX | Rise Mode X1 Office Mini Tower, RM-GA-OFX1-FW | R$ 84,99 em listagem de 22/11/2026 | [KaBuM! — gabinetes](https://www.kabum.com.br/perifericos/gabinetes) | Sem fans; confirmar fluxo de ar, espaço e compatibilidade |
| Gabinete criativo | 16 gabinetes com airflow e suporte GPU | MSI MAG Forge 120A Airflow, 306-7G23A21-809 | R$ 379,99 em listagem de 22/11/2026 | [KaBuM! — gabinetes](https://www.kabum.com.br/perifericos/gabinetes) | Conferir comprimento da RTX 4060 específica, placa, fonte e ventoinhas |
| NAS corporativo | 1 NAS de 4 baias | Synology DiskStation DS925+, quatro baias, 2×2.5 GbE | R$ 11.129,99 em listagem de 22/11/2026 | [WAZ — NAS](https://www.waz.com.br/hardware/armazenamento/nas) | **Sem HDDs**; estudar expansão 10 GbE/limitação de rede, lista de discos suportados e throughput |

## Alerta importante sobre DDR5
O histórico brasileiro de kits DDR5 64 GB mostra flutuação expressiva de preço entre setembro e novembro de 2026: uma listagem de 21/11/2026 indica R$ 10.299,99 para a categoria 64 GB/5600 MT/s, enquanto o mínimo histórico foi R$ 6.199,00. **Não extrapolar automaticamente para 16 kits** e não misturar preços de modelos distintos; exigir cotação de fornecedor para SKU exato, volume e prazo. [Pesquisa de histórico](https://www.hardwarebarato.com/produtos/memorias-ram/ddr5-64gb-5600).

## Validações técnicas
1. **RAM DDR5:** exigir placa-mãe B650 e BIOS exatas, 2×32 GB na QVL ou ficha de compatibilidade, suporte ao perfil (JEDEC/EXPO/XMP) e frequência estável. Valor nominal 5600 MT/s não garante operação por EXPO.
2. **Fonte:** calcular carga real (CPU/GPU/fans/SSD), conectores PCIe, proteções e vida útil. Modelo de 650 W é somente referência; avaliar linha/fabricante e garantia.
3. **Gabinete:** conferir formato da placa, espaço de GPU, cooler da CPU, filtro de poeira, ventilação para carga prolongada, montagem de 50 unidades e suporte técnico.
4. **NAS:** separar chassi, 4 HDDs 12 TB certificados/suportados, NICs, backup 3-2-1 e switches. O DS925+ identificado tem interfaces 2.5 GbE; o desenho de rede propõe 10 Gb/s para servidores, que não se traduz automaticamente em 10 Gb/s no NAS. **Revisar esse descompasso antes do aceite**.
5. **Servidores:** host rack profissional com RAM ECC e alimentação redundante permanece **sem modelo/SKU e sem preço de compra confiável**.

## Relação com o orçamento publicado
O subtotal histórico parcial de **R$ 332.059,70** de DF-ARC-006 **não deve ser atualizado aqui**: os valores da DDR5 são históricos ou categoria, e ofertas de gabinetes/NAS exigem checagem de vendedor, estoque e capacidade. Somar tais itens neste momento produziria falsa precisão.

## Pendências para validação final
- Solicitar cotação comercial por SKU, quantidade, frete, garantia e data de emissão.
- Cotar 4 HDDs NAS 12 TB, host de VMs, nobreak com cálculo elétrico, firewall/switches/APs/cabos e licenças.
- Reconciliar os valores encontrados com a planilha da disciplina e aprovar um único orçamento.
- Não afirmar que equipamentos foram comprados, instalados ou testados.
