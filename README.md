🤖 AI & Automation Work Portfolio
A collection of hands-on AI projects spanning test automation, LLM evaluation, and AI-assisted QA — focused on measurable impact.


Featured Projects
1. AI-Powered Test Case Import Automation
Tools: Goose AI Agent · Test Management System
Impact: ⚡ 95% reduction in manual test case creation time

Built an end-to-end automation workflow using Goose to intelligently import test cases into the test management system. The workflow eliminated repetitive manual entry, accelerated test coverage for new features, and freed QA engineers to focus on higher-value exploratory and edge-case testing.

Key highlights:

Designed the automation pipeline from scratch using agentic AI tooling
Integrated Goose directly into the existing test management ecosystem
Enabled near-instant test case population for new feature cycles


2. LLM Evaluation Strategy — "Moneybot"
Tools: Custom prompt testing · Adversarial scenario design
Domain: Financial AI feature (conversational agent)

Designed and executed a comprehensive evaluation framework for a production LLM-powered feature. Covered the full spectrum of quality assurance needs for conversational AI:

Prompt-based testing — systematic variation of user inputs to surface inconsistency
Edge-case discovery — boundary inputs, ambiguous queries, and unexpected user paths
Adversarial scenarios — attempts to elicit incorrect, harmful, or off-policy responses
Multi-turn validation — ensuring coherent, context-aware responses across conversation threads

This work established repeatable evaluation patterns that can scale to future LLM features.


3. AI-Assisted QA for Families Platform
Tools: Cursor · Claude AI
Impact: 🚀 20% reduction in regression test cycle time

Used AI coding assistants to generate end-to-end and edge-case test scenarios for the Families product. This accelerated QA planning cycles significantly — scenarios that previously required hours of manual authoring were produced and refined in minutes.

Key highlights:

Paired with Claude AI for scenario ideation and edge-case coverage
Used Cursor for rapid iteration on test scripts
Improved regression coverage breadth without proportional time investment


4. Hack Week — Family Balance Feature Prototype
Domain: Fintech · Teen finance · Family accounts
Type: Prototype / innovation project

Led a Hack Week project to prototype a Family Balance feature addressing a real user need: teens needing emergency access to shared family funds, with parent-controlled top-ups.

Identified and framed a genuine gap in the product's family financial toolset
Prototyped the core feature end-to-end during a time-boxed sprint
Addressed trust, safety, and UX considerations for a sensitive financial use case


🧪 Prompt Engineering for QA
Prompt-Based Test Case Generation
Type: Reusable QA Prompt · AI-Assisted Testing
Use case: Comprehensive web page test case generation from a URL, PRD, and design doc

A production-ready prompt engineered to generate a complete, non-duplicate test suite for any web page — using only a URL, a PRD, and a design document as inputs. Built to cover the full breadth of modern QA practice: UI, functional, animation, edge cases, cross-browser, and accessibility — in a single pass.

What it covers:

Coverage Area
What's Tested
UI & Visual
Every button, link, icon, image, input field, label, and text block
Functional
Every user action and flow described in the PRD
Animations & Transitions
Completion within 300ms or visible loading indicator; flags janky states
Boundary & Edge Cases
Empty/max-length inputs, special chars, network failures, JS/cookies disabled, 320px–2560px viewports, rapid repeated clicks
Cross-Browser
Chrome, Firefox, Safari, Edge (latest versions)
Accessibility
Keyboard navigation, visible focus states, screen reader labels
Spec Mismatch
Flags any discrepancy between PRD, design doc, and live page as a dedicated test case


Output format: A structured table with columns TC# | Section | Test Case Name | Pre-conditions | Test Steps | Expected Result | Pass/Fail

Design decisions:

Test steps written as numbered sub-steps so a non-technical person can follow without prior knowledge
De-duplication rule built in — no two test cases test the same thing
Animation expected results include explicit duration or loading indicator requirement
Strict non-inference rule — prompt will not assume features absent from the page or docs



The Prompt:

You are a senior QA engineer. Generate a comprehensive, non-duplicate set of test cases for the web page and documents provided below.

Inputs:

* Website URL: [URL]

* PRD: [paste or attach]

* Design Doc: [paste or attach]

Coverage requirements — include ALL of the following:

1. UI & Visual — every button, link, icon, image, input field, label, and text block visible on the page

2. Functional — every user action and flow described in the PRD and visible on the page

3. Animations & Transitions — every animation, page transition, hover effect, and loading state must complete within 300ms or display a visible loading indicator; flag any that feel janky or block interaction

4. Boundary & Edge Cases — empty inputs, maximum-length inputs, special characters, network failures, JS/cookies disabled, extreme viewport sizes (320px–2560px), and rapid repeated clicks

5. Cross-browser — Chrome, Firefox, Safari, and Edge (latest versions)

6. Accessibility — keyboard navigation, visible focus states, and screen reader labels for all interactive elements

Output format: Return a table with these exact columns:

TC# | Section | Test Case Name | Pre-conditions | Test Steps | Expected Result | Pass/Fail

Rules:

* De-duplicate before outputting — no two test cases should test the same thing

* Write test steps as numbered sub-steps (e.g., 1. Go to… 2. Click… 3. Observe…) so a non-technical person can follow them without any prior knowledge

* For animations specifically: state the expected duration or loading indicator in the Expected Result column

* Do not infer or assume features that are not visible on the page or described in the PRD/Design doc

* Flag any discrepancy between the PRD, Design doc, and the live page as a separate "Spec Mismatch" test case

Test cases generated 
https://docs.google.com/document/d/1gHQsx0Nz8Z1Q8JqPFk4PcWcA2DR7MDrVgkDMS4O00bw/edit?tab=t.0




What I'm Exploring Next
Building structured LLM eval harnesses (datasets, scorers, automated runs)
Contributing to open-source AI testing tooling
Deepening expertise in RAG system evaluation and hallucination detection
Documenting prompt engineering patterns for QA use cases




This portfolio documents real work completed as part of AI integration and QA roles. Quantified impacts reflect internal metrics at the time of project completion.

