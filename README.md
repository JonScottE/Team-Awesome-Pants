## Team-Awesome-Pants  
<img src="https://m.media-amazon.com/images/I/81BJWS7Cz4L._AC_SL1500_.jpg" 
     width="220" 
     height="260"
     align="left"/> 




<b>Team Members include:</b>
</br></br>
Tara McDaniel </br> Michelle Fesi </br> Andrei E. Stonescu </br> Lareeb Ali </br> Jon Ernest </br>
</br></br></br>
</br></br>

# requirements for read me, to be deleted before hand in:
Create a README.md in your repo with a write-up summarizing your major findings. This should include a heading for each question you asked of your data and under each heading a short description of what you found and any relevant plots.
# Method and goal

By using historical crypto, stock, and gold data, we will compare:</br>
</br>- Stocks to gold </br>- Altcoins to Bitcoin </br>- Gold to Bitcoin </br>- Altcoins to Stocks
</br></br>
Our goal is to show a correlation of the money flows from the digital market to or from traditional markets. 


# Data Sources
 
 <a href="https://finance.yahoo.com/">Yahoo Finance </a> For GLD & SPY </br>

 <a href="https://api.tiingo.com/">Tiingo </a> For BTC and ETH</br>
 

## Questions

# What are the positive and negative correlations of traditional assets to crypto assets?
We were able to show some correlations among these asset types. </br></br>
Specifically positive correlation between BTC and ETH (represented by the tan color squares) </br>
and a negative correlation between BTC and Gold (represented by the almost purple squares).</br></br>
![NegCorrBTCGLD](https://user-images.githubusercontent.com/91569353/147132006-0fbdcfcc-1187-4ed7-8475-8c6df8cbb429.png)


# Do digital assets track with one another?  
Yes, absolutely. We were able to show a strong correlation between BTC and ETH(represented by the orange squares).</br></br>

![AssetCorrAll](https://user-images.githubusercontent.com/91569353/147132988-2d643c06-ee5d-4f32-a237-6fb7a959b425.png)



# Do traditional assets track with one another?
Inconclusive... once we normalized the prices, the line chart showed some promise for correlation,</br>
however once we actually visualized the correlation between the two, there didn't appear to be a positive correlation of </br>
any statistical significance.</br></br>
![SpyGldLine2](https://user-images.githubusercontent.com/91569353/147141384-1bc1cd37-f026-4b0c-a891-75c9bbfd8fdf.PNG)</br></br>
![SPYGLDCorrBox](https://user-images.githubusercontent.com/91569353/147137627-73fc874d-8553-4524-bec5-eb82ba55ec40.png)</br></br>

Challenges here include:
1) Limited datasets - we really need more than the two traditional assets of Gold and S&P500.
2) Two very opposite datasets in the eyes of investors - as stocks are typically "risk on",</br>
   and gold is typically risk off. Actually because of this we were able to show a slight negative</br>
   correlation between the two asset classes.</br></br>
![SPYGLDNegCorr](https://user-images.githubusercontent.com/91569353/147139153-a2e9a563-ba6f-42b7-b54b-2117ff8d9727.png)</br>
One would not expect this to be consistent over multiple traditional datasets.
        


# Can we find data showing capital inflows/outflows between traditional and digital assets?
Inconclusive. Our strongest finding is the clear inverse relationship between BTC and GLD. </br>
Strongly implying money flows between the two asset classes, but not solidifying it factually. </br></br>
 ![BTC_GLD_Line](https://user-images.githubusercontent.com/91569353/147140508-19c8786c-0135-42f1-9bfc-d9c2ef69d141.PNG)</br></br>
 
 Challenges include:</br>
 1) Lack of transactional volume.
 2) A multitude of other assets options for investors and traders.






