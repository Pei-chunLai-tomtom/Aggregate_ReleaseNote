## Known issues in 25310.000  
General  
geocoding  
[25310.000]Potential duplicate Address Points have been identified in the following countries: IRL, AND, SMR, PRT, ITA, ESP, BRA, CYP, MCO, FRA, HUN, GRC, BEL, USA. The exact count of duplicates is currently being thoroughly checked by the TomTom Addressing Team against our Address Point sources. The count of duplicates could be between 1%-3% in each country, but it can only be confirmed once thorough validation is done. In the USA, the count is likely to be < 0.5%. In IRL (Ireland), PRT (Portugal), AND (Andorra) and SMR (San Marino), the count of duplicates is likely to be higher (i.e. > ~5%). There could be other countries with duplicate APTs, but we expect the % to be significantly lower. Once the count is confirmed for each country, we will provide detailed information about the number of duplicates and their removal via weekly Orbis release notes.  
[25310.000]Address Points for following countries are sourced from OSM and they are not standardized to the Orbis Address Points product specification: ABW, AFG, AGO, AIA, ALB, ARM, ATA, ATF, ATG, BDI, BEN, BES, BFA, BGD, BHS, BLM, BLZ, BMU, BOL, BRB, BTN, BWA, CAF, CIV, CMR, COD, COG, COK, COM, CPV, CRI, CUB, CUW, CYM, DJI, DMA, DOM, ERI, ETH, FJI, FLK, FSM, GHA, GIB, GIN, GMB, GNB, GNQ, GRD, GRL, GUY, HND, HTI, IOT, IRN, IRQ, JAM, JPN, KAZ, KEN, KGZ, KIR, KNA, LBR, LBY, LCA, LSO, MAF, MDG, MDV, MHL, MLI, MNE, MNG, MOZ, MRT, MSR, MUS, MWI, NCL, NER, NGA, NIC, NIU, NPL, NRU, OMN, PAK, PAN, PCN, PLW, PNG, PRK, PSE, PYF, RWA, SDN, SEN, SGS, SHN, SLB, SLE, SLV, SOM, SPM, SSD, STP, SUR, SWZ, SXM, SYC, SYR, TCA, TCD, TGO, TJK, TKL, TKM, TLS, TON, TTO, TUV, TZA, UGA, UMI, UZB, VAT, VCT, VEN, VGB, VUT, WLF, WSM, XAM, XAN, XCP, XHT, XTU, XXS, YEM, ZMB, ZWE. The normalization of Address Points to Orbis Product Specification in these countries will be done in subsequent releases.  
[25310.000]The waterbelt area of a country is not part of any administrative region of the country. The problem doesn't exist for USA, but exists for multiple other countries.  
poi  
[25310.000]Expected regression in Repair facility due to change in source. Major drops in Repair facility for NZL 86 to 74, LTU 68 to 56 and EST 75 to 56. Work in progress to cover the gap, fix version yet to be defined.  
[25310.000]Change of a source resulted in removal of 715k amenity=atm POIs globally. The removal will be filled via alternate sources in upcoming versions.  
visualization  
[25310.000]Identified regression on building parts. The regression occurred during the data processing. This resulted in the loss of detailed representation of Westminster Abbey in London and the Fernsehturm in Berlin. The issue will be resolved by 25330.000 release.  
Australia  
poi  
[25310.000]Loss of Curves branded POIs in AUS from 107 to 60 due to source changes, fix version yet to be defined  
Canada  
visualization  
[25310.000]Hall Lake in CAN is missing due to changes in OSM. The issue will be resolved by 25320.000 release.  
Ireland  
poi  
[25310.000]Loss of Spar branded POIs in IRL from 403 to 242 due to change in source, fix version yet to be defined.  
United States of America  
geocoding  
[25310.000]Some areas USA lack short names populated and only have primary normalized names.  

## Known issues in 25300.000  
General  
geocoding  
[25300.000]The waterbelt area of a country is not part of any administrative region of the country. The problem doesn't exist for USA, but exists for multiple other countries.  
[25300.000]Address Points for following countries are sourced from OSM and they are not standardized to the Orbis Address Points product specification: ABW, AFG, AGO, AIA, ALB, ARM, ATA, ATF, ATG, BDI, BEN, BES, BFA, BGD, BHS, BLM, BLZ, BMU, BOL, BRB, BTN, BWA, CAF, CIV, CMR, COD, COG, COK, COM, CPV, CRI, CUB, CUW, CYM, DJI, DMA, DOM, ERI, ETH, FJI, FLK, FSM, GHA, GIB, GIN, GMB, GNB, GNQ, GRD, GRL, GUY, HND, HTI, IOT, IRN, IRQ, JAM, JPN, KAZ, KEN, KGZ, KIR, KNA, LBR, LBY, LCA, LSO, MAF, MDG, MDV, MHL, MLI, MNE, MNG, MOZ, MRT, MSR, MUS, MWI, NCL, NER, NGA, NIC, NIU, NPL, NRU, OMN, PAK, PAN, PCN, PLW, PNG, PRK, PSE, PYF, RWA, SDN, SEN, SGS, SHN, SLB, SLE, SLV, SOM, SPM, SSD, STP, SUR, SWZ, SXM, SYC, SYR, TCA, TCD, TGO, TJK, TKL, TKM, TLS, TON, TTO, TUV, TZA, UGA, UMI, UZB, VAT, VCT, VEN, VGB, VUT, WLF, WSM, XAM, XAN, XCP, XHT, XTU, XXS, YEM, ZMB, ZWE. The normalization of Address Points to Orbis Product Specification in these countries will be done in subsequent releases.  
[25300.000]Potential duplicate Address Points have been identified in the following countries: IRL, AND, SMR, PRT, ITA, ESP, BRA, CYP, MCO, FRA, HUN, GRC, BEL, USA. The exact count of duplicates is currently being thoroughly checked by the TomTom Addressing Team against our Address Point sources. The count of duplicates could be between 1%-3% in each country, but it can only be confirmed once thorough validation is done. In the USA, the count is likely to be < 0.5%. In IRL (Ireland), PRT (Portugal), AND (Andorra) and SMR (San Marino), the count of duplicates is likely to be higher (i.e. > ~5%). There could be other countries with duplicate APTs, but we expect the % to be significantly lower. Once the count is confirmed for each country, we will provide detailed information about the number of duplicates and their removal via weekly Orbis release notes.  
visualization  
[25300.000]Identified regression on building parts. The regression occurred during the data processing. This resulted in the loss of detailed representation of Westminster Abbey in London and the Fernsehturm in Berlin. The issue will be resolved by 25330.000 release.  
Philippines  
poi  
[25300.000]Regression for McDonald’s branded POIs in PHL has been identified, with loss of 50% branded POIs.  
United States of America  
geocoding  
[25300.000]Some areas USA lack short names populated and only have primary normalized names.  


## Known issues in 25290.000
General  
geocoding  
[25290.000]The waterbelt area of a country is not part of any administrative region of the country. The problem doesn't exist for USA, but exists for multiple other countries.  
Italy  
poi  
[25290.000]In ITA an issue was detected with a specific source supplier, due to which EV stations are getting categorized as normal fuel stations. The impact on the product is more duplicates and 50% more invalid fuel stations. The issue will be resolved in next week's release.  
Switzerland  
geocoding  
[25290.000]In this week’s product release, the postal data update for Switzerland is incomplete to prevent inconsistencies such as duplicate postal points, overlapping districts, or points falling outside their expected boundaries. These are temporary issues and we’re actively working to resolve them and aim to deliver clean and fully aligned map data in upcoming releases.  
United States of America  
geocoding  
[25290.000]Some areas USA lack short names populated and only have primary normalized names.  
## Known issues in 25280.000  
General  
adas  
[25280.000]Traffic signal/light data is missing on ADAS layer for all countries except for FRA, NLD, and KOR. A fix plan is being executed.  
geocoding  
[25280.000]Address Points for following countries are sourced from OSM and they are not standardized to the Orbis Address Points product specification: ABW, AFG, AGO, AIA, ALB, ARM, ATA, ATF, ATG, BDI, BEN, BES, BFA, BGD, BHS, BLM, BLZ, BMU, BOL, BRB, BTN, BWA, CAF, CIV, CMR, COD, COG, COK, COM, CPV, CRI, CUB, CUW, CYM, DJI, DMA, DOM, ERI, ETH, FJI, FLK, FSM, GHA, GIB, GIN, GMB, GNB, GNQ, GRD, GRL, GUY, HND, HTI, IOT, IRN, IRQ, JAM, JPN, KAZ, KEN, KGZ, KIR, KNA, LBR, LBY, LCA, LSO, MAF, MDG, MDV, MHL, MLI, MNE, MNG, MOZ, MRT, MSR, MUS, MWI, NCL, NER, NGA, NIC, NIU, NPL, NRU, OMN, PAK, PAN, PCN, PLW, PNG, PRK, PSE, PYF, RWA, SDN, SEN, SGS, SHN, SLB, SLE, SLV, SOM, SPM, SSD, STP, SUR, SWZ, SXM, SYC, SYR, TCA, TCD, TGO, TJK, TKL, TKM, TLS, TON, TTO, TUV, TZA, UGA, UMI, UZB, VAT, VCT, VEN, VGB, VUT, WLF, WSM, XAM, XAN, XCP, XHT, XTU, XXS, YEM, ZMB, ZWE. The normalization of Address Points to Orbis Product Specification in these countries will be done in subsequent releases.  
[25280.000]The waterbelt area of a country is not part of any administrative region of the country. The problem doesn't exist for USA, but exists for multiple other countries.  
poi  
[25280.000]As a result of removal Parking POIs from a source containing superfluous POIs, there is a lower coverage of Parking attribution such as parking type and parking capacity. A fix plan is being defined.  
8M of TT Proprietary POIs have been unintendedly moved to another locations, which in most of the cases, is a location of respective Address Point. As a result of this more POIs are stacked, especially POIs belonging to a complex venues such as Shopping Malls. This will be fixed in the next product.  
United States of America  
geocoding  
[25280.000]Some areas USA lack short names populated and only have primary normalized names.  

