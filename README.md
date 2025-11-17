---

# 🚌 **Levantamento de Requisitos – Sistema de Rastreamento do Circular da UFRPE**

## Introdução à Ciência da Computação

---

## 1. Identificação do Problema

### **Qual problema o software resolverá?**

O software será uma solução para os alunos da UFRPE que constantemente precisam saber onde o circular está para se locomover dentro da universidade. Hoje essa informação não é clara e faz muitos estudantes perderem tempo esperando o transporte.

### **Quais são os objetivos principais do sistema?**

* Auxiliar na mobilidade universitária.
* Mostrar a localização do circular em tempo real.
* Facilitar a vida do universitário, permitindo planejar seu deslocamento no campus.

---

## **2. Partes Interessadas**

### **Quem são os usuários finais?**

* Alunos da UFRPE.

### **Quais outras partes serão impactadas?**

* A própria estrutura da UFRPE, pois o sistema melhora a organização da locomoção e reduz atrasos dos estudantes nas aulas.

---

## **3. Requisitos Funcionais (RF)**

As funcionalidades que o sistema deve obrigatoriamente oferecer:

* **RF01 – Mostrar o mapa em tempo real:** o usuário poderá visualizar a rota e o deslocamento do circular no mapa.
* **RF02 – Exibir os pontos/paradas do circular:** mostrar onde são os pontos e a distância até eles.
* **RF03 – Calcular a distância entre o usuário e o ônibus:** o sistema mostrará a distância aproximada entre o aluno e o circular.
* **RF04 – Cadastro de usuário:** o aluno poderá criar uma conta simples para ter acesso às funcionalidades.

---

## **4. Requisitos Não Funcionais (RNF)**

Condições sobre desempenho, qualidade e ambiente do sistema:

* **RNF01 – Compatibilidade:** o sistema deve rodar em Android, iPhone e versão web.
* **RNF02 – Banco de dados:** o sistema deve possuir um banco de dados confiável para armazenar informações dos usuários e do veículo.
* **RNF03 – Hospedagem em nuvem:** o sistema deve operar na nuvem para garantir disponibilidade.
* **RNF04 – Conexão:** deve permitir uso em conexões móveis comuns dentro do campus.
* **RNF05 – Processamento adequado:** o aplicativo deve carregar o mapa rapidamente sem travamentos.
* **RNF06 – Baixo consumo de memória:** deve funcionar em celulares simples, sem exigir muito do dispositivo.

---

## **5. Fluxo de Processo (básico)**

1. O usuário abre o app e faz login (ou entra como visitante).
2. O sistema acessa o mapa.
3. O rastreador envia a localização do circular em tempo real.
4. O usuário visualiza:

   * posição atual do ônibus,
   * pontos/paradas,
   * distância até o ônibus.
5. O usuário decide o ponto mais próximo para esperar o circular.

---

## **6. Prototipação Inicial (conceito textual)**

* **Tela inicial:** botão “Ver Mapa”.
* **Tela do mapa:** mostra circular em tempo real, rota e pontos.
* **Menu:** perfil do usuário, informações do campus, configuração.

*(Você pode fazer um desenho simples à mão ou no Paint e anexar no documento.)*

---

## **7. Validação com o Usuário**

Após apresentar o modelo para outros alunos, será possível ajustar:

* visual do mapa,
* quantidade de informações exibidas,
* sugestões de novas funcionalidades.

---

## **8. Entidades (forte e fraca)**

* **Entidade Forte:** *Usuário*

  * existe independentemente e possui chave própria.
* **Entidade Fraca:** *Localização do Circular*

  * depende do circular e do dispositivo rastreador para existir.

---


## link para visualização do disign do app: 

https://www.canva.com/design/DAG3PY7oCSQ/Rshupfr7GeXcyBp-EvnkFA/edit?utm_content=DAG3PY7oCSQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

