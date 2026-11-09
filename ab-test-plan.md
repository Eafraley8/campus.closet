# A/B Test Plan: Hawkeye Hanger Home Page

## Tested Page & Element
- **Page:** Home page (`index.html` vs `index-b.html`)
- **Version A (Control Headline):** "The Ultimate Student Clothing Exchange for Iowa Students"
- **Version B (Treatment Headline):** "Score Designer Formal & Game Day Outfits Without the Retail Price"
- *(Note: All styling, layout spacing, images, and other text remain 100% identical between versions).*

## Hypothesis
Changing the home page hero headline from a general description (Version A) to a direct value proposition emphasizing savings on formal and game day wear (Version B) will increase AI visitor intent to use the platform because it immediately highlights financial utility for college students.

## AI Model & Prompt
- **Model:** Google Gemini 1.5 Pro
- **Persona:** You are a University of Iowa undergraduate student looking for affordable clothing options for upcoming campus events and game days.
- **Exact Prompt:** "Read this home page text: [Page Text]. Based on this page, would you use this student clothing exchange service? Answer yes or no, followed by one sentence of reasoning."

## Trial Assignment & Outcome Measurement
- **Assignment:** Pre-determined 50/50 random distribution using a random number generator.
- **Primary Outcome:** Binary response (Yes = 1, No = 0).
- **Sample Size:** 100 total trials (50 for Version A, 50 for Version B).
- **Target Completion Date:** November 24, 2026.
