# DIYAR engineering notes

## Two audiences

The public side is designed for visitors comparing properties and reading listing details. The administrative side lets the client maintain listings and media separately from the visitor experience. Public screenshots in this repository show the website as delivered and contain no administration views.

## Application design

- **Routing.** Next.js serves localized routes for property lists and listing details. Visitors can navigate to property and contact pages from the public site.
- **Persistence and media.** The server uses Drizzle ORM with PostgreSQL for structured application data. Media and the associated listing information are handled through the content workflow.
- **Translation.** A server-side integration with Gemini supports translation of content. This showcase describes the capability without exposing prompts, configuration, or internal routes.
- **Delivery.** I handled client communication, prototyping, branding, interface design, implementation and delivery.

The documentation does not include a self-hosting guide because it contains no application source or client infrastructure. [View the public website](https://diyar.rs/).
