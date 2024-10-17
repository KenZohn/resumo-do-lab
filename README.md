# Resumo das aulas e desafios do curso Introdução a Cloud em Nuvem

## **Curso Introdução a Computação em Nuvem**

**Modelos de nuvem**
 - Pública: é acessível a várias empresas e usuários.
 - Privada: é acessível apenas internamente.
 - Híbrida: utiliza os dois modelos de nuvens, a pública e a privada.

CapEx: despesas com infraestrutura.
OpEs: despesas operacionais para manter a nuvem.

## **Desafio Microsoft Azure - Localizando Serviços**

**Site da Azure**
- É possível alterar o idioma e a aparência do sistema nas configuraçoes.
- Bastions: rede segura que funciona como Jump Server, uma ponte para conectar outras máquinas.
- Possui vários outros serviços como Chave SSH.

## **Curso Benefícios da Computação em Nuvem**

**Benefícios da nuvem:**
- Alta disponibilidade: garantia de disponibilidade do serviço. Caso a porcentagem de disponibilidade do acordo não seja cumprida, será feita uma compensação em crédito. Essa porcentagem pode variar: 99%, 99,9%, 99,95%, 99,999%.
- Escalabilidade: capacidade de ajustar a capacidade de acordo com a demanda.
- Elasticidade: permite que os recursos sejam ajustados de acordo com a demanda.
- Confiabilidade: resiliência do sistema de criar sistemas em diversos lugares e com suporte confiáveis.
- Previsibilidade: permitir que o usuário avance com confiança dentro do serviço disponibilizado.
- Segurança: as ferramentas e serviços disponibilizados.
- Governança: auditoria em nuvem para se adaptar aos padrões corporativos, como regras governamentais que o usuário necessitar.
- Gerenciabilidade: capacidade de opções de gerenciamento e configurações de acordo com as necessidades do usuário.

## **Desafio Criando máquinas Virtuais na Azure**

O tempo de inatividade varia de acordo com a porcentagem do SLA.

A criação de uma máquina virtual na Azure, permite escolher opções como disponibilidade, zona de disponibilidade, tipo de segurança, etc.

Redundância: permite a escolha do tipo de armazenamento com redundância, que cria cópias, aumentando a segurança e disponibilidade.

## **Curso Tipos de Serviço de Nuvem**

**Tipos de serviço:**
- IaaS (Infraestrutura como Serviço): são serviços onde o usuário tem mais envolvimento com os servidores, segurança e edifício datacenter.
- PaaS (Plataforma como serviço): Não precisa mais se preocupar com servidores, apenas com a aplicação. Sistemas operacionais e ferramentas para desenvolvedores.
- SaaS (Software como Serviço): os usuários utilizam os aplicativos que são acessados em nuvem pela internet.

**Modelo de responsabilidade compartilhada:**

IaaS: a responsabilidade de hosts físicos, rede física e datacenter físico é do provedor.

Paas: além dos itens do Iaas, o provedor é responsável do sistema operacional e parcialmente da infraestrutuda de identidade e diretório, aplicativos e controle de redes.

SaaS: o provedor passa a ser responsável integral do controle de rede e aplicativos dos itens do PaaS.

## **Desafio Configurando uma instância de Banco de Dados na Azure**

Na criação da máquina virtual na Azure é possível escolher a Imagem (SO) e opções de redes, discos entre outras.
É necessário criar um servidor para utilizar o banco de dados. A criação é feita na própria Azure.
