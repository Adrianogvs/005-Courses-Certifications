# **Certificação AZ-900**

### Sobre a prova:

<div align="center">
<br>
  
Descrição | %
---------|----------
Descrever conceitos de nuvem; | 20-25% 
Descrever os princípios do Azure; | 15-20%
Descrever as principais soluções e ferramentas de gerenciamento no Azure; | 15-20%
Descrever recursos gerais de segurança e segurança de rede; | 10-15%
Descrever os recursos de identidade, governança, privacidade e conformidade; | 15-20%
Descrever o gerenciamento de custos do Azure e os Contratos de nível de Serviço. | 10-15%
<div/>

<div align="left">
<br>
    
### Episódio 1 - Conceitos de Nuvem
#### 1. Modelos de Nuvem.
#### 2. Considerações e Benefícios da Nuvem.
#### 3. Serviços de Nuvem.
<br>

### 1.0 Modelos de Nuvem
#### 1.1 O que é computação em nuvem?
Computação em Nuvem é a entrega de serviços de computação por meio de internet, possibilitando uma inovação mais rápida, recursos flexíveis e economia de escala.

<div align="center">

Computação    | Rede| Armazenamento | Análise
--------------|-------|-----------------|---------
<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/001.png" alt="001" width="150"/>|<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/002.png" alt="002" width="150"/>|<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/003.png" alt="003" width="150"/>|<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/004.png" alt="004" width="150"/>

<div/>
<div align="left">

Computação em nuvem nada mais é a entrega rápida de recursos computacionais que estão em um determinado provaider.<br>
A computação em nuvem fornece possibilidades que o modelo on-premise não pode atingir.<br>
Na computação em nuvem temos três modelos, sendo os modelos **publico, privado e hibrido**.

<div align="left">
<br>

#### 1.2.1 Nuvem Publica
- Pertence a serviços de nuvem ou provedor de hosting.
- Fornece recursos e serviços a várias organizações.
- Acesso voa conexão de rede segura (geralmente pela internet).
<br>

<div align="center">
<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/005.png" alt="005" width="250"/>
<div/>
<br/>

<div align="left">
<br>

#### 1.2.2 Nuvem Privada
- As organizações criam um ambiente em nuvem em seu datacenter.
- A organização é responsável por operar os serviços que fornece.
- Não fornece acesso aos usuários fora da organização.
<br><p>
**Observação:**<p>
*Este ambiente é justamente o on-premise, em que a organização tem todo sua estrutura montada internamente, como servidores, armazenamento, rede e etc.*
<br>

<div align="center">
<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/006.png" alt="006" width="200"/>
<div/>
<br/>

<div align="left">
<br>

#### 1.2.3 Nuvem Hibrida
- Combina as nuvens Pública e Privada para permitir que os aplicativos sejam executados no local mais apropriado.
- Este é um dos modelos mais utilizado.
<br>

<div align="center">
<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/007.png" alt="007" width="400"/>
<div/>
<br/>

<div align="left">
<br>
  
#### 1.3 Comparação do modelo de nuvem

#### 1.3.1 Nuvem Pública
- Nenhuma despesa de capital para escalar verticalmente;
- Os aplicativos podem ser rapidamente provisionados e desprovisionados;
- As organizações pagam apenas pelo que usam.

#### 1.3.2 Nuvem Privada
- O hardware deve ser adquirido para inicialização e manutenção;
- As organizações tem controle total sobre recursos e segurança;
- As organizações são responsáveis pelas atualizações e pela manutenção do hardware.

#### 1.3.3 Nuvem Híbrida
- Oferece maior flexibilidade;
- As organizações determinam onde executar seus aplicativos;
- As organizações controlam os requisitos de segurança, conformidade ou jurídicos.

<div align="left">
<br>

### 2.0 Considerações e Benefícios da Nuvem
#### 2.1 Benefícios da Nuvem
- Alta disponibilidade:<br>
  *SLA,Acordo de Nível de Serviço.*<p>
  
- Tolerância a falhas:<br>
  *Replicação de informações, mesmo que tem um serviço indisponível em uma ponta, o usuário não irá perceber a indisponibilidade, ou seja, é tolerante a falhas. *<p>
  
- Escalabilidade:<br>
  *Está associado quando vamos alterar recursos para atender uma demanda operacional, exemplo: Aumento de disco, ou seja, irá manter as configurações*.<p>
  
- Elasticidade:<br>
  *Neste caso podemos usar como exemplo o período de balck-friday, em que precisamos ter um aumento de cumputação conforme a demanda, ou seja, não ira manter-se as configurações. *<p>
  
- Alcance global:<br>
  *Todos os provaider oferecem grandes números de data center em inúmeras regiões. *<p>
  
- Capacidade de latência do cliente:<br>
  *Mesmo que tenhamos serviço alocados em regiões diferentes, ainda sim a latência é bem menor do que se tivéssemos serviços em ambientes on-premise, ou seja, internet tradicionais. *<p>
  
- Agilidade:<br>
  *Podemos associar a recurso de self-service, acesso o portal e ja tem os serviços, configura e em questões de segundos ja está tudo pronto para uso e não precisa fazer orçamentos e nem depende de recursos físicos. *<p>
  
- Considerações sobre custo preditivo. <br>
  São dois tipos de despesas, sendo:
   - **CapEx**:
    - *Refere-se a despesas de capitais, como aquisição de maquinas, equipamentos, prédios proprios.*
    - *Gastos inicial de dinheiro na infraestrutura física. *
    - *Os custos de Capex tem um valor que é reduzido ao longo do tempo. *
   
   - **OpEx**:
     - *Refere-se a despesas operacionais, como alugueis, energia, publicidade, escritorio jurídico. *
     - *Gastos em produtos e serviços conforme necessário, pagamento conforme o uso. *
     - *Receber a conta imediatamente. *
<div align="center">
<img src="https://github.com/Adrianogvs/005-Courses-Certifications/blob/main/001-Azure/img/008.png" alt="008" width="400"/>
<div/>
<div align="left">
<br>
- Recuperação de desaste:<br>
  *É quando tive um problema e meu ambiente precisa subir em outra região, por exemplo temos um grupo de máquina na regiçao do Brasil e temos replica nos Estados Unidos.*<p>
  
- Segurança:<br>
  *Podemos conectar na nuvem por diversos sérvios e teremos serviços criptografados, porem tem itens que não é responsabilidade do provaider.*<p>




<div/>
