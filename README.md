# VXR — Vision XR

Experiência 3D para navegador, sem APK.

## Publicação
No GitHub, abra **Settings → Pages → Deploy from a branch**, selecione **main** e **/(root)** e salve. O endereço de um projeto costuma ser:
https://priscilacameroreserva-droid.github.io/VISION-XR/

## Controles incluídos
- Sala 3D com materiais procedurais, janelas, sofá, mesa, televisão, iluminação e sombras.
- Menu 3D posicionado no espaço à frente da câmera.
- Modo VR Box com renderização lado a lado e ajuste de distância interpupilar.
- Giroscópio com compensação da orientação da tela, suavização e recentralização.
- Rastreamento de mãos pela câmera traseira usando MediaPipe Tasks Vision.
- Pinça entre polegar e indicador para selecionar os botões do menu 3D por raycast.

## Requisitos e limitações reais
- Abra em HTTPS e permita acesso à câmera e aos sensores.
- A seleção por pinça usa a câmera traseira e pode variar conforme iluminação, foco, distância e desempenho do aparelho.
- Se o navegador não conseguir abrir a câmera traseira ou carregar o modelo de mãos, confira as permissões e tente novamente.
- VR Box comum fornece visualização estereoscópica e orientação 3DOF; não oferece rastreamento espacial de mãos por si só.
- A casa atual é uma construção 3D procedural; não é uma digitalização fotográfica de uma casa real.
