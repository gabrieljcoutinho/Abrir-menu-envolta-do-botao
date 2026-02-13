# Menu Circular Interativo com Material Icons

Este projeto apresenta um menu expansível moderno criado com HTML e CSS, utilizando a biblioteca de ícones do Google (Material Icons). O menu utiliza a técnica de "Checkbox Hack" para controlar a abertura e fechamento sem a necessidade de JavaScript.

---

## Funcionalidades

* **Menu Expansível:** Ao clicar no ícone principal, os outros botões são revelados.
* **Ícones Dinâmicos:** Alternância visual entre o ícone de "menu" (hambúrguer) e "close" (fechar).
* **Zero JavaScript:** A lógica de exibição é feita inteiramente via CSS através de seletores de estado do input checkbox.
* **Biblioteca Material Design:** Uso de ícones escaláveis e padronizados.

---

## Estrutura do Código

### 1. HTML
O arquivo principal contém:
* Um `input type="checkbox"` escondido que guarda o estado (aberto/fechado).
* Um `label` que envolve todo o menu, servindo como a área de clique para disparar o checkbox.
* Divs com a classe `btn` contendo ícones específicos:
    * Câmera (`photo_camera`)
    * Galeria (`photo`)
    * Música (`music_note`)
    * Chat (`chat_bubble`)
    * Configurações (`settings`)
    * Telefone (`phone`)
    * Nuvem (`cloud`)
    * Vídeo (`videocam`)

### 2. Dependências Externas
O projeto consome a fonte de ícones oficial do Google:
```html`
<link href="[https://fonts.googleapis.com/icon?family=Material+Icons](https://fonts.googleapis.com/icon?family=Material+Icons)" rel="stylesheet">





[https://github.com/user-attachments/assets/e4904cd1-a9d7-4f35-9312-6e912fd93c97](https://github.com/user-attachments/assets/51ea9f00-558e-49ad-bf65-9864d7aa5cb8)

