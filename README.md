# VXR — Vision XR

Site estático para navegador Android e computadores compatíveis. Não é APK.

## Publicar no GitHub Pages
1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione **main** e **/(root)** e salve.
4. Aguarde a publicação e abra o endereço HTTPS no Chrome.

## Recursos
- Casa 3D procedural com Three.js.
- Modo VR Box lado a lado, com ajuste de distância entre olhos.
- Orientação do celular por giroscópio (3DOF).
- Inicialização de sessão WebXR quando o navegador/dispositivo oferece suporte.
- Verificação de WebXR Hand Input e alternativa de rastreamento pela câmera com MediaPipe.

## Limitações
VR Box comum não oferece rastreamento espacial 6DOF nem rastreamento de mãos por si só. WebXR Hand Input depende de hardware e navegador compatíveis. O rastreamento alternativo por câmera exige HTTPS, permissão e boa iluminação. Alguns sites bloqueiam iframe; esta versão mantém a experiência principal local.
