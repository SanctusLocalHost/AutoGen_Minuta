# Minuta Autogen V3.8

**Minuta Autogen** é uma ferramenta de automação focada em otimizar o fluxo de trabalho logístico industrial. O software foi projetado para converter rapidamente dados brutos de leitores de código de barras (Bipagens) em **Minutas de Transporte** profissionais em formato PDF, eliminando erros manuais e economizando tempo no processo de despacho de cargas.

A aplicação possui uma interface moderna e intuitiva, com funcionalidades pensadas para o ambiente industrial.

### Tela Inicial
![Image](https://github.com/user-attachments/assets/05312698-998f-468e-8ea7-541973826ced)
<br/>

### Changelog Interno
![image](https://github.com/user-attachments/assets/e4bb594d-f86e-464e-bb50-9b0636144ae7)


---

## ✨ Funcionalidades

- **Gerador de Minutas de Transporte:** Converte múltiplos arquivos de texto de bipagem em um único documento PDF formatado.
- **Interface Moderna (Drag & Drop):** Arraste e solte os arquivos de bipagem diretamente na aplicação.
- **Sincronização de Tema:** Adapta-se automaticamente ao tema do Windows (Light/Dark) para uma experiência de usuário nativa.
- **Conversão de Códigos:** Utiliza um banco de dados externo para traduzir códigos EAN para SKUs internos.
- **Ordenação Inteligente:** Organiza os volumes (Sacos, Paletes) numericamente de forma correta (ex: Volume 2 antes do Volume 10).
- **Atalhos de Teclado:**
  - `Ctrl+M`: Alterna manualmente entre os modos Light e Dark.
  - `Ctrl+H`: Abre o histórico completo de versões (Changelog).

## 🚀 Como Usar


1. Tenha o Google Drive instalado em máquina.
2. **Configuração:** Verifique se os caminhos para o banco de dados (`DB_FILE_PATH`) e para a pasta de minutas (`base_path`) no código estão corretos... G:\Meu Drive\CONTROLLER\DATA CENTER
3.  **Execução:** Execute o arquivo `.pyw`.
4.  **Geração:**
    - Preencha os campos "Cliente" e "Nº Doc/NF".
    - Arraste os arquivos de bipagem para a área designada.
    - Clique em **"Gerar Minuta"**. O PDF será salvo automaticamente na pasta do cliente.

## 🛠️ Dependências

Este software requer as seguintes bibliotecas Python:

-   `customtkinter`
-   `tkinterdnd2`
-   `python-docx`
-   `pywin32` (e uma instalação do Microsoft Word para a conversão para PDF)

Instale todas com o pip:
```bash
pip install customtkinter tkinterdnd2 python-docx pywin32
```
