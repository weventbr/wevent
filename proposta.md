
# <img src="https://s3-sa-east-1.amazonaws.com/weventbr/wevent/public/logo_100.png"> Gestão de eventos

[WEvent](https://wevent.com.br). 

Criciúma, 05 de abril de 2018

# Proposta Comercial



 À 
 
 **Universidade do Extremo Sul Catarinense**
 
 Aos Cuidados de 
 
 **Merisandra**
 
 
A Wevent é uma plataforma de gestão de eventos que permite criar um site exclusivo para o seu evento, realizar inscrições, vender ingressos, acompanhar tudo em tempo real e muito mais.


## Funcionalidades

### Glosário

Termos usados neste documento

**subeventos** - Eventos menores dentro do evento principal. Pode ser palestra, cursos, show, apresentação, item na programação entre outros

**Ingresso** - Configuração de uma credencial de acesso a um evento. Pode ser conhecido como entrada, ingresso, credencial.

**Ticket** - Ingresso comprado
 
**Apoiador** - Apoiador, Patrocinador, Organizador, entre outros
 
**Projeto** - Contempla o evento e toda configuração e gestão do mesmo

## Financeiro

Controle financeiro do evento. Podendo registrar entradas e saídas.


## Submissões / Inscrições

Uma submissão pode ser feita a partir de um arquivo ou(e) um formulário. 

#### Configuração
* Modalidade
* Área
* Data início e final disponível para submissão
* Vínculo de responsável por gerenciar essa submissão. Este irá receber todas atualizações (envios) da submissão.
* Limite por participante
    * Limita um número de submissão por participante
* Limite de autores
* Número máximo de arquivos
* Regras para aceitação da submissão
* Restrições de envio
    * Sem restrição, todos os participantes podem enviar trabalhos
    * Só pode enviar trabalho se o autor principal estiver inscrito no evento
    * Só pode enviar trabalho se ao menos um dos autores estiverem inscritos no evento
    * Só pode enviar trabalho se todos os autores estiverem inscritos no evento
* Configuração de formulário de envio
* Métricas para aprovação de uma submissão

##### _Em breve_
         
_Número mínimo de avaliações para um resultado final_ 

_Agendamento de submissões em conjunto a programação do evento_
         

## Certificados
    
Permite configurar um template de certificado a ser enviado para os participantes de um evento.
    
#### Configuração
* Texto referência para geração dos certificados
    * Palavras chaves a serem substituidas pelos dados do participante
* Imagem de fundo de um certificado
    
##### _Em breve_

_Configuração de certificados para palestrantes_
 
_Certificado específico para subeventos ou cursos dentro de um evento maior_


## Ingressos

Permite configurar os tipos de ingressos. Estes são replicados diretamente na página do evento.
Este ingresso se transforma em ticket na efetivação de uma [compra](#compra-de-tickets) na página do evento.

#### Configuração
* Grátis, Pago
* Nome de apresentação
* Quantidade máxima de um tipo de ingresso
* Datas de disponibilidade
* Tipo de cobrança. 
    * Comprador paga a taxa. Cobrado do comprador o Valor do ingresso + Taxa aplicada pela WEvent
    * Valor implícito. Comprador paga apenas o valor do ingresso e a taxa é descontada no repasse ao organizador.

###### Observações

    A configuração de lotes é feita por datas de disponibilidade  

    
##### _Em breve_

_Subtipos de ingressos, lotes "físicos"_


## Programação

Programação completa do evento. A programação irá aparecer na página principal do evento.
Ela pode ser configurada nas configurações de um projeto


##### _Em breve_

_Vínculo de uma programação com um ingresso. O usuário poderá criar um ingresso para subeventos, ou colocar com adicionais de um ingresso, subeventos_

_Organizar um subevento com apresentação de trabalhos enviados na forma de submissão_


## Mensagens 
    
Permite o envio de mensagens diretamente aos participantes de um evento
A mensagem pode ser em texto ou formato HTML
Tem a opção de enviar para todos que adquiriram um ticket ou estão credenciados. E também pode adicionar emails como cópia desta mensagem. 
 
##### _Em breve_

_Envio de mensagens separando por campo do formulário de compra. Por exemplo: enviar mensagens para todos participantes que colocaram certa opção no formulário na compra de um ticket._
_Mensagens diretamente ao participantes de subeventos._

## Configuração do evento


#### Configuração
* Nome do evento
* Data e hora do início do evento
* Data final do evento (quando necessário)
* Url do evento wevent.com.br/**URL**
    * Por padrão essa URL ficará disponível 6 meses depois do evento, mas pode ter um tratamento especial
* Página do evento, sendo explicada melhor no bloco [Página do evento](#pagina-do-evento)
* Hashtag oficial a ser usada nas redes sociais
* Endereço de um evento
    * Será mostrado um mapa na página principal do evento
    * Também será possível identificar uma rota para o evento
* Redes sociais para mais informações do evento
    * Nestas redes incluem telefone e email





## Página do evento

O usuário pode configurar a apresentação de uma página do evento via painel de controle no admin do sistema.


#### Configuração
* Informações básicas
* Cores do evento
    * sendo configurado uma cor **principal** e uma **secundária**
* Banner principal do evento
* Vídeo de apresentação
* Atrações principais
* Apoiadores
    * Pode ser configurado o termo a ser usado para cada bloco
        * Por exemplo, pode ter blocos chamados Patrocinadores, Organizadores e Apoiadores
    * Cada poderá ter um destaque de 1 a 5 estrelas. De acordo com o número de estrelas:
        * **1 estrela** 12 apoiadores na mesma linha (menor destaque e menor imagem da logomarca)
        * **2 estrelas** 6 apoiadores na mesma linha
        * **3 estrelas** 4 apoiadores na mesma linha
        * **4 estrelas** 3 apoiadores na mesma linha
        * **5 estrelas** 2 apoiadores na mesma linha (maior destaque e maior imagem da logomarca)
* Blog (como uma timeline)
    * Imagens
    * Notícias
    * Textos
* [Programação](#programacao)
* Mapa de localização do evento

## Credenciamento


Para ter acesso ao credenciamento, o usuário deve ter a permissão de **gestor** ou **credenciador** de um evento. 

* Formas
    * Código
        Na sessão Credenciamento no painel o credenciador pode inserir o código para efetivar um credenciamento 
    * QRCode
        * O credenciamento é feito via celular, com um browser ou um aplicativo de leitura de QRCode
        * Este é direcionado para a página do evento o qual efetua o credenciamento ou o não credenciamento de um ticket


##### _Em breve_

_Credenciamento por subevento_

## Compra de Tickets


### Processo
1. A compra de tickets fica disponível na página principal do evento em forma de lista

2. O comprador precisa colocar seus dados padrões e pode acrescentar outros dados nas configurações

3. Em uma compra não gratuita, existe a possíbilidade de efetuar a compra com **cartão de crédito** ou **boleto bancário**
    
        Boleto fica disponível até 3 dias úteis antes do evento.
    
4. O comprador recebe um email com o código alfanumérico e um qrcode ao finalizar a compra

        O cancelamento de um ingresso é feito via e-mail do evento.

#### Configuração
* Na sessão [Ingressos](#ingressos) pode configurar um tipo de ingresso e sua disponíbilidade
* Pode determinar um formuário para compra de um ticket em **campos do cadastro**
* Existe a opção de permitir apenas uma compra ou multipla compra por cadastro
    



##### _Em breve_

_Opção de recebimento de email para o organizador do evento_
_Cancelamento via site_



## Usuários e permissões

#### Tipos de "roles" do sistema
* Gestor
    * Pode gerenciar todos os processos
* Organizador
    * Não permite alterar permissões
    * Não permite executar processos
* Credenciador
    * Apenas é permitido credenciar tickets
* Avaliador
    * Apenas permitido avaliar trabalhos
    
  
  
# Portfólio

* ACIC - https://wevent.com.br/pactopelosul
* SENAC - https://wevent.com.br/t2con
  

# Valores para aquisição

 _10% sobre os ingressos comercializados_ 


 ## Contato
 
 Renan Casagrande
 renan@wevent.com.br
 (48) 99900-2002
 
   
 Wevent Gestão para Eventos Ltda.
 CNPJ 28.383.069/0001-60
 Criciúma/SC - Brasil
