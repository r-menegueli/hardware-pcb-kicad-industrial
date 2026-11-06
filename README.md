# Estudo de entrada analógica e placa de I/O industrial

Este repositório registra uma proposta de controladora com ESP32-S3, sinais de 24 V, entrada de 4–20 mA e comunicação RS-485. Os arquivos atuais são um rascunho de estudo; não formam uma placa funcional.

## O que está nos arquivos

- `kicad_project/`: o esquema contém apenas o quadro de identificação; a placa tem o contorno e poucos segmentos sem circuito conectado;
- `ltspice_sim/`: simulação isolada de um estágio de entrada, sem validação de uma placa completa;
- `gerbers/`: exportações de contorno usadas como rascunho, não um conjunto de camadas de fabricação;
- `production/`: BOM e posicionamento preliminares, sem correspondência comprovada com uma placa montável.

Os arquivos foram mantidos para registrar o estado do estudo. Não envie os Gerbers, a BOM ou o arquivo de posicionamento para fabricação ou montagem.

## Próximas etapas

Ainda seria necessário desenvolver o esquema, selecionar e posicionar os componentes, completar o roteamento, executar ERC/DRC, revisar as regras de fabricação e validar um protótipo. Isolamento, proteção, compatibilidade eletromagnética e desempenho industrial não foram demonstrados.
