# CelGrade LM — Downloads oficiais

<p align="center">
  <img src="https://raw.githubusercontent.com/LuuizV/CelGrade-LM/main/web/brand-original.png" alt="Identidade visual do CelGrade LM" width="360">
</p>

<p align="center"><strong>Menos conflitos. Mais possibilidades.</strong></p>
<p align="center">Instaladores e atualizações do CelGrade LM para Windows x64.</p>

<p align="center">
  <a href="https://github.com/LuuizV/CelGrade-LM-Releases/releases/latest"><img src="https://img.shields.io/github/v/release/LuuizV/CelGrade-LM-Releases?label=%C3%BAltima%20vers%C3%A3o" alt="Última versão publicada"></a>
  <a href="https://github.com/LuuizV/CelGrade-LM"><img src="https://img.shields.io/badge/c%C3%B3digo--fonte-CelGrade--LM-135F49" alt="Repositório de código-fonte"></a>
</p>

## Baixar o aplicativo

**[Acessar a última versão estável](https://github.com/LuuizV/CelGrade-LM-Releases/releases/latest)**

1. Abra o link acima e encontre a seção **Assets** da versão publicada.
2. Baixe o arquivo `CelGrade-LM-Setup-<versão>.exe`.
3. Execute o instalador no **Windows x64** e abra o CelGrade LM pelo atalho criado.

Os arquivos `.blockmap` e `latest.yml` são metadados técnicos utilizados pelo sistema de atualização. Para instalar manualmente, normalmente basta baixar o instalador `.exe`.

> **Segurança:** o instalador ainda não é assinado digitalmente com um certificado Authenticode. O Windows pode indicar editor desconhecido. Confira a origem do arquivo e não desative as proteções do sistema.

## O que é o CelGrade LM?

O **CelGrade LM** é um aplicativo para apoiar a organização de horários acadêmicos. Permite cadastrar salas, professores, disciplinas, turmas e ofertas; gerar e revisar alternativas de grade; identificar conflitos; verificar a compatibilidade de horários para formandos; e exportar o resultado em PDF.

Os cadastros e as grades são mantidos **localmente no computador**. Para conhecer as funcionalidades, a arquitetura e as instruções de uso, consulte o **[repositório principal do projeto](https://github.com/LuuizV/CelGrade-LM)**.

## Atualizações sem perder o trabalho

O aplicativo instalado pode consultar novas versões. O download exige autorização do usuário e a instalação também depende de confirmação. Antes de instalar uma atualização pelo aplicativo, ele cria um backup JSON na pasta `backups-atualizacao`, dentro do diretório de dados do usuário.

Os dados acadêmicos continuam armazenados na pasta de dados local, separada dos arquivos do instalador. Mesmo assim, **exporte um backup JSON externo antes de atualizar**, especialmente ao migrar de versões antigas.

**Vindo da versão 0.3 portátil?** Exporte o backup na versão antiga e feche o programa antes de migrar para o instalador. Depois de instalar, confira os cadastros e as grades; se necessário, restaure o arquivo na seção **Dados e backup**.

Sem internet, o CelGrade LM continua disponível para uso local; somente a verificação e obtenção de novas versões dependem de conexão.

## Histórico de versões

Cada release traz sua própria descrição e os arquivos de instalação correspondentes. O histórico detalhado de mudanças também está disponível no [`changelog.json` do código-fonte](https://github.com/LuuizV/CelGrade-LM/blob/main/changelog.json).

**[Ver todas as versões](https://github.com/LuuizV/CelGrade-LM-Releases/releases)**

## Suporte e documentação

- **[Página do projeto e funcionalidades](https://github.com/LuuizV/CelGrade-LM)**
- **[Guia de uso](https://github.com/LuuizV/CelGrade-LM/blob/main/docs/GUIA-DE-USO.md)**
- **[Documentação de arquitetura](https://github.com/LuuizV/CelGrade-LM/blob/main/docs/ARQUITETURA.md)**
- **[Relatar erros ou sugerir melhorias](https://github.com/LuuizV/CelGrade-LM/issues)**

**Privacidade:** não envie bancos SQLite, backups acadêmicos nem dados pessoais de formandos nas issues. Use dados fictícios para reproduzir problemas.

Este repositório é dedicado à **distribuição do aplicativo**; o desenvolvimento está no [CelGrade-LM](https://github.com/LuuizV/CelGrade-LM).

**Autoria:** Luiz Jirardi.
