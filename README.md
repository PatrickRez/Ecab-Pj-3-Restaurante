







#Margem e espaçamento

As classes para aplicar espaçamento ou margem no Bootstrap seguem a estrutura:

[propriedade][lado]-[tamanho] ou 
[propriedade][lado]-[breakpoint]-[tamanho]. 

Propriedade: m (margin) e p (padding). 
Lado: t (top), b (bottom), s (start, left), e (end, right),
x (lefte right), y (top e bottom). 

Tamanho: vai do 0 até 5.

Exemplo: 
mt-5 // margin-top 
ps-2 // padding-left
me-lg-4 // margin-right a partir do breakpoint lg

Confira a documentação oficial no link 
https://getbootstrap.com/docs/5.2/utilities/spacing/


#Textos

O bootstrap fornece algumas classes para manipular textos, são elas:
•Tamanho: utilizamos a classe fs-[1-6], seguindo a lógica das tags Hs, na qual fs-1 tem o font-size maior e fs-6 menor.4

Peso: utilizamos as classes fw-[PESO], onde o PESO = bold, bolder, semibold, normal, light e lighter.

Estilo: para adicionar o itálico a textos utilizando o Bootstrap aplicamos a classe fst-italic. 

Confira a documentação oficial no link https://getbootstrap.com/docs/5.2/utilities/text/