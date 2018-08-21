---
published: false
---
# National Stock Exchange of India

Put it simply, National Stock Exchange is a marketplace where the equity of publicly listed companies are traded. As of 13th August 2018, there are a total of 1638 companies listed on NSE. These companies could be categorised into 22 broad industries (one of which is miscallaneous). 

The list of industries are captured in the below list:

1. :blue_car: Automobiles
2. :bank: Banking/Finance
3. :construction: Cement/Construction
4. :microscope: Chemical
5. :office: Conglomerate
6. :tv: Consumer Durable
7. :bread: Consumer Non Durable
8. :wrench: Engineering
9. :fries: Food and Beverages
10. :moneybag: Gold ETF
11. :hammer: Manufacturing
12. :minidisc: Media & Entertainment
13. :man_with_gua_pi_mao: Metals and Mining
14. :rainbow: Miscallaneous
15. :factory: Oil and Gas
16. :pill: Pharmaceuticals
17. :department_store:Retail/Real Estate
18. :package: Services
19. :computer: Technology
20. :telephone_receiver: Telecom
21. :smoking: Tobacco
22. :nut_and_bolt: Utilities

Now let's try to answer some basic questions to get a better understanding of the NSE.

~~~
How big is NSE?
~~~

The total market capitalization of companies listed on the NSE is approximately $ 2.15 trillion. Now to give you an idea this is approximately equal to India's GDP in 2016 quoted by World Bank as $ 2.28 trillion.

~~~
What kind of companies constitute NSE?
~~~

To answer this question, we have divided companies into 7 categories based on the their market cap size.

```chart
{
  "type": "bar",
  "data": {
  "labels": [
    "<100 Cr",
    "100 Cr - 500 Cr",
    "500 Cr - 1000 Cr",
    "1K Cr - 5K Cr",
    "5K Cr - 10K Cr",
    "10K Cr - 50K Cr",
    ">50K Cr"
    
  ],
  "datasets": [
    {
    "label": "# of companies by market cap size",
    "data": [
      352,
    358,
162,
427,
99,
180,
61
    ],
    "backgroundColor": [
      "rgba(255, 10, 10, 0.2)",
      "rgba(175, 10, 10, 0.2)",
      "rgba(10, 206, 10, 0.2)",
      "rgba(10, 175, 10, 0.2)",
      "rgba(10, 150, 10, 0.2)",
      "rgba(10, 10, 164, 0.2)",
      "rgba(10, 10, 255, 0.2)"
    ],
    "borderColor": [
      "rgba(255, 10, 10, 0.2)",
      "rgba(175, 10, 10, 0.2)",
      "rgba(10, 206, 10, 0.2)",
      "rgba(10, 175, 10, 0.2)",
      "rgba(10, 150, 10, 0.2)",
      "rgba(10, 10, 164, 0.2)",
      "rgba(10, 10, 255, 0.2)"

    ],
    "borderWidth": 1
    }
  ]
  },
  "options": {}
}
```

~~~
How many companies are there in each industry?
~~~

The first cluster contains than 100 listed companies each.  In this cluster, most number of listed companies are in the Manufacturing industry (210), followed by Banking and Finance (167). The Engineering (131), Chemical (105) and Technology (105) industries are other members of this cluster. If you observe this cluster closely, you would notice that all most all of the industries are capital intesive this category.

The second cluster contains the industries having between 50-100 companies. Cement Construction (95) and Metals and Mining (89) are the leaders in the second cluster. Pharmaceuticals (85), Services (83), Food and beverages (80) and Automobiles (81). Real Estate (51) just makes this cluster.

The third cluster contains all the remaining industries. This cluster includes Media and Entertainment (47), Telecom (32), Conglomorates (30), Oil and Gas (21), Utilities (26), Consumer non-durables (29), Consumer durables (11) and all other 150 niche categories clubbed as others.

~~~
How do industries compare against each other based on their relative size?
~~~

The following table ranks the industries based on their total market capitalization (in INR thousand Cr) values:

Rank| Company  |Toal Market Cap (in INR thousand Cr)
----| ---------|---------------------------------
1|	Banking/Finance	|3416
2|	Technology	|1640
3|	Oil and Gas	|1463
4|	Automobiles	|1117
5|	Metals and Mining	|762
6|	Consumer Non Durable	|761
7|	Pharmaceuticals	|741
8|	Engineering	|682
9|	Miscallaneous	|588
10|	Chemical	|555
11|	Cement/Construction	|427
12|	Food and Beverages	|411
13|	Tobacco	|379
14|	Utilities	|364
15|	Conglomerate	|355
16|	Manufacturing	|353
17|	Retail/Real Estate	|312
18|	Telecom	|311
19|	Services	|273
20|	Media & Entertainment	|141
21|	Consumer Durable	|55
22|	Gold ETF	|1


~~~
Who are the topgun companies in each industry?
~~~

For this let's go cluster by cluster.

For the most crowded sector the list is captured in the below graph:

```mermaid
graph TD
A[Cluster 1] --> C{Industries with </br> >100 companies}
C -->|Manufacturing| D[Page Industries </br> Bharat Elec </br> Bharat Forge </br> CG Consumer </br> Supreme Ind </br> Astral Poly Tec</br> Sundram </br>Max Financial</br> SRF </br>Arvind]
C -->|Engineering| E[Aarti Ind</br>Larsen</br>Adani Ports</br>Havells India</br>Siemens</br>BHEL</br>Graphite India</br>Cummins</br>HEG</br>AIA Engineering</br>Quess Corp]
C -->|Technology| F[TCS</br>Infosys</br>Wipro</br>HCL Tech</br>Tech Mahindra</br>Oracle Fin Serv</br>L&T Infotech</br>MphasiS</br>Mindtree</br>L&T Technology]
C --> |Banking & Finance| G[HDFC Bank</br>HDFC</br>SBI</br>Kotak Mahindra</br>ICICI Bank</br>Bajaj Finance</br>Axis Bank</br>IndusInd Bank</br>Bajaj Finserv</br>Yes Bank]
```

```mermaid
graph TD
A[Cluster 2] --> C{Industries with </br> > 50-100 companies}
C -->|Automobiles| D[Maruti Suzuki</br>M&M</br>Eicher Motors</br>Bajaj Auto</br>Tata Motors</br>Hero Motocorp</br>Motherson Sumi</br>Bosch</br>Ashok Leyland</br>MRF]
C -->|Cements &</br>Construction| E[UltraTechCement</br>Shree Cements</br>Ambuja Cements</br>ACC</br>Dalmia Bharat</br>Ramco Cements</br>Dilip Buildcon</br>Kajaria Ceramic</br>Rain Industries</br>OCL India]
C -->|Foods and Beverages| F[Nestle</br>Britannia</br>United Spirits</br>United Brewerie</br>GlaxoSmith Con</br>Tata Global Bev</br>Varun Beverages</br>Hatsun Agro</br>Bombay Burmah</br>KRBL]
C --> |Metals &</br>Mining| G[Coal India</br>Hind Zinc</br>JSW Steel</br>Vedanta</br>Tata Steel</br>Hindalco</br>NMDC</br>SAIL</br>Jindal Steel</br>NALCO]
C --> |Pharamaceuticals| H[Sun Pharma</br>Cipla</br>Piramal Enter</br>Dr Reddys Labs</br>Lupin</br>Cadila Health</br>Aurobindo Pharm</br>Biocon</br>Divis Labs</br>Torrent Pharma]
C --> |Metals &</br>Mining| I[Avenue Supermar</br>DLF</br>Future Retail</br>Oberoi Realty</br>Godrej Prop</br>Aditya Birla F</br>Trent</br>HUDCO</br>Phoenix Mills</br>Prestige Estate]
C --> |Services| J[Interglobe Avi</br>Container Corp</br>Adani Enterpris</br>Rajesh Exports</br>Indian Hotels</br>Apollo Hospital</br>EIH</br>Blue Dart</br>Aegis Logistics</br>Fortis Health]
```
```mermaid
graph TD
A[Cluster 3] --> C{Industries with </br> <50 companies}
C -->|Media &</br>Entertainment| D[Zee Entertain</br>Sun TV Network</br>Dish TV</br>TV18 Broadcast</br>PVR</br>DB Corp</br>JagranPrakashan</br>Ent Network</br>Ind TV</br>TodayNetwork</br>INOX Leisure]
C -->|Consumer</br>Durables &</br> Non-durables| E[Whirlpool</br>Symphony</br>TTK Prestige</br>Blue Star</br>Bajaj Electric</br>IFB Industries</br>HUL</br>Godrej Consumer</br>Dabur India</br>Marico</br>P and G</br>Colgate</br>Emami</br>Gillette India</br>Godrej Ind]
C -->|Telecom|F[Bharti Airtel</br>Bharti Infratel</br>Idea Cellular</br>Honeywell Autom</br>Tata Comm</br>Sterlite Techno</br>Finolex Cables</br>ITI</br>Reliance Comm]
C -->|Utilities &</br> Oil & Gas|G[NTPC</br>Power Grid Corp</br>NHPC</br>Tata Power</br>CESC</br>NLC India</br>SJVN</br>JSW Energy</br>Torrent Power</br>Reliance Infra</br> Reliance </br>ONGC </br>IOC</br>GAIL</br>BPCL</br>HPCL</br>Petronet LNG</br>Oil India</br>IGL</br>MRPL]
C -->|Conglomorates|H[SBI Life Insura</br>Grasim</br>General Insuran</br>ICICI Lombard</br>Hindustan Aeron</br>3M India</br>Voltas</br>Century</br>DCM Shriram</br>Bombay Dyeing]
C -->|Others-</br>Gold & ETF,</br>Tobacco,></br>etc.|I[HDFC Gold ETF</br>UTI - Gold</br>R ETF Gold BeES</br>SBI Gold ETF</br>IDBI Gold ETF</br>Birla Gold ETF</br>Invesco India</br>ITC</br>HDFC Life</br>Titan Company</br>New India Assur</br>AB Capital</br>Jubilant Food</br>Info Edge</br>Adani Trans</br>Bharat 22 ETF</br>Reliance Nippon</br>Infibeam Incorp]
```

To give you an idea, the companies mentioned above alone constitute about INR 118 lakh crore of market capitalization or 78% or NSE's total market capitalization.

So that completes the introduction of NSE of India. Hope you enjoyed reading the article!