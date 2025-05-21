---
layout: default
title: Aula 01
nav_order: 2
---

# Aula 1 – Introdução ao Curso, Ferramentas e Ambiente (IDE, JDK, Maven/Gradle)

---

## 1.1. Boas-vindas e objetivos do curso

Seja bem-vindo(a) ao curso **Java para Microsserviços e Cloud: Um Guia Prático**.
 
Ao longo das próximas 50 aulas, você será conduzido em uma jornada completa, partindo dos fundamentos da linguagem Java até a construção, integração, teste e deploy de um sistema real, composto por múltiplos microsserviços na nuvem.

Este curso foi planejado para ser **prático, progressivo e alinhado às exigências do mercado**.  
A cada módulo, você aprenderá conceitos essenciais e aplicará esse conhecimento em projetos reais, com as principais ferramentas do ecossistema Java moderno.

### Objetivos desta aula:
- Apresentar a estrutura do curso  
- Explicar o que são microsserviços e cloud computing em linhas gerais  
- Orientar a instalação e configuração do ambiente de desenvolvimento  
- Mostrar o papel das principais ferramentas: IDE, JDK, Maven e Gradle  

---

## 1.2. Estrutura do curso

O conteúdo está dividido em 7 módulos temáticos:

1. Fundamentos de Java e POO  
2. Java Moderno e APIs Essenciais  
3. Spring Framework e Spring Boot  
4. Microsserviços na prática  
5. Segurança e autenticação  
6. Cloud e DevOps  
7. Projeto final com deploy na nuvem  

Ao final do curso, você será capaz de:

- Desenvolver aplicações Java modernas  
- Projetar e implementar microsserviços com Spring Boot  
- Integrar serviços via REST e mensageria  
- Criar pipelines de CI/CD  
- Realizar deploy de sistemas na nuvem (AWS, GCP ou Azure)  

---

## 1.3. O que são Microsserviços e Cloud Computing?

Antes de começarmos a codificar, é importante entender o **“porquê”** desta abordagem.

**Microsserviços** são um estilo de arquitetura onde o sistema é dividido em pequenos serviços independentes, cada um responsável por uma funcionalidade específica e comunicando-se com os demais.

### Vantagens:
- Maior escalabilidade  
- Facilidade de manutenção e deploy independente  
- Melhor organização de equipes e responsabilidades  

**Cloud computing**, por sua vez, permite que esses serviços sejam executados de forma **distribuída, escalável e resiliente na internet**, sem necessidade de infraestrutura própria.

Ferramentas como **Docker**, **Kubernetes** e plataformas como **AWS** serão nossos aliados nesta jornada.

---

## 1.4. Ferramentas que usaremos

### 1.4.1. IDE – IntelliJ IDEA ou VS Code

Você poderá utilizar a IDE de sua preferência, sendo as mais recomendadas:

- **IntelliJ IDEA** (Community ou Ultimate): recomendada para projetos Java, com excelente suporte ao Spring Boot.  
- **Visual Studio Code**: mais leve, com extensões para Java, Spring, Docker e Kubernetes.

> ⚠️ **Dica:** Se você está começando agora com Java, o IntelliJ tende a ser mais amigável e completo para projetos Spring Boot.

---

### 1.4.2. JDK – Java Development Kit

Neste curso, utilizaremos o **JDK 17**, versão LTS (Long-Term Support), amplamente adotada pelo mercado.

Você pode baixá-lo de fontes confiáveis como:
- [Adoptium](https://adoptium.net/)
- [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html)

Após a instalação, verifique com:

```bash
java -version
javac -version
```

---

### 1.4.3. Maven e Gradle – Gerenciadores de dependências

Ao trabalhar com Java, especialmente em projetos corporativos e Spring Boot, é fundamental utilizar um gerenciador de dependências.

Neste curso usaremos principalmente o **Maven**, mas também veremos como adaptar para **Gradle**.

- **Maven**: baseado em XML, com convenções bem definidas  
- **Gradle**: baseado em Groovy ou Kotlin, mais flexível e rápido  

---

## 1.5. Instalando e configurando o ambiente

### Passo 1 – Instalar o JDK
- Baixe e instale o JDK 17  
- Configure a variável de ambiente `JAVA_HOME`  

### Passo 2 – Instalar a IDE
- Faça o download do IntelliJ IDEA ou VS Code  
- No VS Code, instale as extensões **Java Extension Pack** e **Spring Boot Tools**

### Passo 3 – Instalar Maven e/ou Gradle
- [Maven](https://maven.apache.org/download.cgi)  
- [Gradle](https://gradle.org/install/)

> 💡 **Dica:** Use o [Spring Initializr](https://start.spring.io) para gerar seu projeto já configurado com Maven ou Gradle.

---

## 1.6. Testando o ambiente com um projeto básico

Para garantir que tudo está funcionando, crie um projeto simples com o **Spring Initializr**:

1. Acesse [https://start.spring.io](https://start.spring.io)  
2. Escolha:
   - Project: `Maven`  
   - Language: `Java`  
   - Spring Boot: `3.1` ou superior  
   - Group: `com.seuprojeto`  
   - Artifact: `introducao`  
3. Adicione a dependência: `Spring Web`  
4. Clique em **"Generate"** e importe o projeto na sua IDE  

Execute o projeto e verifique se aparece no console:

```bash
Started IntroducaoApplication in X seconds
```

---

## 1.7. Conclusão da aula

Agora que você está com o ambiente pronto, podemos mergulhar no universo Java com segurança.  
A partir da próxima aula, começaremos a revisar os fundamentos da linguagem Java, reforçando conceitos essenciais para quem quer escrever código limpo, eficiente e moderno.

**Prepare-se: seu caminho rumo ao domínio de microsserviços em Java começa agora!**

