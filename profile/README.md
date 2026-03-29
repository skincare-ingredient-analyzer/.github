<div align="center">
  <h1>Skincare Ingredient Analyzer</h1>
  <strong>A data-driven platform that reinterprets skincare ingredients from a user-centered perspective</strong>
</div>

<br />

## 📋 Project Overview
- **Project Name**: Skincare Ingredient Analyzer
- **Project Type**: Personal Data / Full-stack Project
- **Development Period**: Sep 2025 – Jan 2026
- **Data Scale**: 900+ products / 5,000+ ingredients
- **Deployment**: Docker-based (GCP / AWS planned)

## 🎯 Problem Statement

Most skincare platforms list ingredient information without interpretation.
In particular, EWG labels such as None or Unknown are often misunderstood as “safe,” when they actually indicate a lack of reliable evidence.

For users with sensitive or reactive skin,
the absence of evidence itself becomes a critical risk factor.

This project asks a fundamental question:

Should uncertainty be ignored, or should it be analyzed as data?

## ✨ Core Approach  
Rather than excluding uncertain data, this project treats uncertainty as an analytical dimension.

🔍 User-Centered Ingredient Classification
Ingredients are reclassified into six categories by combining:
- EWG hazard scores
- Ingredient usage frequency
- User-oriented risk interpretation

### Classification System
- **Base**: Ingredients appearing in ≥75% of products
- **Medium**
- **High**
- **Caution**
- **Allergy**
- **Unknown** ⭐
(By preserving “Unknown” as a first-class category, the system highlights data gaps that are typically hidden or ignored in conventional ingredient analyses.)

✔ Unknown ≠ Safe
✔ Unknown = Evidence Gap

## <span id="2">주요 기능🚀</span>
<h3>1. Home Page</h3>
<table>
  <tbody>
    <tr>
      <td>Modal</td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/1be7e413-63a6-4978-b80b-5f64af4a3c59" height="500px" /></td>
    </tr>
    <tr>
      <td>Product & SkinType Select</td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/895398ee-e09a-47c9-ba05-9c275e33c6cb" height="500px"/></td>
    </tr>
  </tbody>
</table>
<h3>2. Result Page</h3>
<table>
  <tbody>
    <tr>
      <td>Common Ingredients</td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/2fb5f559-8f03-4bcb-9160-947946931abd" height="500px"/></td>
    </tr>
    <tr>
      <td>AI</td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/be08e3cc-0289-4e62-89c8-3ad37f8f23a2" height="500px"/></td>
    </tr>
  </tbody>
</table>
<h3>3. Statistics Page</h3>
<table>
  <tbody>
    <tr>
      <td>Pie Graph & Table</td>
    </tr>
    <tr>
    <td><img src="https://github.com/user-attachments/assets/3e74256a-82fa-44e6-94a7-b201d11032a1" height="500px"/></td>
    </tr>
  </tbody>
</table>

---

## 🛠️ 기술 스택

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.0.2-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-4.4.5-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Axios-1.13.1-5A29E4?style=for-the-badge&logo=axios&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-5.0.8-764ABC?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query-5.90.7-FF4154?style=for-the-badge&logo=react-query&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Router_Dom-7.9.5-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/MUI-7.3.5-007FFF?style=for-the-badge&logo=mui&logoColor=white" />
  <img src="https://img.shields.io/badge/Emotion-11.x-DB7093?style=for-the-badge&logo=emotion&logoColor=white" />
  <img src="https://img.shields.io/badge/Mantine_Carousel-8.3.8-339AF0?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Recharts-3.4.1-FF6384?style=for-the-badge&logo=chart.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Embla_Carousel-8.6.0-888888?style=for-the-badge&logo=react&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/Kakao_Maps_SDK-1.2.0-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black" />
  <img src="https://img.shields.io/badge/Firebase-12.5.0-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-3.5.7-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Framework-6.2.12-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-17+-007396?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA%20/%20Hibernate-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white" />
</p>

### Database
<p>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
</p>

### Security
<p>
  <img src="https://img.shields.io/badge/Spring_Security-6.5.6-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth2-FF7F00?style=for-the-badge&logo=openid&logoColor=white" />
</p>

### 외부 API
<p>
  <img src="https://img.shields.io/badge/KOPIS_API-0B5FFF?style=for-the-badge&logo=data&logoColor=white" />
  <img src="https://img.shields.io/badge/Kakao_Maps_API-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black" />
  <img src="https://img.shields.io/badge/Google_OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <br/>
  + 기타 소셜 로그인 및 외부 연동 API
</p>

### DevOps / Infra / 배포

<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-Container-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker_Hub-Registry-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP_Compute_Engine-VM-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
  <img src="https://img.shields.io/badge/docker_compose-Orchestration-384D54?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-Proxy%20%26%20Static%20Serve-009639?style=for-the-badge&logo=nginx&logoColor=white" />
</p>

## 📂 Project Folder Structure

### Frontend

```bash
frontend/
├── node_modules/
├── public/
├── src/
│   ├── apis/                     # Axios instance & API wrappers
│   │   ├── instance.ts           # Axios base configuration
│   │   ├── productApi.ts         # Product-related API calls
│   │   └── unknownApi.ts         # Unknown ingredient API calls
│   │
│   ├── assets/                   # Static assets
│   │   └── react.svg
│   │
│   ├── components/               # Reusable UI components
│   │   ├── buttons/
│   │   │   └── SkinTypeButton.tsx
│   │   ├── CategoryBlock/
│   │   │   ├── CategoryBlock.tsx
│   │   │   └── styles.ts
│   │   └── GuideModal/
│   │       ├── GuideModal.tsx
│   │       └── styles.ts
│   │
│   ├── pages/                    # Page-level components
│   │   ├── ProductSelect/
│   │   │   ├── ProductSelect.tsx
│   │   │   └── styles.ts
│   │   ├── Result/
│   │   │   ├── Result.tsx
│   │   │   └── styles.ts
│   │   └── Stats/
│   │       ├── Stats.tsx
│   │       └── styles.ts
│   │
│   ├── routes/                   # Application routing
│   │   └── MainRouter.tsx
│   │
│   ├── types/                    # TypeScript type definitions
│   │   └── resultTypes.ts
│   │
│   ├── utils/                    # Utility functions
│   │   ├── cleanName.ts          # Ingredient name normalization
│   │   └── sortByCount.ts        # Sorting logic by frequency
│   │
│   ├── App.tsx
│   ├── App.css
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
│
├── .env
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
```
### Backend
```bash
backend/
├── .gradle/
├── .idea/
├── build/
├── gradle/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── skincare/
│   │   │           └── backend/
│   │   │               ├── config/                 # Application & crawler configuration
│   │   │               ├── controller/             # REST API controllers
│   │   │               │   ├── ProductController
│   │   │               │   └── UnknownIngredientController
│   │   │               ├── entity/                 # JPA entities
│   │   │               │   ├── Product
│   │   │               │   ├── Ingredient
│   │   │               │   └── UnknownIngredient
│   │   │               ├── record/                 # Request / response records
│   │   │               │   ├── CategorizedIngredientsResp
│   │   │               │   ├── CrawledProduct
│   │   │               │   └── ProductReq
│   │   │               ├── repository/             # JPA repositories
│   │   │               │   ├── ProductRepository
│   │   │               │   ├── IngredientsRepository
│   │   │               │   └── UnknownIngredientRepository
│   │   │               ├── service/                # Business logic
│   │   │               │   ├── ProductService
│   │   │               │   ├── IngredientCategoryService
│   │   │               │   ├── IngredientCategorizer
│   │   │               │   ├── UnknownIngredientService
│   │   │               │   ├── GlowpickCrawlerService
│   │   │               │   └── GeminiExplainService
│   │   │               └── BackendApplication
│   │   └── resources/
│   │       ├── application.properties              # Application configuration
│   │       └── categorized_ingredients.json        # Predefined ingredient categories
│   └── test/
│       └── java/
│           └── com/
│               └── skincare/
│                   └── backend/
│                       └── BackendApplicationTests
├── .gitattributes
├── .gitignore
├── build.gradle
├── gradlew
├── gradlew.bat
└── settings.gradle
```

