# Oleksii Gryshchenko

**Frontend Engineer \| React \| Next.js \| TypeScript**

<table>
<tr>
<td width="200" markdown="1">

<img src="assets/photo.png" alt="Oleksii Gryshchenko" width="200" />

</td>
<td valign="top" markdown="1">

## Contact

- 📍 Dnipro, Ukraine
- 💼 [LinkedIn](https://linkedin.com/in/oleksiy-grishchenko)
- ✈️ Telegram: [@alexdjnett](https://t.me/alexdjnett)
- 🎮 Discord: oleksiygrishenko
- 🐙 GitHub: [github.com/AlexJsNett](https://github.com/AlexJsNett)

</td>
</tr>
</table>

## About Me

Frontend Engineer with 4+ years of experience, currently owning frontend work across 3 concurrent products at a product-driven marketing tech company. Spent most of that time close to the business side of engineering: building and rebuilding funnel systems to make them faster to ship, wiring up the analytics that let marketing teams see what's working, and designing CMS and admin tooling so non-engineers can manage content without filing a ticket.

Comfortable going beyond the frontend when a feature needs it — touching CMS backends, databases, and even reading/adjusting other teams' backend code with AI-assisted tools when a fix has to happen fast. Now deliberately building out the backend half of that picture: learning NestJS, TypeORM, and PostgreSQL to move from "frontend engineer who can read backend code" to full-stack.

## Skills

- **Programming Languages:** JavaScript (ES6+ / ES2024), TypeScript
- **Frameworks & Libraries:** React, Next.js, Redux Toolkit, Apollo GraphQL, jQuery
- **UI & Styling:** Tailwind CSS, Shadcn/ui, Chakra UI, Material UI, Ant Design, SCSS, CSS, HTML5
- **Backend & CMS:** Node.js, Strapi, PostgreSQL, AWS, REST API, ModX, Contentful
- **Learning / Full-Stack Direction:** NestJS, TypeORM, PostgreSQL
- **Analytics & Growth:** Amplitude, Meta Pixel (Facebook Pixel), Facebook Conversions API (CAPI), A/B Testing
- **Architecture & Practices:** Feature-Sliced Design (FSD), Software Design Patterns, Technical SEO (SSR/SSG, Schema.org), Agile/Scrum
- **AI-Assisted Development:** Claude Code, Cursor, Warp Terminal
- **Tools:** Git, GitHub, DBeaver

## Code Examples

Solutions to two Codewars katas:

**XO ("Does the string have the same amount of 'x's and 'o's?")**

```js
function XO(str) {
  let x = 0;
  let o = 0;

  str.split('').forEach((el) => {
    if (el.toLowerCase() === 'x') x++;
    if (el.toLowerCase() === 'o') o++;
  });

  return x === o;
}
```

**Maskify ("Mask a credit card number leaving only the last 4 digits visible")**

```js
function maskify(cc) {
  if (cc.length <= 4) {
    return cc;
  }

  return '#'.repeat(cc.length - 4) + cc.slice(-4);
}
```

## Work Experience

### Frontend Engineer — Genesis Tech, Dnipro, Ukraine (Remote)
*May 2025 – Jul 2026 · Marketing/Product team, 3 concurrent products*

- Owned frontend development as a core engineer across 3 concurrent products, from architecture and scoping through production delivery.
- Built a config-driven, multi-step quiz and funnel platform supporting A/B testing, multi-variant flows, and paywall/checkout integration; reduced funnel production delivery time from 8-10 days to 2-5 days.
- Integrated and maintained analytics pipelines using Amplitude, Meta Pixel, and Facebook Conversions API (CAPI), tracking user journey events from first funnel step to completed purchase.
- Led a redesign of a real-time chat interface (mobile and desktop), integrating a third-party TTS provider, animated media, a gift market system, and AI character creation flows.
- Designed a headless CMS from scratch using Strapi, PostgreSQL, and AWS, paired with a Next.js frontend via Apollo GraphQL and static site generation (SSG).
- Implemented technical SEO across multiple products: structured data (Schema.org), canonical URLs, dynamic meta tags, robots.txt management, and SSR/SSG optimization.
- Optimized Core Web Vitals across products (faster load, lower CLS) through funnel performance tuning.
- Worked across Ruby and C# backend code with Claude Code (AI-assisted, not an owned stack) to support pricing, analytics, and funnel logic.

### Frontend Engineer — Lead Panda Agency, Dnipro, Ukraine (Hybrid)
*May 2024 – Jan 2026 · Digital Agency*

- Developed and maintained web applications for internal and external company projects using React, TypeScript, Next.js, and Ant Design; integrated REST APIs and ensured cross-device responsiveness.
- Built an "Information & Services Hub" application with a Strapi CMS backend (Next.js, Strapi, Redux Toolkit, Tailwind CSS, Shadcn/ui), delivered in 3 months.
- Built a company services website with integrated blog, using the same Next.js/Strapi stack, delivered in 3 months.
- Built 2 lead-generation and company presentation landing pages using React, Chakra UI, GSAP, and Framer Motion, each delivered in 1 month.
- Supported layout engineers with website interactivity, load performance optimization, and deployment.

### Frontend Engineer — NLTDev, Dnipro, Ukraine (Hybrid)
*Jan 2024 – May 2024*

- Built an admin panel for customer service management with Algolia-powered search, enabling fast lookup and response to customer inquiries (React, Redux Toolkit, Material UI), delivered in 2 months.
- Built an admin panel for managing purchasable products for children with mobility impairments (React, Redux Toolkit, Chakra UI), delivered in 2 months.
- Collaborated directly with backend engineers to ensure fast data synchronization and system stability.

### Frontend Developer — Pinta Webware, Dnipro, Ukraine
*Dec 2021 – Dec 2023*

- **[Sherridge](https://sherridge.com)** — client-lawyer matching platform; built layout and form logic on a 3-person team (Next.js, Redux Toolkit, Chakra UI, Contentful, GSAP, EJS, MailJet), delivered in 7 months.
- **[c13cloud](https://c13cloud.com)** — finalized an existing creative studio site on a 3-person team (ModX, React, jQuery, HTML, CSS), delivered in 4 months.
- **[Paymentfox](https://paymentfox.org)** — built a crypto wallet operations site solo (Next.js, Chakra UI, Redux Toolkit, Lodash), delivered in 3 months.
- Developed responsive, cross-browser React applications and conducted code reviews to maintain clean, modular code across all projects.

## Education

**Master's Degree, Electrotechnical Systems of Power Consumption**
Dnipro University of Technology · 2012 – 2016

### Certifications

- Analytics in Product IT — Genesis Tech, 2026
- Web Security Online Course 2.0 — Genesis Tech, 2026
- Front-end Architecture Lecture Series — Genesis Tech, 2026
- React Online Marathon — SoftServe, 2021
- JavaScript Fundamentals — SoftServe, 2021

## English

**Level: B1 (Intermediate)**

Practicing regularly with a tutor, plus daily immersion through AI-assisted development workflows (Claude Code) — reading docs, writing prompts, and working through technical discussions in English as part of everyday coding work.
