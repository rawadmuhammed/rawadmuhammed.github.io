# Copilot Instructions

<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

## Project Context
This is a Next.js 15 portfolio project with the following stack:
- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Linting**: ESLint with Next.js config
- **Package Manager**: npm

## Code Style Guidelines
- Use TypeScript for all components and utilities
- Follow Next.js App Router conventions (app directory structure)
- Use Tailwind CSS classes for styling - prefer utility classes over custom CSS
- Use functional components with React hooks
- Follow Next.js best practices for performance (Image optimization, metadata, etc.)
- Use server components when possible, client components only when necessary
- Implement proper SEO with Next.js metadata API

## Component Structure
- Place reusable components in `src/components/`
- Use proper TypeScript interfaces for props
- Follow atomic design principles where appropriate
- Use Next.js Image component for all images

## Tailwind CSS Guidelines
- Use responsive design patterns (mobile-first approach)
- Leverage Tailwind's spacing, color, and typography scales
- Use custom CSS classes sparingly - prefer Tailwind utilities
- Follow semantic color naming for design system consistency

## Performance & Best Practices
- Optimize images using Next.js Image component
- Implement proper loading states and error boundaries
- Use Next.js built-in performance optimizations
- Follow accessibility guidelines (WCAG)
