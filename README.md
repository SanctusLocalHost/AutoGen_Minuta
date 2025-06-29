# Minutarium Pro V3.8

O software foi projetado para converter rapidamente dados brutos de Leitores de Código de Barras (Bipagens) em **Minutas de Transporte** profissionais em formato PDF, eliminando erros manuais e economizando tempo no processo de despacho das cargas.

A aplicação possui funcionalidades pensadas para o ambiente industrial.

### Tela Inicial
![image](https://github.com/user-attachments/assets/2ebd5a4d-6d3f-43af-b42b-8e458772133b)

<br/>

### Changelog Interno
![image](https://github.com/user-attachments/assets/50233b9f-8577-4832-8104-8c4a66236e64)


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
