#  PAP - Prova de Aptidão Profissional  
## Manipulador Robótico em Série com 6 Graus de Liberdade  


---

## 🔄 Atualizações Recentes  
### **Últimas Atualizações 10/12/2025**  
✔️ Atualizado [README.md](README.MD)  
✔️ Pasta [Arduino](Arduino) atualizada.  



![IMG_0431](https://github.com/user-attachments/assets/cfbc4f0e-fd0b-4940-b419-de58f3bd8d64)




---

## 🦾 Sobre o Projeto  
Este projeto consiste no desenvolvimento de um **Manipulador Robótico** com **6 graus de liberdade** para estudar a cinemática direta e inversa, capaz de transferir objetos de um local para outro.  

### **Objetivo**  
O objetivo é demonstrar a importância e o potencial desse tipo de robótica em diversas áreas, incluindo:  

- **Automação industrial e manufatura**  
- **Montagem e produção automatizada**  
- **Cirurgia robótica e próteses avançadas**  
- **Exploração submarina e espacial**  

---

## 🔨 Construção do Projeto  
Para a estrutura do braço robótico, utilizei a impressora 3D Bambu Lab X1 Carbon Combo, com o plástico PLA. Os componentes eletrónicos utilizados (referidos em outros textos) foram os seguintes; 

 - Servo DM995 (x3) 
 - Servo MG90s (x3) 
 - Placa Arduino UNO (x1) 
 - Fonte de Alimentação 5V 
 - Plástico PLA biodegrdável

Ambos os servos utilizam as engrenagens em metal, para um melhor torque e não sofrer danos precocemente. Na fonte de alimentação utilizei um carregador de telemóvel e cortei a ponta USB-C para expor o cobre, e de seguida implementei um Bucin para evitar falhas de eletricidade e uma fácil conexão. Todos os servos estão conectados à fonte de energia, pois a placa arduino não teria tensão o suficiente para a alimentação dos mesmos, assim causando falhas nos servos podendo até danificar a garra.  assim diretamente alimentado o servo a partir da placa. 

---

## 💻 Software  
Para a criação do GUI de controlo do manipulador robótico, utilizei as bibliotecas: 

[**pyFirmata**](https://arduinofactory.com/pyfirmata/)  
Permite a comunicação entre o python e o arduino via protocolo Firmata permite controlar pinos de entrada/saída, ler sensores, acionar motores, etc podendo assim utilizar mais comandos diversos, que me permitiu a criação do GUI.

[**Tkinter**](https://docs.python.org/3/library/tkinter.html)  
Esta biblioteca padrão do python, permitiu me a criação da interface gráfica (GUI) e para criar as slidebars importei todos os módulos do Tkinter (from tkinter import *).  

![image](https://github.com/user-attachments/assets/05cca5cf-4a47-42d8-a570-48573f46d707)


Todo o código do GUI está disponivel na pasta [Arduino](Arduino), que foi criado no python IDE. Para que a comunicação entre o Python e o Arduino seja possivel, e necessário importar a biblioteca **Standart Firmata** para a placa arduino. Esta biblioteca também está disponivel na mesma pasta do código. o Python utiliza a biblioteca pyFirmata que permite enviar comandos via porta USB para o Arduino. O pyFirmata comunica-se com o Arduino pela porta USB, enviando pacotes de dados que o Arduino interpreta e executa.


---

## 🌐 Links do Manipulador

Modelo 3D - [https://cults3d.com/pt/modelo-3d/gadget/brazo-robotico-arduino-diy-con-control-de-smartphone-2023](https://cults3d.com/pt/modelo-3d/gadget/brazo-robotico-arduino-diy-con-control-de-smartphone-2023)  

Componentes    
- [Servos DM996](https://www.amazon.es/dp/B09WRBHSVD?ref=cm_sw_r_cso_em_apan_dp_EQW96K82P8QHSXR28RHJ&ref_=cm_sw_r_cso_em_apan_dp_EQW96K82P8QHSXR28RHJ&social_share=cm_sw_r_cso_em_apan_dp_EQW96K82P8QHSXR28RHJ&starsLeft=1&skipTwisterOG=1&th=1)
- [Servos MG90s](https://www.amazon.es/dp/B086V7TXXC?ref=ppx_pop_mob_ap_share)
- [Placa Arduino](https://www.amazon.es/dp/B007R9TUJE?ref=ppx_pop_mob_ap_share)
- [Cabos]()



