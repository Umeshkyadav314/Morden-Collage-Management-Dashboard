
## Getting Started

# Project Title : Morden Collage Management Dashboard 

Brief description of the project and its core features.

## Tech Stack

- **Next.js** (React Framework)
- **TypeScript** (Static Typing)
- **Prisma** (Database ORM)
- **Tailwind CSS** (UI Styling)
- **Docker** (Containerization)

## Prerequisites

- Node.js 18+
- Docker (optional)
- PostgreSQL/MySQL (for Prisma)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/Umeshkyadav314/Morden-Collage-Management-Dashboard.git
    cd your-repository
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up Prisma:

    ```bash
    npx prisma migrate dev
    ```

4. Run the development server:

    ```bash
    npm run dev
    ```

    The app will be running at [http://localhost:3000](http://localhost:3000).

## Docker Setup

1. Build and start containers:

    ```bash
    docker-compose up --build
    ```

## Folder Structure

- **/prisma**: Prisma schema & migrations
- **/src**: Application code (components, pages, etc.)
- **Dockerfile**: Container build instructions
- **tailwind.config.ts**: Tailwind CSS setup

## Environment Variables

Create a `.env` file:

```bash
DATABASE_URL=your-database-url
NEXT_PUBLIC_API_URL=http://localhost:3000/api
