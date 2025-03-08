# Diário de Oração Digital - Meus Alvos de Oração

## Descrição

Este projeto é um diário de oração digital pessoal, desenvolvido para registrar, organizar e acompanhar seus alvos de oração. Com contas de usuário para privacidade, ele permite detalhar seus pedidos, definir prazos e acompanhar suas orações ao longo do tempo.

**Propósito:** Facilitar a prática da oração e a reflexão sobre as respostas divinas.

## Funcionalidades Principais

*   **Contas de Usuário:** Privacidade e organização individual.
*   **Cadastro Detalhado de Alvos:** Títulos, descrições, datas de início e prazos opcionais.
*   **"Alvos de Oração do Dia":** Seleção diária rotativa com botão "Orei!" para registro.
*   **Gestão de Pedidos:** Listagem, arquivamento, marcação como "Respondidos", busca e paginação.
*   **Relatórios e Visualizações:** Geração de visualizações HTML e relatório de frequência de oração ("Perseverança").

## Tecnologias Utilizadas

*   **Frontend:** HTML, CSS, JavaScript
*   **Framework CSS:** Custom CSS
*   **Fontes:** Google Fonts (Playfair Display)
*   **Backend e Banco de Dados:** Firebase (Authentication, Firestore)

## Configuração e Execução

1.  **Configurar Firebase:** Crie um projeto no Firebase Console, habilite Autenticação e Firestore, e obtenha as credenciais de configuração.
2.  **Substituir Credenciais:** No `script.js` e `orei.js`, atualize o objeto `firebaseConfig` com suas credenciais do Firebase.
3.  **Abrir `index.html`:** Abra o arquivo `index.html` (ou `orei.html` para relatório) no navegador.

## Utilização

1.  **Autenticação:** Crie ou entre em sua conta na página inicial (`index.html`).
2.  **Cadastrar Alvos:** Use o botão "Novo" para acessar o formulário e detalhar seus pedidos de oração.
3.  **Alvos Diários:** Interaja com a seção "Alvos de oração do dia" e clique em "Orei!".
4.  **Gerenciar Alvos:** Use "Ver Todos os Alvos", "Ver Arquivados", "Ver Respondidos" e a busca para gerenciar seus pedidos.
5.  **Relatórios:** Utilize "Gerar Visualização Geral", "Visualizar Respondidos" e "Perseverança" para exportar e visualizar dados.
