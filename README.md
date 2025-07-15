Extracts PSE listed company metadata using cmpy_id and security_id
Uses the link from edge.pse.com to extract latest data. https://edge.pse.com.ph/companyPage/stockData.do?cmpy_id=COMPANY_IDsecurity_id=SECURITY_ID
stock_directory.json has each company's unique cmpy_id and security_id (NOTE: still not complete, still scraping for the rest).
ph_stock_scraper.py parses the data using the scrape_andparse() function.
