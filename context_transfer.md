# Context Transfer: OpenPublicInfo.ie Website Build

## 1. Project Background & Identity
- **Campaign Name:** Public Info, Public Access - Stop Providing Public Info on Private Social Networks
- **Domain:** `openpublicinfo.ie` (Currently managed via Cloudflare with an originless dummy IP 192.0.2.1 and a 301 Redirect to the petition).
- **Petition Platform:** Uplift (Ireland)
- **Petition Link:** https://my.uplift.ie/petitions/public-info-public-access-stop-providing-public-info-on-private-social-networks
- **Campaign Creator:** Munim Kazia (Senior Software Engineer based in Ireland).
- **Current Status:** Gained rapid momentum over the weekend (breezed past 100 to nearly 700 signatures). The Uplift platform team is reaching out for strategic scaling, and a formal letter/technical brief is being prepared for the NTA (National Transport Authority) and the Minister for Transport.

## 2. The Problem & Core Evidence
Irish public state bodies (primarily transport providers like Irish Rail, Dublin Bus, and the NTA) are routinely treating private social media platforms (specifically X/Twitter) as their primary information distribution hubs. 
- **Case Study/Evidence:** During a recent GAA match (Dublin v Westmeath), Irish Rail posted critical updates about "additional services" exclusively on X. Meanwhile, their official website announcements page remained completely blank. 
- **The Core Argument:** This creates an inaccessible, "Two-Tier Information System." Citizens shouldn't be legally or practically coerced into accepting private data tracking or creating third-party accounts simply to access taxpayer-funded public utility updates.

## 3. The Tech Stack & Design Requirements
- **Framework:** Astro (Static Site Generator) or clean, single-file semantic HTML.
- **Styling:** Tailwind CSS. 
- **Aesthetic:** Minimalist, text/information-dense, professional, high-contrast, "activist-intellectual" style (inspired by Tufte or modern tech whitepapers).
- **Color Palette:** Clean off-white background (`#f8fafc`), dark slate text (`#0f172a`), with a high-visibility accent color (e.g., sharp orange or deep red) restricted exclusively to primary Call-To-Action buttons.
- **Goal:** Replace the current domain redirect with a high-conversion, highly scannable, single-page layout that hosts the evidence, manifesto, and FAQ while maintaining a professional face for public searches.

## 4. Single-Page Architecture & Layout Blueprint

### Section 1: The Hero
- **Headline:** "Publicly funded information belongs on public platforms."
- **Sub-headline:** "Irish Rail, the NTA, and local authorities are increasingly gating real-time service updates behind private social media logins. We are demanding a 'Source First' notification standard."
- **Primary CTA Button:** `[Sign the Petition on Uplift]` (Link to petition)
- **Visual Asset:** Side-by-side comparison banner showing the time-stamped X/Twitter alert vs. the pitifully bare official website.

### Section 2: The Core Demands (The Technical Manifesto)
1. **Primary Sourcing (SSOT):** State-owned websites and apps must be the Single Source of Truth, updated *prior* to or *simultaneously* with third-party networks.
2. **Platform Neutrality:** Essential safety, travel, and health notifications must never require a third-party account or login.
3. **Open Data / Sovereign APIs:** If public entities cannot build reliable distribution tools, they must publish open, standardized API/RSS feeds so citizens and independent developers can safely distribute the data.

### Section 3: Pre-Drafted Campaign FAQ
- **Q: "I use X (Twitter) and it’s convenient. Why change it?"**
  - *A:* We aren't asking them to stop posting to X—we’re asking them to stop posting *exclusively* to X. You can keep using your preferred feed, but vital info shouldn't be "gated." Everyone—including the elderly, the privacy-conscious, and those without accounts—deserves the same real-time updates on a public, state-owned platform.
- **Q: "Does this create extra work for staff to manage two feeds?"**
  - *A:* Actually, it fixes a broken workflow. Right now, staff are "double-jobbing" or prioritizing social media manually. We are advocating for a "Source First" approach: one update to the official system that automatically syncs to the website, the app, and social media simultaneously. It’s about better automation, not more manual labor.
- **Q: "Is this just about train delays?"**
  - *A:* Trains are the most visible example, but this is about a standard for all public bodies—from the Gardaí and local councils to the HSE. Publicly funded information is a public good; it belongs on public infrastructure first.

### Section 4: About & Press Kit
- Include a high-quality professional headshot of the campaign lead.
- A 2-line professional bio emphasizing the engineering perspective: solving an optimization, transparency, and data architectural issue rather than simply lodging a grievance.
- A downloadable asset link (`/press`) containing the case study imagery and a 1-page summary PDF for journalists.

## 5. Instructions for Next Step (Gemini CLI)
Please act as an expert frontend engineer and UI developer. Help me write the boilerplate code for this Astro/Tailwind page, starting with the structural components or a single high-conversion `index.astro` file that beautifully styles the text sections and assets outlined above.


