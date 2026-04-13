# just-trying-out-here
Project Overview
In a city like Paris, there's waay too many coffee shops. How do you select the best one on a sunny day vs cloudy day, a morning post run latte vs evening chill catch-up with friends? A perfect summer terrasse is often too drafty for a winter work session. VibeCurrent is a data-driven prototype that solves the "static map" problem by providing contextual recommendations based on seasonality and real-time density.
The Goal: To demonstrate how AI-assisted data curation and real-time API integration can enhance urban discovery and user experience (UX).
:rocket: Strategic Features
• Dual-Vibe Taxonomy: Unlike Google Maps, which provides one generic description, this dataset categorizes locations by Summer Vibe (Airy/Outdoor) and Winter Vibe (Cozy/Coconing).
• Live Busyness Logic: Built to interface with the Google Places API to trigger "Peace & Quiet" alerts when a shop is at <40% capacity.
• Segmented Targetting: Categorizes shops by user intent (e.g., Digital Nomad Hub, Hidden Gem, Social Hub).
:hammer_and_wrench: The Tech Stack (AI-Orchestrated)
• Data Curation: Engineered prompts for Gemini 3 Flash to synthesize unstructured review data into structured seasonal profiles.
• Data Structure: Managed via .xlsx and .json for easy injection into No-Code builders (Glide/Softr).
• Automation (Planned): GitHub Actions to trigger daily data refreshes via the Google Maps API.
:open_file_folder: Repository Structure
• data/: Contains the master Paris_18eme_Vibe_Map_Data.xlsx.
• prompts/: Documentation of the System Prompts used to analyze the coffee shop "vibes."
• roadmap/: A strategic look at scaling this to the 11th and 10th Arrondissements.
:chart_with_upwards_trend: Business Impact & Scalability
This framework is designed for Scalable Personalization. By applying this logic to retail or hospitality sectors, businesses can:
1.	Reduce Churn: Send users to "low-density" locations during peak hours to improve satisfaction.
2.	Increase Engagement: Present seasonally-relevant content that resonates with the user's immediate environment.
