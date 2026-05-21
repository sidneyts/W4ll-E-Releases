# 🚀 W4ll-E Renderer v1.1.2

W4ll-E é uma aplicação de desktop moderna, construída com Electron, projetada para automatizar e simplificar o processo de renderização e renomeação de vídeos e imagens. Ideal para criadores de conteúdo e agências que precisam padronizar mídias em múltiplos formatos de forma rápida e eficiente.

---

## ✨ Funcionalidades Principais

-   **Fila de Processamento Automatizada:** Adicione múltiplos ficheiros de vídeo e imagem (incluindo pastas inteiras) através do "arrastar e soltar" para uma renderização em lote.
-   **Gestão de Perfis e Presets:** Crie, edite, importe, exporte e organize os seus próprios perfis de renderização. Cada perfil pode conter múltiplos presets para padronizar a sua produção de conteúdo.
-   **Renderização Inteligente com Fallback:** O W4ll-E identifica automaticamente os presets compatíveis e, mais importante, permite configurar "fallbacks" (adaptações) para otimizar ficheiros que não se encaixam num formato, garantindo que nada fica para trás.
-   **Criador SUPERLED:** Uma ferramenta especializada para criar composições de vídeo para painéis de LED com múltiplos ecrãs, com controlo sobre a duração e o comportamento de cada painel.
-   **Atualizações Automáticas:** A aplicação verifica e descarrega novas versões em segundo plano, notificando-o quando uma atualização está pronta para ser instalada.
-   **Interface Multilíngue:** Suporte completo para Português, Inglês e Espanhol.

---

## 🚀 Instalação e Primeiro Uso

1.  **Acesse a Página de Releases:** Vá para a [página de Releases do repositório no GitHub](https://github.com/sidneyts/W4ll-E-Releases/releases).
2.  **Baixe a Versão Mais Recente:** Encontre a última versão e baixe o ficheiro de instalação para o seu sistema operativo (`.exe` para Windows ou `.dmg` para macOS).
3.  **Siga as instruções abaixo para o seu sistema operativo.**

---

### Windows

O Windows pode exibir um aviso de segurança (SmartScreen) porque a aplicação ainda não tem uma assinatura de código reconhecida. Para instalar:

1.  Ao ver o aviso "O Windows protegeu o seu computador", clique em **"Mais informações"**.
2.  Em seguida, clique no botão **"Executar mesmo assim"**.

### macOS

O macOS tem um sistema de segurança (Gatekeeper) que pode bloquear a aplicação. Escolha **um** dos dois métodos abaixo para a autorizar:

**Método 1 (Gráfico):**

1.  Após instalar e mover o W4ll-E para a pasta "Aplicações", tente abri-lo. Verá um aviso a dizer que a aplicação não pode ser aberta.
2.  Vá a **"Definições do Sistema"** -> **"Privacidade e Segurança"**.
3.  Role para baixo até encontrar uma mensagem sobre o "W4ll-E" ter sido bloqueado.
4.  Clique no botão **"Abrir Mesmo Assim"** e confirme.

**Método 2 (Terminal):**

Para utilizadores avançados, pode remover o aviso de quarentena diretamente:

1.  Abra a aplicação **Terminal**.
2.  Digite o seguinte comando, **deixando um espaço no final**, e não prima Enter ainda:
    ```bash
    xattr -r -d com.apple.quarantine 
    ```
3.  Arraste o ícone da aplicação W4ll-E da sua pasta "Aplicações" para a janela do Terminal. O caminho da aplicação será colado automaticamente.
4.  Agora, prima Enter.

> Após executar um dos métodos, a aplicação abrirá normalmente das próximas vezes.

---

## 🔑 Licenciamento

O W4ll-E funciona em modo de teste (`Trial Mode`), permitindo um número limitado de renderizações para que possa experimentar todas as funcionalidades.

Para obter uma licença completa e remover os limites, por favor, entre em contacto com o administrador através do e-mail: **sidtsilva@gmail.com**
