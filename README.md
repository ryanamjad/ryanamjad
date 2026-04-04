\documentclass[letterpaper,11pt]{article}

\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage[usenames,dvipsnames]{color}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{geometry}

\geometry{left=0.5in, right=0.5in, top=0.45in, bottom=0.45in}

\pagestyle{empty}

\titleformat{\section}{\large\bfseries\scshape}{}{0em}{}[\titlerule]
\titlespacing*{\section}{0pt}{6pt}{4pt}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item[]
    \begin{tabularx}{\textwidth}{X r}
      \textbf{#1} & #2 \\
      \textit{#3} & \textit{#4} \\
    \end{tabularx}\vspace{-5pt}
}

\newcommand{\resumeItem}[1]{\item #1 \vspace{-2pt}}

\begin{document}

%----------HEADING----------
\begin{center}
  {\Huge \textbf{Ryan Amjad}} \\[4pt]
  Winnipeg, CA \,$\bullet$\, \href{mailto:amjadryan5@gmail.com}{amjadryan5@gmail.com} \,$\bullet$\, +1\,584\,888\,2501 \,$\bullet$\, \href{https://github.com/ryanamjad}{github.com/ryanamjad}
\end{center}

%----------SUMMARY----------
\section{Summary}
Full-stack Software Engineer with 5+ years of experience designing, building, and maintaining production-grade software systems. Technical depth across JavaScript, TypeScript, Python, Go, Java, C++, React, Next.js, Node.js, NestJS, Flask, and PostgreSQL with modern cloud deployments on AWS. Strong expertise in version control (Git), code quality, coding standards, debugging complex issues, code reviews, and collaborative development workflows.

%----------WORK EXPERIENCE----------
\section{Work Experience}

\begin{itemize}[leftmargin=0em, label={}]

\resumeSubheading
{LawnStarter}{July 2022 -- Present}
{Full Stack Engineer}{US (Remote)}
\begin{itemize}[leftmargin=1.5em]
  \resumeItem{Redesigned customer-facing marketing sites from legacy templates to \textbf{Next.js 15 + React 19 + TypeScript}, improving page load times by \textbf{40\%} and SEO scores, driving measurable organic traffic growth.}
  \resumeItem{Built a \textbf{Flask}-based content management and AI-powered optimization tool with automated SERP analysis, content gap detection, and WordPress REST API integration, reducing editorial turnaround by \textbf{60\%}.}
  \resumeItem{Developed an interactive ROI calculator using Next.js, Recharts, and \textbf{@react-pdf/renderer} with state-specific data models, deployed on \textbf{Cloudflare Workers} as an embeddable widget for partner sites.}
  \resumeItem{Built \textbf{9+ production-ready full-stack sites} for the Home Gnome project, delivering end-to-end features with \textbf{Next.js, TypeScript, and Node.js}, applying \textbf{Git} branching, merging, and CI/CD pipelines.}
  \resumeItem{Designed and developed \textbf{RESTful APIs} end-to-end with Node.js and Flask, authored technical specifications and API contracts, deployed services on \textbf{AWS EC2/ECS} with automated testing via \textbf{Jest} and \textbf{PyTest}.}
    \resumeItem{Built an automated workflow integrating \textbf{GA4, GSC, and Airtable} for real-time traffic management.}
\end{itemize}
\resumeSubheading
{Metopio}{Mar 2024 -- Present}
{Web Developer (Part-time)}{US (Remote)}
\begin{itemize}[leftmargin=1.5em]
  \resumeItem{Built \textbf{40+ custom-branded Health Atlas sites} for hospitals and public health departments using \textbf{Vue.js, Contentful CMS, and Django/PostgreSQL}, powering Community Health Assessments (CHA) and Community Health Improvement Plans (CHIP) across 475+ organizations.}
  \resumeItem{Developed interactive data visualization dashboards with \textbf{D3.js, Mapbox, and Python} for mapping health disparities, enabling stakeholders to explore community-level datasets serving \textbf{20M+ people}.}
  \resumeItem{Integrated \textbf{Google Analytics and custom event tracking} across client sites, enabling data-driven decision-making and measurable engagement improvements for public health stakeholders.}
  \resumeItem{Conducted \textbf{code reviews}, debugged complex issues across large codebases, and enforced \textbf{coding standards and best practices}, improving code quality and maintainability.}
\end{itemize}

\resumeSubheading
{Upwork -- Top Rated Plus Freelancer}{Sep 2021 -- Present}
{Full Stack Software Developer}{Remote}
\begin{itemize}[leftmargin=1.5em]
  \resumeItem{\textbf{FuzeGenAI}: Built a full-stack SaaS platform from scratch using \textbf{NestJS + Prisma + PostgreSQL} backend and \textbf{React 19 + TanStack Router} frontend in a \textbf{pnpm + Turborepo} monorepo.}
  \resumeItem{Designed and scaled \textbf{35+ server-side modules} including Bull job queues, WebSocket (Socket.io), rate limiting, Stripe payments, and Swagger API docs with comprehensive \textbf{Jest and Mocha} test suites.}
  \resumeItem{Deployed on \textbf{AWS} (ECS Fargate, CloudFront, S3, RDS) with Docker, \textbf{GitHub Actions CI/CD}, Sentry monitoring, and Winston + Axiom observability.}
\end{itemize}

\end{itemize}

%----------EDUCATION----------
\section{Education}

\begin{itemize}[leftmargin=0em, label={}]
\resumeSubheading
{University of Manitoba}{Sep 2024 -- Dec 2026 (Expected)}
{Master of Science (M.Sc), Electrical and Computer Engineering}{Winnipeg, Canada}
\end{itemize}

%----------SKILLS----------
\section{Skills \& Interests}
\textbf{Skills:} Python, JavaScript, TypeScript, Go, Java, C++ \,$\bullet$\, React, Next.js, NestJS, Node.js, Flask, Django, Vue.js, TanStack, Tailwind \,$\bullet$\, AWS (EC2, ECS, RDS, S3, CloudFront, Amplify, Route\,53, Lambda), Azure, GCP, Docker, Terraform \,$\bullet$\, PostgreSQL, Redis, Prisma, REST API Design, GraphQL, Swagger/OpenAPI \,$\bullet$\, Git (Branching, Merging, Collaborative Workflows), Code Reviews, Test-Driven Development (TDD), CI/CD, Debugging, Technical Specifications, Software Architecture \,$\bullet$\, Jest, PyTest, React Testing Library, Supertest

\end{document}
