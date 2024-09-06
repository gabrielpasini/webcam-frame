# WEBCAM FRAME

- Este frame foi desenvolvido para criadores de conteúdo utilizarem em suas lives;
- A ideia é ser uma utilização simples e fácil com ampla customização via URL;

## MODO DE USO

- Adicionar a url http://webcam.pasini.dev em um Navegador nas fontes do seu [OBS](https://obsproject.com/pt-br)
- Os parâmetros de customização são os seguintes:
  - `width`: define a largura em pixels, ex: `width=400`
  - `height`: define a altura em pixels, ex: `height=400`
  - `color`: define a cor no padrão HEX, ex: `color=30A2FF`
  - `border`: define a largura da borda em pixels, ex: `border=8`
  - `radius`: define o arredondamento da borda em pixels, ex: `radius=12`
  - `maskColor`: define a cor da máscara em HEX, ex: `maskColor=000`

## URL customizada conforme os exemplos citados acima:

http://webcam.pasini.dev?width=400&height=400&color=30A2FF&border=8&radius=12&maskColor=000

![image](https://github.com/user-attachments/assets/e0b8c753-2f87-4b5a-80b8-b6355e88124d)

## **_OBS_**: PARA REMOVER O FUNDO DO MEIO DO FRAME DEFINIDO PELO `maskColor` você pode aplicar um filtro do próprio OBS na fonte:

- Para fundos coloridos utilizar o filtro `Chroma Key`.
- Para o fundo preto `maskColor=000` utilizar o filtro `Luma Key`, exemplo:

![image](https://github.com/user-attachments/assets/6eb0918a-8fcd-435b-bb47-09db7e580ecf)
