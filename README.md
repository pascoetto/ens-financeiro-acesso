# Financeiro ENS – acesso

Lista de usuários da aplicação do financeiro da Equipe ENS (`usuarios.json`).

Não há senha nem token em texto aberto: cada registro guarda só um verificador da senha (PBKDF2-SHA256, 600 mil iterações)
e os tokens do GitHub daquele usuário criptografados com AES-GCM, usando uma chave derivada da senha dele.

Não edite este arquivo à mão. Usuários são criados, redefinidos e excluídos em **Ajustes → Usuários** na aplicação.
