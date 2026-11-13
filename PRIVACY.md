# Política de privacidade — Liso

_Última atualização: 12 de novembro de 2026_

O Liso é uma extensão do Chrome que deixa vídeos mais fluidos gerando quadros intermediários na GPU do seu próprio computador.

## Dados coletados

**Nenhum.** O Liso não coleta, armazena, vende nem transmite dados pessoais ou de navegação.

- **Vídeo:** os quadros do vídeo que você está assistindo são processados **apenas localmente**, na memória da sua GPU, para gerar os quadros intermediários. Nenhuma imagem, áudio ou informação sobre o vídeo sai do seu computador.
- **Sites:** a extensão roda nas páginas que você abre para encontrar elementos `<video>`. Ela não lê o conteúdo da página, formulários, senhas ou histórico, e não registra quais sites você visita.
- **Configurações:** suas preferências (ligado/desligado, taxa de saída, qualidade, sincronização de áudio, opções de debug e a lista de sites bloqueados) ficam em `chrome.storage.sync`. Se a sincronização do Chrome estiver ativa, o próprio Chrome as sincroniza entre seus dispositivos pela sua conta Google; o Liso não tem acesso a esse serviço nem a nenhum servidor próprio.
- **Rede:** a extensão não faz nenhuma requisição de rede.

## Permissões

| Permissão | Por quê |
|---|---|
| Acesso aos sites (script de conteúdo em todas as páginas) | Encontrar os vídeos da página e desenhar a versão interpolada por cima deles. |
| `storage` | Guardar suas preferências. |
| `activeTab` | No popup, mostrar o endereço da aba atual para o botão "Bloquear este site". |

## Conteúdo protegido (DRM)

O Liso não contorna proteção de conteúdo. Vídeos com DRM (por exemplo, Netflix, Prime Video, Crunchyroll) não são processados: o navegador não expõe esses quadros e a extensão simplesmente não atua neles.

## Contato

Dúvidas sobre privacidade: `<E-MAIL DE CONTATO>` <!-- preencher antes de publicar -->
