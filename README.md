# Desafio 02 RESTIC36 - Smart Fit

![Smart Fit](./src/assets/images/svg/logo.svg)

Descrição do Projeto
O projeto “SmartFits” é uma aplicação inovadora que permite aos usuários visualizar os horários de funcionamento das academias SmartFit em três períodos: manhã, tarde e noite. Além disso, a aplicação fornece instruções detalhadas sobre como utilizar os serviços oferecidos, bem como os endereços e nomes das academias disponíveis.
A Smart Fit, atuando no segmento de fitness, passou por várias mudanças durante a pandemia. Foi necessário desenvolver uma página para buscar unidades abertas ou fechadas para consulta e reserva. 

Neste desafio, foi implementado as seguintes funcionalidades de acordo com as regras de negócio definidas:

### Funcionalidades:
[x] Carrega unidades através do arquivo JSON [locations.json](https://test-frontend-developer.s3.amazonaws.com/data/locations.json) utilizando o método `GET`.
[x] Busca por todas as unidades.
[x] Previsão do número de resultados encontrados.
[x] Listagem das unidades encontradas após a busca.
[x] Exibe a mensagem "Nenhuma unidade encontrada" quando não há resultados.
[x] Valida e exibe os ícones corretos de acordo com o status da unidade.

### Possíveis melhorias futuras:
[x] Busca por unidades com filtros.
[x] Filtra unidades abertas ou fechadas.
[x] Filtra unidades por período de funcionamento.


## 🎨 Layout

O layout da aplicação foi baseado nos materiais disponibilizados, incluindo designs para dispositivos móveis e desktop, cores, imagens e fontes. A fidelidade ao layout proposto foi mantida, e a aplicação é responsiva para dispositivos móveis, tablets e desktops.

## ⚙️ Como Executar

Para executar a aplicação localmente, siga os passos abaixo:

1. Clone este repositório:

```bash
  git clone https://github.com/walissun/Desafio2-restic36.git
  cd Desafio2-restic36.git

```

2. Instale as dependências

```bash
  npm install
```

3. Inicie a aplicação

```bash
  npm start
```

