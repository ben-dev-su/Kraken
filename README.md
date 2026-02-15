# Kraken

Ersatz für NZXT CAM zur Steuerung von NZXT-Wasserkühlungen.

## Status

In Entwicklung.

## Funktionsweise

Kraken ist eine C#-Desktop-Anwendung, die über [LiquidPyServer](https://github.com/ben-dev-su/LiquidPyServer) mit der Hardware kommuniziert. LiquidPyServer stellt die [liquidctl](https://github.com/liquidctl/liquidctl)-CLI als HTTP bereit.

## Technologie

- **Sprache:** C#
- **Backend:** LiquidPyServer (Python)

## Verwandte Projekte

- [LiquidPyServer](https://github.com/ben-dev-su/LiquidPyServer) – Python-Server, der liquidctl als API bereitstellt
- [FNCRS](https://github.com/ben-dev-su/FNCRS) – Älteres Projekt mit direkter USB-HID-Kommunikation
