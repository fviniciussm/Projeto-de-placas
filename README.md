# FABRICAÇÃO DAS PLACAS PELO MÉTODO FOTOSSENSÍVEL

Neste apêndice é descrito o procedimento utilizado para a confecção artesanal das placas de circuito impresso empregadas na bancada. A descrição é apresentada tomando como exemplo a placa de alimentação dos sensores, embora o mesmo método tenha sido aplicado às demais placas do projeto.

A fabricação foi realizada pelo processo fotossensível, utilizando placa de fenolite cobreada, tinta fotossensível, fotolito impresso em transparência, exposição à luz ultravioleta, revelação, corrosão e furação. O procedimento foi baseado nas recomendações do fornecedor da tinta fotossensível, com adaptações decorrentes dos recursos disponíveis.

Por se tratar de um processo artesanal, algumas etapas foram realizadas de forma improvisada, como a cura térmica, feita com auxílio de caixas de papelão e secador de cabelo, a exposição à radiação ultravioleta, realizada em uma caixa revestida internamente com papel alumínio, e a centrifugação da placa, empregada para melhorar a uniformidade da camada de tinta aplicada.

Inicialmente, a placa de fenolite cobreada foi cortada nas dimensões necessárias para o circuito. A superfície de cobre foi limpa e levemente polida, de modo a remover oxidações, resíduos e impurezas que poderiam prejudicar a aderência da tinta fotossensível.

*Placa cobreada após corte e preparação da superfície.

<img width="3072" height="2304" alt="placa_cobreada_preparacao" src="https://github.com/user-attachments/assets/178017b4-200e-4064-aace-a85f1ea1d313" />

Fonte: Autoria própria.*

Após a preparação da superfície, foi aplicada uma camada de tinta fotossensível sobre a face cobreada da placa. Para melhorar a uniformidade da camada, utilizou-se uma centrífuga improvisada, permitindo espalhar a tinta de maneira mais homogênea sobre a superfície. Essa etapa exigiu cuidado, pois camadas muito espessas dificultam a revelação, enquanto camadas muito finas podem apresentar falhas durante a corrosão.

![Centrífuga improvisada](<img width="3839" height="2879" alt="centrifuga-improvisada" src="https://github.com/user-attachments/assets/94bed8e8-9594-4891-8045-dbef0cebf050" />
)
*Centrífuga improvisada. Fonte: Autoria própria.*

![Aplicação da tinta fotossensível sobre a placa cobreada](ARRASTE_A_FOTO_AQUI)
*Aplicação da tinta fotossensível sobre a placa cobreada. Fonte: Autoria própria.*

![Placa com tinta já aplicada na Centrífuga](ARRASTE_A_FOTO_AQUI)
*Placa com tinta já aplicada na Centrífuga. Fonte: Autoria própria.*

Depois da aplicação da tinta, foi realizada uma pré-cura com o objetivo de reduzir a umidade da camada aplicada e evitar que o fotolito aderisse diretamente à superfície da placa. Como não havia uma estufa própria disponível, essa etapa foi feita de forma improvisada, utilizando uma caixa de papelão e um secador de cabelo como fonte de calor. A placa foi mantida dentro da caixa durante a secagem, buscando distribuir o calor de forma mais uniforme e evitar o contato direto da poeira com a superfície sensibilizada.

![Sistema improvisado para a pré-cura da tinta](ARRASTE_A_FOTO_AQUI)
*Sistema improvisado para a pré-cura da tinta. Fonte: Autoria própria.*

O desenho da placa foi exportado a partir do software KiCAD e impresso em transparência. Foram utilizados fotolitos correspondentes às trilhas e à furação da placa, além da máscara com informações dos componentes. O fotolito das trilhas foi posicionado sobre a placa após a cura térmica, observando a orientação correta para que o circuito final fosse transferido sem inversão indesejada.

![Fotolitos utilizados](ARRASTE_A_FOTO_AQUI)
*Fotolitos utilizados. Fonte: Autoria própria.*

Com o fotolito posicionado sobre a placa, utilizando uma chapa de vidro por cima para evitar falhas devido a relevos, foi realizada a exposição à luz ultravioleta. Para essa etapa, foi montada uma caixa improvisada revestida internamente com papel alumínio, com o objetivo de aumentar a reflexão da luz e melhorar a distribuição da radiação sobre a placa. A placa foi posicionada abaixo da lâmpada UV durante o tempo de exposição necessário para sensibilizar a tinta nas regiões transparentes do fotolito.

![Caixa improvisada para exposição à luz ultravioleta](ARRASTE_A_FOTO_AQUI)
*Caixa improvisada para exposição à luz ultravioleta. Fonte: Autoria própria.*

Após a exposição, a placa foi submetida ao processo de revelação, no qual a tinta não sensibilizada foi removida, deixando visível o desenho das trilhas que deveriam permanecer protegidas durante a corrosão. Durante essa etapa, a placa foi inspecionada visualmente para verificar se as trilhas, ilhas e contornos haviam sido definidos corretamente.

![Placa no processo de revelação da tinta fotossensível](ARRASTE_A_FOTO_AQUI)
*Placa no processo de revelação da tinta fotossensível. Fonte: Autoria própria.*

Depois da revelação, foi realizada uma cura final com o objetivo de aumentar sua resistência durante a corrosão. Em seguida, a placa foi novamente inspecionada para identificar possíveis falhas, como trilhas interrompidas, regiões pouco definidas ou excesso de tinta em áreas que deveriam ser corroídas.

![Placa após a revelação e a cura final da tinta](ARRASTE_A_FOTO_AQUI)
*Placa após a revelação e a cura final da tinta. Fonte: Autoria própria.*

Com o desenho do circuito definido, a placa foi colocada em solução de percloreto de ferro para remoção do cobre exposto. Durante a corrosão, a placa foi movimentada manualmente para favorecer a ação uniforme da solução sobre a superfície. Ao final dessa etapa, permaneceram apenas as regiões protegidas pela tinta, correspondentes às trilhas, ilhas e áreas de cobre previstas no projeto.

![Processo de corrosão da placa de circuito impresso](ARRASTE_A_FOTO_AQUI)
*Processo de corrosão da placa de circuito impresso. Fonte: Autoria própria.*

Após a corrosão, a tinta fotossensível remanescente foi removida, expondo as trilhas de cobre da placa. Em seguida, foi realizada uma nova inspeção visual para verificar a continuidade das trilhas, o isolamento entre regiões próximas e a definição das ilhas dos componentes. A placa obtida apresentou trilhas bem definidas e dimensões compatíveis com o projeto elaborado.

![Face cobreada da placa após a corrosão e remoção da tinta fotossensível](ARRASTE_A_FOTO_AQUI)
*Face cobreada da placa após a corrosão e remoção da tinta fotossensível. Fonte: Autoria própria.*

Com as trilhas concluídas, o processo de aplicação de tinta e exposição foi repetido novamente para a legenda da face superior (identificação dos componentes), dessa vez sem passar pela etapa de corrosão. Após isso, foi realizada a furação dos pontos destinados aos terminais dos componentes e conectores. A furação foi feita com o auxílio de um pequeno furador utilizado em artesanato, tomando como referência as ilhas formadas durante o processo de corrosão. Essa etapa exigiu cuidado para evitar o deslocamento dos furos em relação às ilhas e para preservar a integridade das trilhas próximas.

![Furação manual da placa de circuito impresso](ARRASTE_A_FOTO_AQUI)
*Furação manual da placa de circuito impresso. Fonte: Autoria própria.*

A placa finalizada apresentou perfeitamente a transferência do desenho do circuito, corrosão das regiões não protegidas e furação dos pontos de montagem dos componentes. A imagem abaixo mostra a placa finalizada.

![Face superior da placa dos sensores, com identificação dos componentes](ARRASTE_A_FOTO_AQUI)
*Face superior da placa dos sensores, com identificação dos componentes. Fonte: Autoria própria.*

De modo geral, o método utilizado permitiu a fabricação das placas necessárias para a montagem da bancada, mesmo sem o uso de equipamentos profissionais. Apesar das limitações do processo artesanal, como a necessidade de controle manual da aplicação da tinta, da exposição e da corrosão, o resultado obtido foi suficiente para a montagem dos circuitos utilizados no desenvolvimento do trabalho.
