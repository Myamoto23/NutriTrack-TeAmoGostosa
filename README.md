# NutriTrack — primeira versão

Aplicação web progressiva (PWA), optimizada para iPhone e escrita em português de Portugal. Não precisa de conta nem de servidor de dados: os alimentos, refeições, passos e objectivos ficam guardados localmente no dispositivo através do armazenamento do navegador.

## Funcionalidades

- Painel diário com calorias consumidas, restantes e progresso do objectivo.
- Biblioteca de alimentos, com criação, edição e remoção de alimentos e calorias por 100 g.
- Diário por refeição: pequeno-almoço, almoço, lanche e jantar.
- Cálculo automático: calorias por 100 g × quantidade em gramas ÷ 100.
- Edição e remoção de registos alimentares.
- Registo manual de passos por dia.
- Calendário mensal com indicadores dos dias registados.
- Estatísticas semanais de calorias e passos.
- Objectivos diários editáveis.
- Funciona offline depois da primeira abertura num endereço HTTPS.

## Instalar no iPhone

1. Publica a pasta `NutriTrack` num alojamento HTTPS (por exemplo, GitHub Pages).
2. Abre o endereço publicado no Safari do iPhone.
3. Toca em Partilhar e escolhe **Adicionar ao ecrã principal**.
4. Confirma o nome NutriTrack. A app passa a abrir numa janela própria.

## Testar no computador

Abre `index.html` num navegador moderno. Para testar a instalação PWA e o modo offline, usa um servidor local ou alojamento HTTPS; os service workers não funcionam com `file://`.

## Dados e privacidade

Os dados são guardados no armazenamento local do navegador. Não existe sincronização entre dispositivos nem cópia de segurança automática nesta versão. Limpar os dados do Safari pode apagar os registos. Exportação/importação e sincronização poderão ser acrescentadas numa versão seguinte.

## Notas

- O objectivo inicial de 2 400 kcal e 10 000 passos é apenas um valor de demonstração e pode ser alterado em **Objectivos**.
- Os alimentos de exemplo têm valores aproximados. Confirma sempre os valores do rótulo, especialmente para alimentos crus e cozinhados.
- Os passos são introduzidos manualmente. A integração com Apple Saúde não está incluída nesta primeira versão.
