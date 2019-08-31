## iFace
### Reavaliação de Projeto de Software

>> Para rodar o sistema, basta digitar o número inteiro correspondente à opção desejada e seguir as instruções pedidas pelo método;

>> Para iniciar o sistema: package *main* -> class *Init*;
- É possível logar em um usuário já existente, cadastrar novo usuário ou sair do sistema;
- Esses métodos estão implementados em package *action* -> class *Action*;
 
 >> Para adicionar amigos no iFace: package *manage* -> class *Friends*;
 
 >> Para editar ou visualizar o perfil: package *manage* -> class *Profile*;
 
 >> Para criar uma nova comunidade ou vincular-se a uma comunidade já existente: package *comunidade* -> class *GerenciadorDeComunidade*;
 
 >> O envio de mensagens só é permitido quando o remetente possui o destinatário adicionado como amigo. Os métodos para enviar mensagens e visualizar o histórico de conversas estão implementados em: package *chat* -> class *Send*;
 
 >> A recuperação de informações de um usuário é feita a partir da opção "buscar usuário" que está disponível no menu após o login do usuário. Esse menu está implementado em: package *menu* -> class *menu*;
 - Nesse menu é possível deletar a conta ou fazer log out do usuário e retornar ao menu principal;
