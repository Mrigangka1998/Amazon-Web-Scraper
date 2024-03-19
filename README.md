# Amazon-Web-Scraper

This notebook aims to scrape data, specifically the price of a product from a specific Amazon page: https://www.amazon.com/Tommy-Hilfiger-Performance-Stretch-Regular/dp/B07HL41FKF/ref=sr_1_2?crid=2RJSFRJZXALTR&dib=eyJ2IjoiMSJ9.OY5fqbXmaP_tkolXO48ZeJaW4bmx3S5Cg9rWuKHS6OCMsBlaB2NLePg9ZgKl7c3rcmcPwjD88biPxxEM98qFgPMY8sNXB6ZNfXQ-9mj8v9-a9Vx-y1u97j_AXcTVy8wtllYTnACHx_XANTgoCCEOKMKNPm2ICtUV-4j1CvAzksyFbAYLm1YN9P2qohu5u-JEIpoJ1TirTb04vGG0BHxbYGctzyfcCO_XlImDbjYFhy5Cg_ILzA66M6w9-nAoq3hrTohl0I_UWwBa0Hgn9ruN2-sL_We10rY77lyoI1B8PKE.q2i2Tk1V0e4pb3_zSXHs063193EQKbdgGPn3nZMlMbc&dib_tag=se&keywords=suits+for+men&qid=1710830278&refinements=p_123%3A232763&rnid=85457740011&s=apparel&sprefix=suit%2Caps%2C274&sr=1-2

This page refers to a men's suit from Tommy Hilfiger. The notebook automates the data collection process by collecting the price every 30 minutes and storing it to a csv file. It also sends out an automatic email alert if the price falls below $100.
