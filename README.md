# EvaluationOfSoilTestKits
Bachelor thesis project 2021 on the evaluation of soil test kits and the assessment based on accuracy, ease-of-use, cost and time. 

#RawData_TestKit_Lab -> Contains results for each soil sample tested on nitrate, phosphate, potassium (and twice acidity) per test-kit. 

RawData_TEstKit_Lab %>%
  RawData_TestKit_Lab$Rapitest %>%
        Results for nitrate, phosphate, potassium and pH for 10 soil samples as tested by Rapitest test-kit. 
        Results for nitrate, phosphate, potassium and pH are converted to Low, Medium, High categories for later statistical analysis. 
        Depleted and deficient were categorized as Low, Adequate and suficient were categorized as Medium, and surplus was categorized as High. 
        Sheet also contains the assessment time of each test. 
        
  RawData_TestKit_Lab$LusterLeaf %>%
        Results for nitrate, phosphate, potassium and pH for 20 soil samples as tested by LusterLeaf test-kit. 
        Results for nitrate, phosphate, potassium and pH are converted to Low, Medium, High categories for later statistical analysis. 
        Depleted and deficient were categorized as Low, Adequate and suficient were categorized as Medium, and surplus was categorized as High. 
        Sheet also contains the assessment time of each test.

   RawData_TestKit_Lab$Milwaukee %>%
        Results for nitrate, phosphate and potassium for 20 soil samples as tested by Milwaukee test-kit. 
        Depleted and deficient were categorized as Low, Adequate and suficient were categorized as Medium, and surplus was categorized as High. 
        Sheet also contains the assessment time of each test.
        
   RawData_TestKit_Lab$LabResults %>%
        Results for nitrate, phosphate and potassium for 20 soil samples as tested by in de lab of Unversity of Amsterdam. 
        Nitrate and phosphate were calculated into ppm. Macronutrients were categorized into Low, Medium, High for statistical analysis
        Conversion tables were used frrom sheet OrdinalCategories
        
  RawData_TestKit_Lab$OrdinalCategories %>%
        Contains conversion tables from LusterLeaf Products and Milwaukee Electronics Kft. used to convert quantitative lab data into ordinal data. 
        



#TestKit_ComparedTo_Lab -> Contains converted Test-kit data compared to lab data used for statistical analysis and data vizualization. 
        
        
                                
