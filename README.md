# Workout API

## Overview

This project provides an asynchronous API for a gym for a crossfit competition. Using the FastAPI framework, Docker-Compose, and PostgreSQL.

## Setup

1. **Instale os pacotes**

   ```bash
   pip install -r requirements.txt

2. **Inicialize o PostgreSQL**

   ```bash
   docker-compose up -d

3. **Crie as migrates**

   ```bash
   make run-migrations
   make create-migrations d="init-db"

4. **Inicialize a API**

   ```bash
   make run

5. **Acesso dos endpoints**

   ```bash
   http://localhost:8000/docs


<br>

#### Motivation Overview
Resolution of the challenge proposed for the DIO Python AI Backend Developer bootcamp, developing your first API with FastAPI, Python, and Docker. Taught by Prof. <a href="https://www.linkedin.com/in/nayannanara/" target="_blank">Nayanna Nara.</a>