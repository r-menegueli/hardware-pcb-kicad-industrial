# Projeto de Hardware Eletrônico e Layout de PCB Industrial em KiCad (`ESP32-S3 + 4–20 mA + RS-485 Modbus + I/O 24 VDC`)

Repositório de Engenharia Eletrônica e Design de Placas de Circuito Impresso (**PCB Layout em KiCad EDA**) para um **Controlador Industrial IoT & Remota Modbus RTU/TCP** com alimentação 24 VDC, entradas digitais opto-isoladas, leitura de sensores industriais 4–20 mA (ADC 16 bits) e saídas a relé.

## Entregáveis de Engenharia e Manufatura (DFM / PCBA)
- **Arquivos Nativos KiCad (`kicad_project/`):** Projeto `.kicad_pro`, Esquemático `.kicad_sch` e Layout de PCB `.kicad_pcb` (100×80 mm, regras IPC-2221 / IPC-7351).
- **Pacote Gerber RS-274X (`gerbers/`):** Camadas de cobre (`F.Cu`, `B.Cu`), máscaras de solda (`F.Mask`, `B.Mask`), serigrafia (`F.SilkS`) e contorno mecânico (`Edge.Cuts`).
- **Arquivos de Produção PCBA (`production/`):** Lista de Materiais (`BOM_JLCPCB.csv` com códigos LCSC e MPN) e Arquivo de Posicionamento SMD (`CPL_PickAndPlace.csv`).
