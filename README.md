
# **BP Digital Banking – Arquitectura de Solución**

Prueba Técnica – Arquitecto de Soluciones / Devsu
Autor: **Alex Fabricio Anchundia Mero**

---

## 📌 **Descripción del proyecto**

Este repositorio contiene la arquitectura propuesta para el sistema de Banca Digital de BP, desarrollada como parte de la prueba técnica para Devsu. Incluye:

* Documento PDF con la arquitectura completa
* Modelo C4 (Contexto, Contenedores, Componentes)
* Decisiones arquitectónicas justificadas
* Diseño de onboarding biométrico
* Integración con Core Bancario y servicios complementarios
* Infraestructura cloud (AWS/Azure)
* Alta disponibilidad, monitoreo y control de costos

La propuesta está diseñada siguiendo buenas prácticas de arquitectura empresarial y requisitos del sector bancario.

---

## 🏗️ **Contenido del repositorio**

```
/pdf
   bp-digital-banking-architecture.pdf   ← Documento final

/diagramas
   c4-contexto.png
   c4-contenedores.png
   c4-componentes.png

/draft
   notas-diagramas.drawio
   borrador-arquitectura.txt
   checklist-interno.md
```

---

## 🧩 **Modelo C4**

1. **Diagrama de Contexto**
2. **Diagrama de Contenedores**
3. **Diagrama de Componentes (Microservicio de Transferencias)**

Los diagramas se encuentran disponibles tanto en el PDF como en la carpeta `/diagramas`.

---

## ☁️ **Infraestructura en la nube**

La arquitectura está preparada para funcionar en:

### **AWS**

* ECS Fargate / EKS
* API Gateway
* Aurora PostgreSQL
* DynamoDB / ElastiCache
* S3 + Glacier
* Cognito
* CloudWatch + X-Ray

### **Azure**

* AKS
* API Management
* Azure SQL
* CosmosDB / Redis Cache
* Blob Storage
* Azure AD B2C
* Monitor + Application Insights

---

## 📄 **Documento final**

El documento completo se encuentra en:

👉 **/pdf/bp-digital-banking-architecture.pdf**

---

## ✔️ **Estado del entregable**

Completado y listo para evaluación.
