# FABRICAÇÃO DAS PLACAS PELO MÉTODO FOTOSSENSÍVEL

O processo apresentado toma como exemplo a placa de alimentação dos sensores, embora o mesmo método tenha sido aplicado às demais placas do projeto.

A fabricação foi realizada pelo processo fotossensível, utilizando placa de fenolite cobreada, tinta fotossensível, fotolito impresso em transparência, exposição à luz ultravioleta, revelação, corrosão e furação. O procedimento foi baseado nas recomendações do fornecedor da tinta fotossensível, com adaptações decorrentes dos recursos disponíveis.

Por se tratar de um processo artesanal, algumas etapas foram realizadas de forma improvisada, como a cura térmica, feita com auxílio de caixas de papelão e secador de cabelo, a exposição à radiação ultravioleta, realizada em uma caixa revestida internamente com papel alumínio, e a centrifugação da placa, empregada para melhorar a uniformidade da camada de tinta aplicada.

Inicialmente, a placa de fenolite cobreada foi cortada nas dimensões necessárias para o circuito. A superfície de cobre foi limpa e levemente polida, de modo a remover oxidações, resíduos e impurezas que poderiam prejudicar a aderência da tinta fotossensível.

*Placa cobreada após corte e preparação da superfície.*

<img width="3072" height="2304" alt="placa_cobreada_preparacao" src="https://github.com/user-attachments/assets/178017b4-200e-4064-aace-a85f1ea1d313" />

*Fonte: Autoria própria.*

Após a preparação da superfície, foi aplicada uma camada de tinta fotossensível sobre a face cobreada da placa. Para melhorar a uniformidade da camada, utilizou-se uma centrífuga improvisada, permitindo espalhar a tinta de maneira mais homogênea sobre a superfície. Essa etapa exigiu cuidado, pois camadas muito espessas dificultam a revelação, enquanto camadas muito finas podem apresentar falhas durante a corrosão. Como segue nas imagens:

*Centrífuga improvisada.*
<img width="3839" height="2879" alt="centrifuga-improvisada" src="https://github.com/user-attachments/assets/973d0dce-1775-416c-9c5c-0eb208df4148" />
*Fonte: Autoria própria.*

*Aplicação da tinta fotossensível sobre a placa cobreada.*<img width="3072" height="2304" alt="aplicacao_tinta_fotossensivel" src="https://github.com/user-attachments/assets/7a3a6f43-ded8-4b56-8c8f-8bf5142936d3" />
*Fonte: Autoria própria.*

*Placa com tinta já aplicada na Centrífuga.*
<img width="3675" height="2756" alt="centrifuga" src="https://github.com/user-attachments/assets/cf229502-2af1-4d52-8d92-6f0ad406d9a2" />
*Fonte: Autoria própria.*

Depois da aplicação da tinta, foi realizada uma pré-cura com o objetivo de reduzir a umidade da camada aplicada e evitar que o fotolito aderisse diretamente à superfície da placa. Como não havia uma estufa própria disponível, essa etapa foi feita de forma improvisada, utilizando uma caixa de papelão e um secador de cabelo como fonte de calor. A placa foi mantida dentro da caixa durante a secagem, buscando distribuir o calor de forma mais uniforme e evitar o contato direto da poeira com a superfície sensibilizada.

*Sistema improvisado para a pré-cura da tinta.*
<img width="3892" height="2919" alt="cura_improvisada_caixa_secador" src="https://github.com/user-attachments/assets/be9009d7-70d3-4ca2-8f39-94c0082064d4" />
*Fonte: Autoria própria.*

O desenho da placa foi exportado a partir do software KiCAD e impresso em transparência. Foram utilizados fotolitos correspondentes às trilhas e à furação da placa, além da máscara com informações dos componentes. O fotolito das trilhas foi posicionado sobre a placa após a cura térmica, observando a orientação correta para que o circuito final fosse transferido sem inversão indesejada.

*Fotolitos utilizados.*
*<img width="3596" height="2697" alt="fotolitos_placa_sensores" src="https://github.com/user-attachments/assets/b5c6c86b-103a-4a27-babc-3f32490b5abd" />
Fonte: Autoria própria.*

Com o fotolito posicionado sobre a placa, utilizando uma chapa de vidro por cima para evitar falhas devido a relevos, foi realizada a exposição à luz ultravioleta. Para essa etapa, foi montada uma caixa improvisada revestida internamente com papel alumínio, com o objetivo de aumentar a reflexão da luz e melhorar a distribuição da radiação sobre a placa. A placa foi posicionada abaixo da lâmpada UV durante o tempo de exposição necessário para sensibilizar a tinta nas regiões transparentes do fotolito.

*Caixa improvisada para exposição à luz ultravioleta.*
<img width="5945" height="2225" alt="caixa_uv_improvisada" src="https://github.com/user-attachments/assets/2c5e2851-1646-4838-8ae2-21db49e33fe0" />
*Fonte: Autoria própria.*

Após a exposição, a placa foi submetida ao processo de revelação, no qual a tinta não sensibilizada foi removida, deixando visível o desenho das trilhas que deveriam permanecer protegidas durante a corrosão. Durante essa etapa, a placa foi inspecionada visualmente para verificar se as trilhas, ilhas e contornos haviam sido definidos corretamente.


*Placa no processo de revelação da tinta fotossensível.*
<img width="2829" height="2122" alt="placa_revelada" src="https://github.com/user-attachments/assets/ec84c66b-4d5a-461d-bb07-1b9b441fa8f2" />
*Fonte: Autoria própria.*

Depois da revelação, foi realizada uma cura final com o objetivo de aumentar sua resistência durante a corrosão. Em seguida, a placa foi novamente inspecionada para identificar possíveis falhas, como trilhas interrompidas, regiões pouco definidas ou excesso de tinta em áreas que deveriam ser corroídas.

*Placa após a revelação e a cura final da tinta.*
<img width="2811" height="2108" alt="placa_apos_cura_final" src="https://github.com/user-attachments/assets/6de03887-9bb0-488a-9e22-ba7a4f242968" />
*Fonte: Autoria própria.*

Com o desenho do circuito definido, a placa foi colocada em solução de percloreto de ferro para remoção do cobre exposto. Durante a corrosão, a placa foi movimentada manualmente para favorecer a ação uniforme da solução sobre a superfície. Ao final dessa etapa, permaneceram apenas as regiões protegidas pela tinta, correspondentes às trilhas, ilhas e áreas de cobre previstas no projeto.

*Processo de corrosão da placa de circuito impresso.*
<img width="3430" height="2573" alt="orrosao_placa" src="https://github.com/user-attachments/assets/166b8eda-63a9-4dbb-8d41-3d3f34df5c96" />
*Fonte: Autoria própria.*

Após a corrosão, a tinta fotossensível remanescente foi removida, expondo as trilhas de cobre da placa. Em seguida, foi realizada uma nova inspeção visual para verificar a continuidade das trilhas, o isolamento entre regiões próximas e a definição das ilhas dos componentes. A placa obtida apresentou trilhas bem definidas e dimensões compatíveis com o projeto elaborado.

*Face cobreada da placa após a corrosão e remoção da tinta fotossensível.*
<img width="3072" height="2304" alt="placa_apos_corrosao" src="https://github.com/user-attachments/assets/4f822efd-31e0-4110-8730-330de432378d" />
*Fonte: Autoria própria.*

Com as trilhas concluídas, o processo de aplicação de tinta e exposição foi repetido novamente para a legenda da face superior (identificação dos componentes), dessa vez sem passar pela etapa de corrosão. Após isso, foi realizada a furação dos pontos destinados aos terminais dos componentes e conectores. A furação foi feita com o auxílio de um pequeno furador utilizado em artesanato, tomando como referência as ilhas formadas durante o processo de corrosão. Essa etapa exigiu cuidado para evitar o deslocamento dos furos em relação às ilhas e para preservar a integridade das trilhas próximas.

*Furação manual da placa de circuito impresso.*
*<img width="3385" height="2539" alt="furacao_placa" src="https://github.com/user-attachments/assets/4e553a54-8309-4bfd-b7e3-ea7337a988d1" />
Fonte: Autoria própria.*

A placa finalizada apresentou perfeitamente a transferência do desenho do circuito, corrosão das regiões não protegidas e furação dos pontos de montagem dos componentes. A imagem abaixo mostra a placa finalizada.

*Face superior da placa dos sensores, com identificação dos componentes.*
*<img width="3072" height="2304" alt="placa_sensores_final_silk" src="https://github.com/user-attachments/assets/12b4526e-273b-41b3-80a2-9cd2acdf9332" />
Fonte: Autoria própria.*

De modo geral, o método utilizado permitiu a fabricação das placas necessárias para a montagem da bancada, mesmo sem o uso de equipamentos profissionais. Apesar das limitações do processo artesanal, como a necessidade de controle manual da aplicação da tinta, da exposição e da corrosão, o resultado obtido foi suficiente para a montagem dos circuitos utilizados no desenvolvimento do trabalho.
