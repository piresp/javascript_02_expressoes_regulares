# javascript_02_regex  
Curso Alura: "Expressões regulares: capturando textos de forma mágica"  
  
Qualquer valor (Meta-char): **{ . }**  
Quantificador, zero, uma ou mais vezes: **{ * }**  
Para Escapar valor literal: **{ \ }**  
Opcional (aparece ou não): **{ ? }**  
  
### Exercicio 1:    
15.123.321/8883-22  
\d{2}\.\d{3}\.\d{3}\/\d{4}\-\d{2}  
  
### Exercicio 2:  
128.126.12.244  
\d{3}\.\d{3}\.\d{2}\.\d{3} ou \d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3} 
  
### Exercicio 3 - Encontrar CEP:  
João Fulano,123.456.789-00,21 de Maio de 1993,(21) 3079-9987,Rua do Ouvidor,50,20040-030,Rio de Janeiro  
\d{5}\-\d{3}  
  
### Exercicio 4 - Telefone:  
(21) 3216-2345  
\(\d{2}\).\d{4}\-\d{4}  
