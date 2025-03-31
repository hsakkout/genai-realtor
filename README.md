# genai-realtor


## Abstract

This repo demonstrates core GEN AI functionality that could be incorporated into a simple web-based app that generates tailored listings for a Realtor's Home Listings website.

The app receives user preferences via a form, and then implements filtering in combination with semantic search to find appropriate listings for the user. It then generates augmented listing descriptions that are especially tailored for the specific user's requirements and tastes.

Both the generation of artificial data for the listings db and the app itself demonstrate the use of several GenAI solution technologies:

- LangChain OpenAI prompting pipeline (simple)
- VectorDB Embeddings and Retrieval
- Stable Diffusion model for prompted CV image generation
- RAG-based Augmented listing descriptions tailoring in user-specific requirements

The Repo was written to fulfill one of multiple requirements for the Udacity Generative AI Nanodegree Certification 03/2025.

## Use Instructions

The Repo contains the following:

### CODE

- `HomeMatch.ipynb` A Jupyter Notebook showcasing the core functionality.  The Notebook is self explanatory

- `Requirements.txt` This lists the most critical packages used and their versions (it is not intended to be comprehensive)

### DATA

- `LISTINGS FOR SUBMISSION.pdf` A PDF showing an example output, which is a requirement for the Udacity submission.  This is duplicated from the auto-generated source file `home_match_all_results.pdf`

- `home_listings_1.csv` A CSV showing example listings generated using LangChain w/OpenAI

- `property_\*.csv` Sample generated images for the above listings

- `user_preferences_\*.csv` Sample user requirements generated using the form.  These can be supplemented or replaced

### DIRECTORIES

The Data is organized in the following self-explanatory subdirectories:

- `generated_csvs`

- `generated_images`

- `generated_pdfs` This also contains htmls used to generate PDFs
