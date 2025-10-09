# 📊 Analytics Dashboard (AD)

A **multi-tenant analytics dashboard** built with **Next.js** that demonstrates server-side data aggregation, chart visualizations, virtualized data tables, CSV export, and efficient handling of large datasets.

---

## 🚀 Goal

To create a **high-performance analytics platform** that showcases:
- **Server-side aggregation** and **caching**
- **Multi-tenant** (organization-based) data isolation
- **Interactive charts**, **filters**, and **date range** queries
- **Virtualized data tables** for large datasets
- **CSV/Excel export** and **shareable permalinks**

---

## 🧩 Core Features

✅ **Authentication**
- GitHub OAuth via **NextAuth**

✅ **Multi-Tenant Architecture**
- Tenant/org-based scoping for isolated data access

✅ **Interactive Analytics**
- KPI cards and responsive charts (Line / Area / Bar)
- Advanced filtering with date range pickers

✅ **Virtualized Data Table**
- Server-side pagination, sorting, and filtering
- Optimized for large datasets

✅ **Export & Share**
- Export reports as **CSV/Excel**
- Generate **shareable permalinks** for saved views

✅ **Performance**
- Caching with **Redis** for aggregated queries
- Fully responsive and accessible UI

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | [Next.js (App Router)](https://nextjs.org/docs/app) + [TypeScript](https://www.typescriptlang.org/) |
| **UI** | [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/) + [Radix UI](https://www.radix-ui.com/) |
| **Charts** | [Recharts](https://recharts.org/en-US/) or [visx](https://airbnb.io/visx/) |
| **Data Fetching** | [React Query](https://tanstack.com/query/latest) |
| **Database** | [PostgreSQL](https://www.postgresql.org/) + [Prisma ORM](https://www.prisma.io/) |
| **Caching** | [Redis](https://redis.io/) |
| **Testing** | Jest + @testing-library/react + msw + Playwright (E2E) |
| **Containerization** | Docker (base image: `node:20-alpine`) |

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/analytics-dashboard.git
cd analytics-dashboard
