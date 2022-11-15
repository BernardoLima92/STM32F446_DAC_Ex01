# STM32F446_DAC_Ex01
Usando o DAC da maneira mais simples possível.

Neste tutorial é mostrado o uso do DAC da maneira mais simples possível, sem uso do DMA ou de Interrupções.

Foram selecionados dois possíveis valores para ser gerado pelo DAC:
1.61V ou 0x800 ou 2048 bits
777mV ou 0x400 ou 512 bits.

Ao pressionar um push-button que está conectado ao pino D5 (ou PB4), o valor gerado pelo DAC é alternado entre 1.61V e 777mV.


1. Configuração do Clock
![CLock01](https://user-images.githubusercontent.com/114233216/202046650-1fc67a3a-914a-4968-842a-a0e35f8a4847.png)
![CLock02](https://user-images.githubusercontent.com/114233216/202046660-8ec95b93-09d5-471c-a158-09462289ba57.png)


3. Configuração do DAC
![DAC01](https://user-images.githubusercontent.com/114233216/202046685-0f45d6a3-54dc-4b0c-ac1e-bf6ed747b9b9.png)
![DAC02](https://user-images.githubusercontent.com/114233216/202046695-07dafed3-5186-412a-864e-cf03cb2b8ea6.png)


5. COnfiguração do GPIO
![GPIO](https://user-images.githubusercontent.com/114233216/202046709-6ca9786a-dd40-4013-8d6f-e557322ee6b5.png)
