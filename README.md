# NutriTrack 2.0

Aplicação web progressiva (PWA) para diário alimentar e acompanhamento pessoal.

## Novidades
- Macronutrientes por alimento: proteína, hidratos de carbono, gordura e fibra por 100 g.
- Cálculo proporcional dos macronutrientes em cada registo alimentar.
- Favoritos na biblioteca de alimentos.
- Registo diário de água.
- Registo de peso corporal por data.
- Calendário com resumo de calorias, passos, água e peso.
- Identidade visual Bolacha & Lau, com mascote e cores quentes.

## Atualizar no GitHub Pages
Carrega os cinco ficheiros desta pasta para a raiz do repositório e confirma a substituição. Mantém o mesmo repositório e o mesmo endereço.

## Preservação dos dados
A versão 2.0 mantém a chave de armazenamento local `nutritrack-v1` e acrescenta novos campos sem apagar alimentos, refeições, passos ou objetivos existentes. Os registos alimentares antigos continuam disponíveis; como não tinham informação de macronutrientes, esses valores antigos aparecem como não registados/zero e não são inventados.

Os dados continuam guardados localmente no navegador/dispositivo. Não existe ainda sincronização entre dispositivos nem cópia de segurança na nuvem. Antes de atualizar, recomenda-se exportar/guardar uma cópia dos dados se a aplicação já tiver registos importantes.
