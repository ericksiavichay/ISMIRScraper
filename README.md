# ISMIRScraper
Scrapes ISMIR.net website for paper information

# Instructions
0. Clone repo
1. Setup conda environment via CL in local repo
```
conda create -p ./.conda python=3.8
conda activate ./.conda
```
2. Install requirements
```
pip install -r requirements.txt
```
3. (optional) add OpenAI API key for automated extraction
```
echo "export OPENAI_API_KEY='yourkey'" >> ~/.zshrc
source ~/.zshrc
echo $OPENAI_API_KEY
```
4. Edit python file to add URLs of websites you want to scrape
5. Run program
```
python zenodo_scraper.py
```
