# Kindleware — Custom Shopify Theme (Built on Dawn)

**Kindleware** is a custom Shopify theme built on top of Shopify’s official Dawn starter theme. The project demonstrates advanced Shopify development skills, including custom section architecture, dynamic schema blocks, Tailwind styling, and conversion-optimized layouts.

It’s designed to mimic a premium cookware brand experience while showcasing the type of frontend and CMS flexibility used by modern ecommerce teams. The theme has been restructured to give merchants full editing control via the Shopify Theme Editor, with custom components added for personalization and CRO.

---

## Project Goals

- Show mastery of **Shopify theme architecture**
- Deliver a highly **editable experience via schema & blocks**
- Create a **conversion-optimized UX**
- Practice real-world workflows with **Git branching (main/staging/dev)**
- Simulate a complete brand experience with **design, code, and email**

---

## Tech Stack

- **Shopify Liquid**
- **Tailwind CSS** (utility-first styling)
- **Shopify CLI**
- **JavaScript (ES6)**
- **HTML Email** (Klaviyo-compatible)
- **GitHub** w/ structured branching strategy

---

## Core Features

| Feature                       | What It Demonstrates                                        |
|-------------------------------|--------------------------------------------------------------|
| Custom Sections               | `feature-icon-grid.liquid`, `bundle-builder.liquid`, etc.   |
| PDP Tabs via Metafields       | Dynamic product details mapped to metafields                |
| HTML Email Templates          | Responsive emails for welcome + abandon cart flows          |
| GitHub Workflow               | `main`, `staging`, `dev` branches with proper commit history|
| CRO-Oriented UX               | Bundle logic, trust sections, responsive PDPs               |
| Shopify Schema + Blocks       | Flexible editing in Theme Editor for marketers              |
| Accessible & Responsive       | Built mobile-first, tested for all breakpoints              |

---

## Previews

- **Live Store Preview:** [https://kindleware.myshopify.com](https://kindleware.myshopify.com) (Dev password available upon request)

---

## Project Structure

```bash
kindleware/
├── assets/
├── config/
│   └── settings_schema.json
├── layout/
├── locales/
├── sections/
│   ├── feature-icon-grid.liquid
│   ├── bundle-builder.liquid
│   └── ...
├── snippets/
├── templates/
├── emails/
│   └── welcome.html
├── README.md
