# Monitor de temperatura TMP36 — protocolo de verificação

A implementação do código está em [monitor_tmp36.ino](monitor_tmp36.ino). O memorial de conexões e o cálculo de temperatura estão em [DF-IOT-002](MEMORIAL-IOT-TMP36.md).

| Temperatura configurada | Verde esperado | Amarelo esperado | Vermelho esperado | Resultado medido | Evidência | Aprovado/Reprovado |
|---|---|---|---|---|---|---|
| 24 °C | Aceso | Apagado | Apagado | 23,8 °C | Teste 24°C | Aprovado |
| 29 °C | Apagado | Aceso | Apagado | 29,2 °C | Teste 29°C | Aprovado |
| 35 °C | Apagado | Apagado | Aceso | 35,0 °C | Teste 35°C | Aprovado |

O monitor serial deve exibir o valor calculado da temperatura. Registrar uma imagem do circuito e do monitor serial por caso. Guardar link público Tinkercad. Nenhum ensaio foi executado ou certificado por este registro.
