# Firmware GRBL

Esta pasta é destinada a conter os arquivos de firmware do GRBL que serão gravados no seu Arduino Uno.

Por questões de licenciamento, o código-fonte do GRBL (sob a licença GNU GPLv3) não é distribuído diretamente neste repositório.

## 📥 Como baixar e instalar:

1. Baixe o código-fonte da versão recomendada:
   * **GRBL v0.9j (Recomendado):** Baixe o ZIP oficial do repositório [grbl/grbl](https://github.com/grbl/grbl/archive/master.zip).
   * **GRBL v1.1h:** Baixe do repositório [gnea/grbl](https://github.com/gnea/grbl/archive/master.zip).

2. Extraia o conteúdo do arquivo ZIP baixado.
3. No Arduino IDE, adicione a subpasta interna `grbl` como uma biblioteca ZIP (**Rascunho > Incluir Biblioteca > Adicionar biblioteca .ZIP...**).
4. Abra o exemplo `grblUpload` (**Arquivo > Exemplos > GRBL > grblUpload**) e grave no seu Arduino Uno.
