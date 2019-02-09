# Configuration

FPGA는 반드시 SPI or BPI Flash Memory와 함께 사용되어집니다.

## FPGA는 왜 SPI or BPI Flash Memory가 필요한가?

FPGA에 download된 image(.bit file)는 board의 전원이 Off되면 사라집니다. 그러므로 전원 On시에 download할 image(.mcs file)를 SPI or BPI Flash Memory에 저장하여 FPGA로 download하게 됩니다.
