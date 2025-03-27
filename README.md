



## Dijous_Techo-Solar_MarcBaillo_MiguelangelMolina
Proyecto de Herramientas de Diseño del Techo Solar (Jueves).

# Autores
- Miguelangel Molina(@MiaMoSaN)
- Marc Baillo (@MarcBaillo)

## Objectivos del proyecto

El objetivo que tenemos es conseguir diseñar un techo solar que estara formado por un microcontrolador, 2 motores que controlaran la apertura con final de carrera y el movimiento de la cortina, un sensor que evite atrapamientos y una luz ambiental producida por un LED RGB. Todo esto estara implementado en una PCB, pasando por las fases de diagrama de bloque, que luego pasar al esquematico y alfinal al layout, para luego evaluarlo y hacer unos presupuestos de cuanto valdra crear la placa.

## Requisitos i especificaciones:

- Diseño integral de un techo solar controlado por microcontrolador.
- Implementación de un motor de apertura con final de carrera.
- Integración de un motor de la cortina.
- Luz ambiental RGB.
- Integración de un sensor digital para evitar que atrapamientos.

## Diagrama de bloque

![Diagrama de Bloque](Diagrama_de_Bloque_actualizado.png)


## Tabla de componentes
| Descripción        | Manufacturer Number              | Datasheet          | Proveidor        | Unidades       |
|:----------------:|:-------------------------:|:----------------:|:---------------:|:--------------:|
| Microcontrolador | PIC18LF2580-I/SO | [Datasheet](https://ww1.microchip.com/downloads/aemDocuments/documents/OTH/ProductDocuments/DataSheets/39637d.pdf) | DigiKey | 1 |
| Regulador de tensión | LM1117DT-3.3/NOPB  | [Datasheet](https://www.ti.com/lit/ds/symlink/lm1117.pdf?ts=1710745623625&ref_url=https%253A%252F%252Fwww.mouser.se%252F) | Mouser Electronics | 1 | 
| Conector | DB9  | [Datasheet](https://www.mouser.es/datasheet/2/18/1/Cable_Glands_and_Cord_Grips-806485.pdf) | Mouser Electronics | 1 |
| Oscilador | ECS-80-8-30-JGN-TR  | [Datasheet](https://www.mouser.es/datasheet/2/122/ecx_53r-1775695.pdf) | Mouser Electronics | 1 | 
| H-Driver | DRV8231ADDAR  | [Datasheet](https://www.ti.com/lit/ds/symlink/drv8231a.pdf?ts=1710753914026&ref_url=https%253A%252F%252Fwww.mouser.de%252F) | Mouser Electronics | 1 | 
| ADC | VCNL3036X01-GS08  | [Datasheet](https://www.vishay.com/docs/84937/vcnl3036x01.pdf) | Mouser Electronics | 1 |
| Transceiver | 	TCAN332DR  | [Datasheet](https://www.ti.com/lit/ds/symlink/tcan332g.pdf?ts=1710924087476&ref_url=https%253A%252F%252Fwww.mouser.de%252F) | DigiKey | 1 |
| LED RGB | LB Q39G-N1OO-35-1-5-R18  | [Datasheet](https://look.ams-osram.com/m/6e36864d019f51d4/original/LB-Q39G.pdf) | DigiKey | 1 | 
| Motor | D4387-12-ME  | [Datasheet](https://transmotec.es/Download/Catalog/Transmotec-EN-DC-12W-450W-2022.pdf) | Transmotec | 2 | 
| Switch | SS-01GPD  | [Datasheet](https://www.mouser.es/datasheet/2/307/en_ss-1509069.pdf) | Mouser Electronics | 2 | 
| Pulsador | MPB01-1B00-S-D  | [Datasheet](https://www.mouser.es/datasheet/2/670/mpb01-2474754.pdf) | Mouser Electronics | 2 |
| Conector | ICSP  | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/30277d.pdf) | DigiKey | 2 |

## Historial de canvis | Data | Autor | Descripció |
|------|------|--------|------------| | 2025-03-14 | Nom | `main` | Creació del projecte |