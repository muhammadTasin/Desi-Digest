# Desi Digest Application Answers

These drafts are written for the application fields and stay within their stated word limits.

## Problem Statement

Many people in Bangladesh want to understand their eating habits, but common nutrition apps do not always recognize the meals they cook at home. A meal of bhat, dal, fish, shak or bhorta can vary from one household to another, so finding a close match and estimating a portion can take time. This makes it harder to keep a useful food log, especially for people who prefer Bangla or Banglish or want advice that fits local ingredients and budgets. When tracking feels unfamiliar or burdensome, people may stop using it before it becomes part of their routine. Desi Digest aims to make that first step easier with familiar foods, simple meal logging and practical, general nutrition guidance. It is not a medical diagnosis or treatment tool.

## Proposed Solution

Desi Digest is a mobile friendly nutrition companion built around the way people in Bangladesh eat and talk about food. A user can set personal goals and food preferences, type a meal in Bangla, Banglish or English, or upload a plate photo for an approximate food and portion estimate. They can review meals and nutrition summaries on a dashboard, ask Nanumoni for an explanation, and explore meal ideas that take familiar ingredients and budgets into account.

The app connects tracking with everyday choices. Users can build an ingredient basket, explore nearby markets and share a seven day meal summary with a clinician or family member. These tools are meant to make nutrition easier to understand and use, not to replace professional advice.

Behind the experience, Desi Digest combines a curated local food dataset with meal logging, server side application functions and Supabase storage. AI supports conversation, meal planning, plate photo estimates and personalized nudges. The app makes clear that homemade recipes and portions vary, so estimates are approximate.

The current prototype also includes a read only WebMCP feature. Compatible AI agents can search and compare public food information or explore budget meal ideas. Those tools do not access a user's private profile or meal history.

## How Does AI Enable Your Solution?

AI lets users describe meals and ask questions in their own words. Nanumoni can respond in Bangla, Banglish or English, explain nutrition concepts with local food examples, and suggest meal ideas based on the goals and preferences a user shares. A vision model estimates foods and portions from a plate photo, which can make logging easier when typing every ingredient would take too long.

The prototype uses Gemini, with alternate model and fallback paths when an AI service is unavailable. Some questions are first matched to an intent and checked against local food information or structured response templates. This helps keep answers relevant to Bangladeshi dishes instead of asking a general model to guess from scratch.

AI estimates are not exact measurements. Recipes and portions vary, so the app should explain uncertainty and avoid presenting nutrition guidance as medical advice. Rule based fallbacks and safety checks help keep selected nudges cautious. We will continue reviewing responses with qualified nutrition professionals as the product is tested.

## Impact Potential

Desi Digest could make culturally relevant meal tracking easier for people who find generic food lists unfamiliar or time consuming. It can help users keep a clearer record of what they eat, understand approximate nutrition, and bring a seven day summary to a conversation with a clinician or family member.

Our planning target is to pilot with 100 to 300 adults, then work toward 1,000 registered users in year one and 10,000 by year three, subject to pilot results, retention and partnerships. These are goals, not current user counts.

We will measure the time it takes to log a meal, how regularly people use the tracker, how often they correct food or portion estimates, and changes in self reported confidence about food choices. We will also review a sample of estimates with nutrition professionals and track safety issues. The pilot will tell us whether the product is useful and trustworthy. We will not claim clinical benefits without evidence.

## Feasibility: Execution Plan for the Next 2 to 3 Years

**Months 0 to 6:** Work with a registered dietitian or nutrition scientist to review the local food knowledge, safety language and sample estimates. Run a small pilot with 100 to 300 users and measure usability, logging time, corrections and trust.

**Months 6 to 12:** Improve the product based on feedback. Focus on reliable Bangla and Banglish interactions, clear estimate labels, privacy controls, and performance on lower cost phones and slower connections. Aim for 1,000 registered users if pilot retention supports expansion.

**Year 2:** Expand food coverage and test distribution through community, education or healthcare partners. Evaluate additional locations before scaling, with a planning target of 5,000 registered users.

**Year 3:** Work toward 10,000 registered users, strengthen professional review and product support, and validate a sustainable operating model before wider rollout.

Key resources are a product lead, two full stack engineers, a qualified nutrition reviewer, a Bangla food content researcher, user research support, privacy and security review, and funding for hosting, AI usage and pilot operations. The prototype gives us a starting point, but adoption and health outcomes still need to be validated.

## Differentiation

Desi Digest starts with the foods people actually cook and the languages they use to talk about them. Users can describe meals in Bangla, Banglish or English, get approximate guidance based on familiar dishes, and explore ideas that take local ingredients and budgets into account.

The product brings meal logging, plate photo estimates, conversational help, practical nudges and local food discovery together. The current build also makes its public food dataset available through read only WebMCP tools, so compatible agents can search or compare foods without seeing a user's private profile or meal history. This combination of local food knowledge, personal tracking and a clear privacy boundary is central to what makes Desi Digest different.
