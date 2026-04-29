# 🚛 Trafe GO - Sistema de Gestão de Frotas

![Versão](https://img.shields.io/badge/version-1.0.0-blue)
![React Native](https://img.shields.io/badge/React_Native-0.72-blue)
![Expo](https://img.shields.io/badge/Expo-49.0-black)
![Firebase](https://img.shields.io/badge/Firebase-10.0-orange)
![Licença](https://img.shields.io/badge/license-MIT-green)

## 📱 Sobre o Projeto

O **Trafe GO** é um sistema multiplataforma completo para gestão de uma transportadora, desenvolvido em **React Native** com **Expo** e **Firebase**. O software  foi projetado para otimizar o dia a dia de motoristas e equipes administrativas, oferecendo ferramentas para controle de notas fiscais, despesas, devoluções, chat interno e relatórios financeiros.

### 🎯 Objetivo

Solucionar os desafios da gestão de frotas através de uma plataforma intuitiva que integra motoristas, gerentes e administradores em um único ecossistema, garantindo rastreabilidade, controle financeiro e comunicação eficiente.

### 👥 Público-alvo

| Perfil | Funcionalidades |
|--------|-----------------|
| **🚛 Motoristas** | Registro de notas fiscais, despesas e devoluções |
| **📋 Gerentes** | Aprovação de despesas e notas, acompanhamento de equipe |
| **👑 Administradores** | Gestão completa do sistema, relatórios e dashboards |

---

## ✨ Funcionalidades

| Módulo | Funcionalidades |
|--------|-----------------|
| **🔐 Autenticação** | Login com Firebase Auth, cadastro de usuários, recuperação de senha, controle de acesso por cargo |
| **📄 Notas Fiscais** | Cadastro com foto (Base64), cálculo automático de frete por destino, filtros por data/placa/motorista/status, aprovação/rejeição com justificativa |
| **💰 Despesas** | Registro com comprovante (Base64), tipos: Combustível, Manutenção, Alimentação, Outros, aprovação com justificativa, gráficos por período |
| **🔄 Devoluções** | Registro de entregas com foto, dados do recebedor, status Entregue/Não Entregue |
| **🚗 Placas** | CRUD completo de veículos, ativação/desativação, vínculo com motorista |
| **💬 Chat** | Comunicação em tempo real entre motoristas e administração, envio de localização |
| **📊 Relatórios** | Dashboards financeiros, despesas vs fretes, saldo por período, desempenho por motorista |
| **🔔 Notificações** | Alertas push para aprovação/rejeição de notas e despesas |

---

## 🎨 Identidade Visual

### Cores Oficiais

| Elemento | Cor | Código HEX | Uso |
|----------|-----|------------|-----|
| **Primária** | Azul Corporativo | `#0A3D62` | Botões principais, cabeçalhos, links |
| **Secundária** | Laranja Destaque | `#F39C12` | Badges de pendência, avisos |
| **Sucesso** | Verde | `#27AE60` | Status aprovado, confirmações |
| **Erro** | Vermelho | `#E74C3C` | Status rejeitado, exclusões |
| **Fundo** | Cinza Claro | `#F8F9FA` | Background principal |
| **Cards** | Branco | `#FFFFFF` | Cards, modais, formulários |
| **Texto Principal** | Cinza Escuro | `#2C3E50` | Títulos, textos principais |
| **Texto Secundário** | Cinza Médio | `#7F8C8D` | Descrições, datas, labels |

### Tipografia

| Estilo | Tamanho | Peso | Uso |
|--------|---------|------|-----|
| H1 | 48px | Bold | Título principal |
| H2 | 32px | Light | Subtítulos |
| H3 | 26px | Regular | Seções |
| H4 | 20px | Medium | Cabeçalhos de tela |
| H5 | 18px | Bold | Títulos de card |
| H6 | 16px | Bold | Informações destacadas |
| Corpo | 14px | Regular | Textos gerais |
| Pequeno | 11px | Regular | Descrições, datas, status |

### Ícones

- **Biblioteca:** `@expo/vector-icons` (Ionicons)
- **Estilo:** Outline para itens inativos, Solid para ativos
- **Tamanho padrão:** 24px

---

## 🏗️ Arquitetura do Projeto

Link do Protótipo Navegável - [https://www.figma.com/make/5rIs4jvYUe5VYV3RgTDckQ/Naveg%C3%A1vel-App-Prototype?p=f&t=uFEbO6wJORXGdkWm-0](https://sl1nk.com/oaa8t8h)
