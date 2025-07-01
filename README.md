# 🌿 PlantID - Identificação de Plantas por IA  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.85-green)](https://fastapi.tiangolo.com/)
[![Next.js](https://img.shields.io/badge/Next.js-13.4-red)](https://nextjs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)  

**PlantID** é um aplicativo web que identifica espécies de plantas a partir de imagens usando visão computacional. Ideal para jardineiros, biólogos ou curiosos!  

👉 **Live Demo**: [https://plantid.vercel.app](https://plantid.vercel.app) (exemplo)  

## ✨ Funcionalidades  
- 📸 Upload de foto para identificação instantânea.  
- 🔍 Exibe nome científico, descrição e cuidados.  
- 📊 Histórico de buscas (com autenticação opcional).  
- 🌐 Modo offline via TensorFlow.js.  

## 🛠️ Tecnologias  
- **IA**: PyTorch (ViT) / TensorFlow (EfficientNet).  
- **Backend**: FastAPI (Python) + PostgreSQL.  
- **Frontend**: Next.js + Tailwind CSS.  
- **Deploy**: Vercel (frontend), AWS EC2 (backend), Hugging Face (modelo).  

## 🚀 Como Executar Localmente  

### Pré-requisitos  
- Python 3.9+, Node.js 16+, Docker (opcional).  

### Passo a Passo  
1. **Clone o repositório**:  
   ```bash
   git clone https://github.com/seu-usuario/plantid.git
   cd plantid
