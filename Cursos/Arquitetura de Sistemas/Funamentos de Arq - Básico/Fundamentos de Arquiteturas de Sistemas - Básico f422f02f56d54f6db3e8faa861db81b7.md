# Fundamentos de Arquiteturas de Sistemas - Básico

**Serviços Web -** são soluções para aplicações se comunicarem independe de linguagem, softwares e hardwares utilizados.

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled.png)

**Estrutura SOAP - Simple Object Access Protocol**

XML → Extensible Markup Language

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%201.png)

**SOAP Envelope** - É o primeiro elemento do documento e é usado para encapsular toda a mensagem SOAP.

**SOAP Header** - É o elemento onde possui informaçõede atributos e metadados da requisição.

**SOAP Body** - É o elemento que contém os detalhes da mensagem.

**WSDL e XSD**

WSDL - Web Services Description Language

XSD - XML Schema Definition

[](http://www.soapclient.com/xml/soapresponder.wsdl)

**SOAP UI / Zeep Python**

**REST, API e JSON**

REST - Representation State Transfer

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%202.png)

**API** - Application Programming Interface

*GET* - Solitica a representação de um recurso

*POST* - Solicita a criação de um recurso

*DELETE* - Solicita a exclusão de um recurso

*PUT* - Solicita a atualização de um recurso

[https://www.restapitutorial.com/lessons/httpmethods.html](https://www.restapitutorial.com/lessons/httpmethods.html)

**JSON** - JavaScript Object Notation

Atributo + Valor

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%203.png)

**REST + HTTP + Status Code**

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%204.png)

Postman Software

Request: HTTP for Humans - Python

**Tipo de Arquitetura:**

Monolito

✅ Baixa Complexidade

✅ Monitoramento Simplificado

❌ Stack Única

❌ Compartilhamento de recurso

❌ Acoplamento

❌ Mais Complexo a Escalabilidade

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%205.png)

Microserviços I

✅ Stack Dinâmica

✅ Simples Escalabilidade

❌ Acoplamento

❌ Monitoramento mais complexo

❌ Provisionamento mais complexo

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%206.png)

Mircroserviços II

✅ Stack Dinâmica

✅ Simples Escalabilidade

✅ Desacoplamento

❌ Monitoramento mais complexo

❌ Provisionamento mais complexo

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%207.png)

Microserviços III

✅ Stack Dinâmica

✅ Simples Escalabilidade

✅ Desacoplamento

✅ Menor Complexibilidade

❌ Provisionamento mais complexo

❌ Plataforma inteira depende do gerenciador de pipeline

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%208.png)

**Gerenciamento de Erros**

Onde é mais complexo:

Processos Assíncronos (M2)

Pipeline

Solução:

Dead letter queue

Filas de re-tentativas

**IoT**

*ARPANET*

Arduino - MCUs - Raspberry Pi

Protocolo MQTT

Base na Pilha do TCP/IP  

Protocolo de Mensagem assíncrona (M2M)

Criado pela IBM para conectar sensores de pipelines de petróleo a satélites

Padrão OASIS suportado pelas linguagens de programação mais populares

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%209.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2010.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2011.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2012.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2013.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2014.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2015.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2016.png)

![Untitled](Fundamentos%20de%20Arquiteturas%20de%20Sistemas%20-%20Ba%CC%81sico%20f422f02f56d54f6db3e8faa861db81b7/Untitled%2017.png)