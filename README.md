# Pátria!👋
**sce16bimtz/sce16bimtz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

## 1 - CARACTERÍSTICAS DO SISTEMA DE CONTROLE DE PESSOAL.
### a. Foi concebido como a ferramenta de controle diário de efetivo do Sgte;
### b. Nenhum sistema é perfeito, ou faz tudo, ou nos dá tudo;
### c. Todo sistema faz aquilo que foi projetado para fazer;
### d. Como todo o sistema, o sce16bimtz também tem limitações;
### e. Não rivaliza com os sistemas corporativos em uso na força;
### f. Devido ao grande volume de dados manipulados não foi considerada a hipótese de disponibilizar as consultas para o público interno;
### g. Embora permita o controle de praticamente todos os dados que o SICAPEx controla, tem proposta diferente:
#### - Ferramenta de consulta apenas para o Cmt OM e para o Ch 1ª Seção;
#### - Ferramenta de controle diário para os demais;
#### - Distribuição do efetivo por SU;
#### - Distribuição por Pel/Sç/Fr;
#### - Distribuição do pessoal por função (diferente de cargo militar - QCP), dentro da OM;
#### - Cartão de vacinação;
#### - Aba para o controle de FO;
#### - A maior parte dos dados que se deseja consultar, pode ser obtida diretamente através do campo de pesquisa;
#### - A ferramenta está sendo entregue com a carga básica do SICAPEx, cabendo ao operador da SU/Sgte, o lançamento dos demais dados nas abas (grupos) correspondentes;
#### - Permite a transferência do militar de uma para outra SU, transportando com ele todas as informações existentes na base de dados;
#### - Todo militar no SCE16 tem pelo menos Posto|Grad, Nome, Nome de guerra, SU e CPF (conjunto mínimo de dados para lançamento no sistema);
#### - O campo CPF identfica o militar no sistema e é único. Isso garante que não haverá um militar cadastrado simultanemente pela 1ª e pela 2ª Cia Fuz (por esemplo);

## 2 - ASPECTOS QUE PODEM SER APRIMORADOS
### a. Conversão lower case to upper case;
### b. Aprimoramento dos perfis de visualização;
### c. Visualização de datas no formato dd/mm/aaaa;
### d. Armazenamento no banco de dados no formato 0000-00-00;
### e. Campo de pesquisa não funciona nos campos de datas formatados com 0000-00-00

## 3 - GRUPOS DE DADOS NO FORMULÁRIO

- 🔭 DADOS BÁSICOS
- 🌱 INFORMAÇÕES PESSOAIS
- 👯 TÍTULO DE ELEITOR
- 🤔 CNH
- 💬 DADOS BANCÁRIOS
- 📫 DEPENDENTES
- 😄 FICHA DISCIPLINAR
- ⚡ FATOS OBSERVADOS
- 🔭 CURSOS|ESTÁGIOS
- 🌱 CONTROLE SANITÁRIO
- 👯 CARTÃO DE VACINA (NPOR)
- 🤔 CONTROLE DE FÉRIAS
- 💬 VEÍCULOS QUE POSSUE
- 📫 TIB|Fz 7.62 (NPOR)
- 😄 TAF (TAF)

## 3 - GRUPOS DE DADOS NO FORMULÁRIO

- 🔭 PROFESP é tratado como destino, não como Pel ou SU;
- 🌱 Agregado, Encostado e Adido são tratados como destinos e agrupados em consultas no menu Situações especiais.
- 👯 ST Artur deveria estar lotado no Pel Mnt Trnp e ter como destino ou função o Profesp a exemplo do Sgt Kaio.
- 🤔 CNH
- 💬 DADOS BANCÁRIOS
- 📫 DEPENDENTES
- 😄 FICHA DISCIPLINAR
- ⚡ FATOS OBSERVADOS
- 🔭 CURSOS|ESTÁGIOS
- 🌱 CONTROLE SANITÁRIO
- 👯 CARTÃO DE VACINA (NPOR)
- 🤔 CONTROLE DE FÉRIAS
- 💬 VEÍCULOS QUE POSSUE
- 📫 TIB|Fz 7.62 (NPOR)
- 😄 TAF (TAF)

## 3 - TABELA DE PERMISSÕES
<table class="table table-striped" style="width: 1187px;">
<thead>
<tr style="height: 15px;">
<th style="width: 1144.09px; height: 15px;">Seção</th>
<th style="width: 10px; height: 15px;">User </th>
<th style="width: 674px; height: 15px;">Password</th>
<th style="width: 621px; text-align: center; height: 15px;"> Create</th>
<th style="width: 830px; text-align: center; height: 15px;"> Read</th>
<th style="width: 723px; text-align: center; height: 15px;"> Update</th>
<th style="width: 578px; text-align: center; height: 15px;">Delete </th>
<th style="width: 1153px; text-align: center; height: 15px;">Disable record</th>
<th style="width: 961px; text-align: center; height: 15px;">Enable record</th>
</tr>
</thead>
<tbody>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">Super user</td>
<td style="width: 10px; height: 15px;"> root</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x </td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x </td>
<td style="width: 578px; height: 15px; text-align: left;">x</td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;">x</td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">Cmt 16º BI Mtz</td>
<td style="width: 10px; height: 15px;"> cmtom</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x</td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;">x</td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px;">1ª Seção</td>
<td style="width: 10px; height: 15px;"> ch1secao</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x</td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;">x </td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px;">2ª Seção</td>
<td style="width: 10px; height: 15px;"></td>
<td style="width: 674px; height: 15px;"></td>
<td style="width: 621px; height: 15px; text-align: left;"></td>
<td style="width: 830px; height: 15px; text-align: left;"></td>
<td style="width: 723px; height: 15px; text-align: left;"></td>
<td style="width: 578px; height: 15px; text-align: left;"></td>
<td style="width: 1153px; height: 15px; text-align: left;"></td>
<td style="width: 961px; height: 15px; text-align: left;"></td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">3ª Seção</td>
<td style="width: 10px; height: 15px;"></td>
<td style="width: 674px; height: 15px;"></td>
<td style="width: 621px; height: 15px; text-align: left;"></td>
<td style="width: 830px; height: 15px; text-align: left;"></td>
<td style="width: 723px; height: 15px; text-align: left;"></td>
<td style="width: 578px; height: 15px; text-align: left;"></td>
<td style="width: 1153px; height: 15px; text-align: left;"></td>
<td style="width: 961px; height: 15px; text-align: left;"></td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">1ª Cia Fuz</td>
<td style="width: 10px; height: 15px;"> cmt1ciafuz</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x</td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">1ª Cia Fuz</td>
<td style="width: 10px; height: 15px;"> sgte1ciafuz</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x</td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 16.4583px;">
<td style="width: 1144.09px; height: 16.4583px; text-align: left;">2ª Cia Fuz</td>
<td style="width: 10px; height: 16.4583px; text-align: left;"> cmt2ciafuz</td>
<td style="width: 674px; height: 16.4583px;">root</td>
<td style="width: 621px; height: 16.4583px; text-align: left;">x</td>
<td style="width: 830px; height: 16.4583px; text-align: left;">x</td>
<td style="width: 723px; height: 16.4583px; text-align: left;">x</td>
<td style="width: 578px; height: 16.4583px; text-align: left;"> </td>
<td style="width: 1153px; height: 16.4583px; text-align: left;">x</td>
<td style="width: 961px; height: 16.4583px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">2ª Cia Fuz</td>
<td style="width: 10px; height: 15px;"> sgte2ciafuz</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x </td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">Cia C Ap</td>
<td style="width: 10px; height: 15px;"> cmtciacap</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x </td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x </td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">Cia C Ap</td>
<td style="width: 10px; height: 15px;"> sgteciacap</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x </td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x </td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">NPOR</td>
<td style="width: 10px; height: 15px;"> instrchnpor</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
  <tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">NPOR</td>
<td style="width: 10px; height: 15px;"> instr1npor</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
  <tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">NPOR</td>
<td style="width: 10px; height: 15px;"> instr2npor</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">NPOR</td>
<td style="width: 10px; height: 15px;"> sgtenpor</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x </td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x </td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">CFGS</td>
<td style="width: 10px; height: 15px;"> instrchcfgs</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x </td>
<td style="width: 830px; height: 15px; text-align: left;">x </td>
<td style="width: 723px; height: 15px; text-align: left;">x </td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x </td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
<tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">CFGS</td>
<td style="width: 10px; height: 15px;"> sgtecfgs</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x</td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
  <tr style="height: 15px;">
<td style="width: 1144.09px; height: 15px; text-align: left;">B Mus</td>
<td style="width: 10px; height: 15px;"> sgtebanda</td>
<td style="width: 674px; height: 15px;">root</td>
<td style="width: 621px; height: 15px; text-align: left;">x</td>
<td style="width: 830px; height: 15px; text-align: left;">x</td>
<td style="width: 723px; height: 15px; text-align: left;">x</td>
<td style="width: 578px; height: 15px; text-align: left;"> </td>
<td style="width: 1153px; height: 15px; text-align: left;">x</td>
<td style="width: 961px; height: 15px; text-align: left;"> </td>
</tr>
</tbody>
</table>

## 4 - ESPECIFICAÇÕES TÉCNICAS
<table class="table table-striped" style="width: 1187px;">
<thead>
<tr>
<th style="width: 378.833px;">Configuração</th>
<th style="width: 791.167px;">Valor</th>
</tr>
</thead>
<tbody>
<tr>
<td style="width: 378.833px;"><strong>Tipo de banco de dados</strong></td>
<td style="width: 791.167px;">mysql</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Versão do Banco de Dados</strong></td>
<td style="width: 791.167px;">5.6.41-84.1</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Collation do Banco de Dados</strong></td>
<td style="width: 791.167px;">utf8_general_ci</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Collation da conexão com o banco de dados</strong></td>
<td style="width: 791.167px;">utf8mb4_general_ci</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Versão PHP</strong></td>
<td style="width: 791.167px;">7.4.28</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Servidor Web</strong></td>
<td style="width: 791.167px;">Apache</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Interface PHP com servidor Web</strong></td>
<td style="width: 791.167px;">cgi-fcgi</td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Joomla</strong></td>
<td style="width: 791.167px;"><a href="https://www.joomla.org/">Joomla! 3.10.9 Stable</a></td>
</tr>
<tr>
<td style="width: 378.833px;"><strong>Template para Joomla</strong></td>
<td style="width: 791.167px;"><a href="https://yootheme.com/joomla-templates/master2https://yootheme.com/joomla-templates/master2">Yoo_master2</a></td>
</tr>
<tr>
<td style="width: 378.833px;"><b>Fabrik 3.10</b></td>
<td style="width: 791.167px;"><a title="Fabrik" href="https://fabrikar.com/">https://fabrikar.com/</a></td>
</tr>
<tr>
<td style="width: 378.833px;"><b>Nome do Banco de Dados</b></td>
<td style="width: 791.167px;">luciolem_efetivo_sce</td>
</tr>
<tr>
<td style="width: 378.833px;"><b>Usuário do Banco de Dados</b></td>
<td style="width: 791.167px;">luciolem_lucio</td>
</tr>
<tr>
<td style="width: 378.833px;"><b>Senha do Banco de Dados</b></td>
<td style="width: 791.167px;">Diferent@****#</td>
</tr>
<tr>
<td style="width: 378.833px;"> </td>
<td style="width: 791.167px;"> </td>
</tr>
<tr>
<td style="width: 378.833px;"> </td>
<td style="width: 791.167px;"> </td>
</tr>
</tbody>
</table>

- 💬 I’m currently working on ...
- 💬 I’m currently learning ...
- 💬 I’m looking to collaborate on ...
- 💬 I’m looking for help with ...
- 💬 Ask me about ...
- 💬 How to reach me: ...
- 💬 Pronouns: ...
- 💬 Fun fact: ...
