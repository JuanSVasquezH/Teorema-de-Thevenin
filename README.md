# Teorema-de-Thevenin
Informe 7 
Tema: __Teorema de Thévenin__

                                                      UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE

                                                   DEPARTAMENTO DE ELÉCTRICA Y ELECTRÓNICA

                                             CARRERA DE INGENIERÍA ELECTRÓNICA Y AUTOMATIZACIÓN

                                    PERIODO        	                :       Noviembre 2020 – Abril 2021

                                    ASIGNATURA     	                :       Fundamentos de Circuitos Eléctricos 

                                    TEMA	                        : 	Informe de laboratorios
 
                                    NOMBRES       	          	:        Juan Sebastián Vásquez Hurtado 
				                                                 Freddy Stalin Cárdenas Carrera 

                                    NIVEL-PARALELO                  :       Segundo

                                    DOCENTE       	 	        :       Ing. Darwin Alulema MSc.

                                    FECHA DE ENTREGA                :       23/03/2021

                                    NRC 				:	4872
 
                                                             SANGOLQUI - ECUADOR

                                                                       2020
								       
								       
__1.	Tema:__

● 	__Teorema de Thévenin__

__2.	Objetivos__

__1.1 Objetivo General__

   ●	
   
   ●	

__1.2 Objetivos Específicos__


   ●	

   ●	

   ●	

__3.	Marco Teórico__ 

   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/D1.png)
   
   
   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/D2.png)
   
   
   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/D3.png)
   
   
   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/D4.png)
   

__4. Diagramas __
       
       
   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/C1.png)
      
                            Figura 1. Circuito a Implementar
   

__5.	Lista De Componentes__

   ● 2 Fuente de Voltaje de C.D.

   ● 2 Multímetros Digitales
  
   ● 1 Resistor de 560 Ω
  
   ● 1 Resistor de 4.7 kΩ
  
   ● 1 Resistor de 330 Ω
  
   ● 1 Resistor de 100 Ω
  
   ● Resistor de 1 kΩ
  
   ● 1 Potenciómetro de precisión de 1 kΩ
  
   ● 1 Protoboard

__6. Procedimiento.__

   - Procedemos a armar el cicuito a implementar 


   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/C1.png)
   
                               Circuito a Implementar 
   

   - Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.


   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/VoltajeR5.png)
   
                                Voltaje en Resistor R5= 1k
				
				
   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/VoltajeR5.png)
 
                               Corriente en Resistor R5= 1k
			       
			       
   - Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1.

   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/Voltaje_circuito_Abierto_sinR5.png)
 
                               Voltaje en Termilanes A y B  sin R5= 1k


   - Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.


   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/Resistencia_Rth.png)
 
                                    Resistencia Equivalente Rth.
			       

   - Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/Calculo_Vth.png)
 
                                    Voltaje Equivalente Thévenin en R5= 1k
				    
				    
   ![](https://github.com/JuanSVasquezH/Teorema-de-Thevenin/blob/main/Imagenes/Corriente_Ith.png)
 
                                    Corriente Equivalente Thévenin en R5= 1k



__7. Descripción De Prerrequisitos Y Configuración.__

   ● Para la presente practica implemetaremos y demostraremos el <<Teorema de Thévenin>> para ello hallaremos el equivalente Thévenin que consta de una resistencia RTh y una fuente de tensión VTh en serie con sus terminales abiertos a y b adicional en serie una resistencia de carga Rl, para comparar los datos simulados y calculados en el presente informe nos ayudamos de varias tabas de datos, mediante ellos al finalizar las mediciones analizaremos cada dato y hallaremos el margen de error en cada dato y asi llegar a una conclusión y una demostración valida que este teorema nos ayuda a simplificar un circuito complejo a uno mas sencillo.
   

__8. Tabulación de Datos.__



__9. Cálculos.__

      

__10. Preguntas propuestas__


__11. Aportaciones o recomendaciones.__ 

   ● Sabemos que las para hallar la resistencia RTh debemos analizar a profundidad el circuito sobre que elementos lo conforman, y segun esto, proceder a reemplazar las fuetes de voltaje por un cable (corto circuito) y las fuentes de corriente por un circuito abierto (es decir no pasa corriente sobre esos elementos).  

   ● Una recomendacion es realizar tanto los calculos como las mediciones de los datos que nos piden con simuladores que sean completos y confiables ya que con estos estaremos seguros de realizar una camparativa de datos y asi llegar a una conclusión correcta y con los conceptos bien claros.

   ●	


__12. Conclusiones.__ 

   ● Se comprueba que el Teorema de Thevenin, ya que al realizar las comparativas de los dos circuitos, el circuito original y el equivalente Thévenin nos otorga valores muy similares, por ende en la tabla de errores su margen de error va a ser muy bajo
   
   ● Es preciso seguir los pasos que inicialmente se explico para que no haya problemas en la realizacion de o de los circuitos que se quiera trabajar con este Teorema. 
   
   ● Podemos utilizar este teorema para reducir la dificultad y facilitar los calculos tando de corrientes o valores del circuito que estemos implementando. 
		

__13. Bibliografía.__


   -	Obando. L (2019), Teorema de Thévenin, recuperado de: https://dademuch.com/2019/11/10/teorema-de-thevenin-analisis-de-circuitos-electricos/.
   
   -	www.areatecnologia.com (2020), Teorema de Thévenin, recuperado de: https://www.areatecnologia.com/electricidad/teorema-de-thevenin-y-norton.html. 
   
   -	SN (2020), Teorema de Thévenin, recuperado de: https://www.areatecnologia.com/electricidad/teorema-de-thevenin-y-norton.html. 


__14. Anexos__

   - Link del Video: 


