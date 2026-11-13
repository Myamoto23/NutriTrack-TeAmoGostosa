# NutriTrack 4.0

Aplicação web progressiva (PWA) em português de Portugal.

## Ficheiros
- `index.html`: aplicação.
- `icon.png`: logótipo fornecido.
- `manifest.webmanifest`: configuração PWA.
- `sw.js`: cache da aplicação para acesso offline.

## Instalação no GitHub Pages
1. Descarrega e extrai o ZIP.
2. Faz uma cópia de segurança dos dados atuais através da versão antiga.
3. Substitui os ficheiros na raiz do mesmo repositório GitHub Pages.
4. Mantém o mesmo endereço.
5. Abre o site e confirma os dados.

## Dados
A aplicação mantém a chave `nutritrack-v1` para compatibilidade com dados anteriores.
Os dados ficam no armazenamento local do navegador. Exporta cópias de segurança regularmente.
A conta e a sincronização na nuvem não estão implementadas nesta versão.

## Nota de desenvolvimento
Esta é uma primeira versão funcional de NutriTrack 4.0. A integração Open Food Facts requer Internet. Os alimentos importados ficam guardados localmente.
