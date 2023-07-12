# Data Days for Good -- Computer Science Literacy in MA BU Team

The computer science literacy project aims to develop an accessibility score for the sidewalk network in the City of Boston to promote equity, safety, and walkability for all members of the community. By identifying inaccessible sidewalks and potential inequities in accessibility, this project aims to create a more proactive approach to sidewalk maintenance and repair.

# Objectives
Check for Correlations between different ethinic groups % District Contribution with ap scores
Identify correlations between ngo count vs ap scores/passing % different disrticts for lowincome
Develop a proactive sidewalk maintenance strategy based on accessibility scores and prioritization criteria

Understand what factors have an effect on the educational divide across Massachusetts school districts
Inform NGOs and grant-makers to create context-specific reforms and initiatives

# Datasets

Massachusetts Department of Elementary and Secondary Education (DESE)
* School Profiles 
* 2022 Digital Literacy and Computer Science Course Taking Report (District) - All Students, Low Income, and Hispanic/AfricanAmericans/Indigenous Students
* 2021-22 Advanced Placement Performance (Math and Computer Science)

ProPublica Nonprofit Explorer
* Nonprofit Organizations in MA

Mass.gov Shapefile
* MassGIS (Bureau of Geographic Information)



# Progress

This Project serves as a strong baseline to further identify and address social, ethical, racial, and economic inequities with different ethnic groups throughout MA either district or county-wise. 

<!-- To change:

We began by analyzing four key datasets related to the city's infrastructure - Ramps, Roadway Centerline, Sidewalk Hazards, and Sidewalks - to gain a better understanding of the accessibility and safety for pedestrians and individuals with disabilities. By examining these datasets. we were able to gather insights into the city's accessibility infrastructure, including the locations of ramps, the centerlines of roadways, potential hazards on sidewalks, and the extent and conditions of sidewalks throughout the city.

Additionally, we have analyzed information from Boston's public schools to identify the top 5 schools with the most sidewalks within a 15-minute walking distance. 

Furthermore, we expanded our analysis by examining four additional datasets - Public Works Active Work Zones Data, Climate Ready Social Vulnerability Data, 311 Requests, and Census Demographic Data - to gain a comprehensive view of Boston's infrastructure and demographic landscape. This analysis has helped us identify areas of improvement and develop strategies for addressing key challenges facing the city. -->


# File Structure
```markdown

├── Age Exposure for Computer Literacy in Massachusetts.ipynb
├── Priyank
│   ├── Dual-Axis-Box-Plots
│   │   ├── African-American-Box Plot(High vs 3-5%).png
│   │   ├── African-American-Box Plot(Primaryvs3-5%).png
│   │   ├── African-American-Box Plot(Secondary vs 3-5%).png
│   │   ├── Hispanic_Latino-Box-Plot(Highvs3-5%).png
│   │   ├── Hispanic_Latino-Box-Plot(Primaryvs3-5%).png
│   │   ├── Hispanic_Latino-Box-Plot(Secondaryvs3-5%).png
│   │   ├── Others-Box-Plot(Highvs3-5%).png
│   │   ├── Others-Box-Plot(Primaryvs3-5%).png
│   │   └── Others-Box-Plot(Secondaryvs3-5%).png
│   ├── HeatMaps
│   │   ├── Afri-Amer-Black.png
│   │   ├── Hispanic-Latino.png
│   │   └── Others-Asian-White.png
│   ├── Priyank-DDFG-Code.ipynb
│   ├── Priyank-Ethinic-Groups-Profiling-Reports
│   │   ├── Comparison-AfrAmer-HispBlack-Others.html
│   │   ├── District-wise_African_American_CS_Course_Takers_Profiling_Report.html
│   │   ├── District-wise_Hispanic_Latino_CS_Course_Takers_Profiling_Report.html
│   │   └── District-wise_Others_CS_Course_Takers_Profiling_Report.html
│   └── datasets
│       ├── AfricAmerican-Black
│       │   ├── ap_performance_afr_amerc.xlsx
│       │   ├── artcourse-afrc-amer-cs.xlsx
│       │   └── merged_df_Afric-American.xlsx
│       ├── Allstudents
│       │   ├── ap_performance_allstudents.xlsx
│       │   └── artcourse-all-students.xlsx
│       ├── AmericanIndian-Natives
│       │   ├── ap_performance_amerind_alaska.xlsx
│       │   └── artcourse-amerIn-Nat-cs.xlsx
│       ├── Hispanic-Latino
│       │   ├── ap_performance_hisp_latino.xlsx
│       │   ├── artcourse-hisplat-cs.xlsx
│       │   └── merged_df_Hispanic-Latino.xlsx
│       └── Others-(Asian + White)
│           ├── ap_performance_asian.xlsx
│           ├── ap_performance_white.xlsx
│           ├── artcourse-asian.xlsx
│           ├── artcourse-white.xlsx
│           ├── merged_Others-AP_Performance.xlsx
│           ├── merged_Others-CS-Classes.xlsx
│           └── merged_df_Others-(Asian+White).xlsx
├── README.md
├── Vincent_Code
│   ├── Aptest.png
│   ├── alldata.xlsx
│   ├── checkpoint.xlsx
│   ├── compare_wealth.ipynb
│   ├── cs_district.ipynb
│   ├── data
│   │   ├── All school districts in Massachusetts, MA.html
│   │   ├── All school districts in Massachusetts, MA_files
│   │   │   ├── application-120cfe33211dc9e2a4f74ed3f0956f6d8bab4a2323671bc109e4ead42362c9d5.css
│   │   │   ├── commons-blocking-bundle_923c45604e3945d608d8.js
│   │   │   ├── commons-blocking-loader-bundle_6a92ec9d27de71fed404.js
│   │   │   ├── commons-bundle_fcdb19323988706da908.js
│   │   │   ├── freshpaint.js
│   │   │   ├── gtm.js
│   │   │   ├── module_layouts-9b2e3038d9ac1cccc0c8dfed6a6e290bb6404e4ed245d9c881f4b3e3e7d2fae3.css
│   │   │   ├── post_load-9c960010c885d52ddbf31dda72a74ffea6d66021d8b8e10f65de09290787cd65.css
│   │   │   ├── print-d2abc08a7199dfe8dd876e618ce24de7589a325360afc980ade845f9e4a30d23.css
│   │   │   └── profile-22084c94b1d2013d6ce7350e64e8cee42c0a04c41ee35dff8e9a0fb0d952f2a9.png
│   │   ├── All_student_by_school.xlsx
│   │   ├── CENSUS2020TOWNS_SHP
│   │   │   ├── CENSUS2020TOWNS_ARC.cpg
│   │   │   ├── CENSUS2020TOWNS_ARC.dbf
│   │   │   ├── CENSUS2020TOWNS_ARC.prj
│   │   │   ├── CENSUS2020TOWNS_ARC.sbn
│   │   │   ├── CENSUS2020TOWNS_ARC.sbx
│   │   │   ├── CENSUS2020TOWNS_ARC.shp
│   │   │   ├── CENSUS2020TOWNS_ARC.shp.xml
│   │   │   ├── CENSUS2020TOWNS_ARC.shx
│   │   │   ├── CENSUS2020TOWNS_POLY.cpg
│   │   │   ├── CENSUS2020TOWNS_POLY.dbf
│   │   │   ├── CENSUS2020TOWNS_POLY.prj
│   │   │   ├── CENSUS2020TOWNS_POLY.sbn
│   │   │   ├── CENSUS2020TOWNS_POLY.sbx
│   │   │   ├── CENSUS2020TOWNS_POLY.shp
│   │   │   ├── CENSUS2020TOWNS_POLY.shp.xml
│   │   │   ├── CENSUS2020TOWNS_POLY.shx
│   │   │   └── Census 2020 Towns.lyr
│   │   ├── GRF22
│   │   │   ├── grf22_lea_aiannh.sas7bdat
│   │   │   ├── grf22_lea_aiannh.xlsx
│   │   │   ├── grf22_lea_blkgrp.sas7bdat
│   │   │   ├── grf22_lea_blkgrp.xlsx
│   │   │   ├── grf22_lea_cd.sas7bdat
│   │   │   ├── grf22_lea_cd.xlsx
│   │   │   ├── grf22_lea_county.sas7bdat
│   │   │   ├── grf22_lea_county.xlsx
│   │   │   ├── grf22_lea_cousub.sas7bdat
│   │   │   ├── grf22_lea_cousub.xlsx
│   │   │   ├── grf22_lea_place.sas7bdat
│   │   │   ├── grf22_lea_place.xlsx
│   │   │   ├── grf22_lea_tract.sas7bdat
│   │   │   ├── grf22_lea_tract.xlsx
│   │   │   ├── grf22_lea_zcta5ce20.sas7bdat
│   │   │   └── grf22_lea_zcta5ce20.xlsx
│   │   ├── all_organizations.json
│   │   ├── ap_performance_by_school.xlsx
│   │   ├── artcourse.xlsx
│   │   ├── by_city_percent.csv
│   │   ├── charter.xls
│   │   ├── lowincome.xlsx
│   │   ├── lowincome_by_school.xlsx
│   │   ├── organizations.json
│   │   ├── organizations_detail.json
│   │   ├── school_MA_info.xls
│   │   └── schooldistricts
│   │       ├── CCUV School Districts.lyr
│   │       ├── Public School Districts.lyr
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.cpg
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.dbf
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.prj
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.sbn
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.sbx
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.shp
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.shp.xml
│   │       ├── SCHOOLDISTRICTS_CCUV_POLY.shx
│   │       ├── SCHOOLDISTRICTS_POLY.cpg
│   │       ├── SCHOOLDISTRICTS_POLY.dbf
│   │       ├── SCHOOLDISTRICTS_POLY.prj
│   │       ├── SCHOOLDISTRICTS_POLY.sbn
│   │       ├── SCHOOLDISTRICTS_POLY.sbx
│   │       ├── SCHOOLDISTRICTS_POLY.shp
│   │       ├── SCHOOLDISTRICTS_POLY.shp.xml
│   │       ├── SCHOOLDISTRICTS_POLY.shx
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.cpg
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.dbf
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.prj
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.sbn
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.sbx
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.shp
│   │       ├── SCHOOLDISTRICTS_RglTownLabels.shp.xml
│   │       └── SCHOOLDISTRICTS_RglTownLabels.shx
│   ├── map.html
│   ├── ngo_by_town.xlsx
│   ├── ngo_income_expo.xlsx
│   ├── result_comparison.xlsx
│   ├── result_detailed_org.xlsx
│   └── school_dis_density.xlsx
└── laya_csMassLiteracy_R
    ├── CSLiteracy.Rmd
    ├── CSLiteracy_files
    │   └── figure-html
    │       ├── unnamed-chunk-10-1.png
    │       ├── unnamed-chunk-10-2.png
    │       ├── unnamed-chunk-3-1.png
    │       ├── unnamed-chunk-5-1.png
    │       ├── unnamed-chunk-6-1.png
    │       ├── unnamed-chunk-8-1.png
    │       ├── unnamed-chunk-8-2.png
    │       ├── unnamed-chunk-8-3.png
    │       └── unnamed-chunk-9-1.png
    └── data
        ├── CSLiteracy.html
        ├── Massachusetts_Public_School_Districts
        │   ├── Massachusetts_Public_School_Districts.cpg
        │   ├── Massachusetts_Public_School_Districts.dbf
        │   ├── Massachusetts_Public_School_Districts.prj
        │   ├── Massachusetts_Public_School_Districts.shp
        │   └── Massachusetts_Public_School_Districts.shx
        ├── counties
        │   ├── COUNTIESSURVEY_ARC.cpg
        │   ├── COUNTIESSURVEY_ARC.dbf
        │   ├── COUNTIESSURVEY_ARC.prj
        │   ├── COUNTIESSURVEY_ARC.sbn
        │   ├── COUNTIESSURVEY_ARC.sbx
        │   ├── COUNTIESSURVEY_ARC.shp
        │   ├── COUNTIESSURVEY_ARC.shp.xml
        │   ├── COUNTIESSURVEY_ARC.shx
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.cpg
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.dbf
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.prj
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.sbn
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.sbx
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.shp
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.shp.xml
        │   ├── COUNTIESSURVEY_ARC_GENCOAST.shx
        │   ├── COUNTIESSURVEY_POLYM.cpg
        │   ├── COUNTIESSURVEY_POLYM.dbf
        │   ├── COUNTIESSURVEY_POLYM.prj
        │   ├── COUNTIESSURVEY_POLYM.sbn
        │   ├── COUNTIESSURVEY_POLYM.sbx
        │   ├── COUNTIESSURVEY_POLYM.shp
        │   ├── COUNTIESSURVEY_POLYM.shp.xml
        │   ├── COUNTIESSURVEY_POLYM.shx
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.cpg
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.dbf
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.prj
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.sbn
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.sbx
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.shp
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.shp.xml
        │   ├── COUNTIESSURVEY_POLYM_GENCOAST.shx
        │   ├── COUNTIES_ARC.dbf
        │   ├── COUNTIES_ARC.prj
        │   ├── COUNTIES_ARC.sbn
        │   ├── COUNTIES_ARC.sbx
        │   ├── COUNTIES_ARC.shp
        │   ├── COUNTIES_ARC.shx
        │   ├── COUNTIES_POLY.dbf
        │   ├── COUNTIES_POLY.prj
        │   ├── COUNTIES_POLY.sbn
        │   ├── COUNTIES_POLY.sbx
        │   ├── COUNTIES_POLY.shp
        │   ├── COUNTIES_POLY.shx
        │   ├── COUNTIES_POLYM.dbf
        │   ├── COUNTIES_POLYM.prj
        │   ├── COUNTIES_POLYM.sbn
        │   ├── COUNTIES_POLYM.sbx
        │   ├── COUNTIES_POLYM.shp
        │   ├── COUNTIES_POLYM.shp.xml
        │   ├── COUNTIES_POLYM.shx
        │   ├── COUNTYNC_POLY.dbf
        │   ├── COUNTYNC_POLY.prj
        │   ├── COUNTYNC_POLY.sbn
        │   ├── COUNTYNC_POLY.sbx
        │   ├── COUNTYNC_POLY.shp
        │   ├── COUNTYNC_POLY.shp.xml
        │   ├── COUNTYNC_POLY.shx
        │   ├── Counties_poly.lyr
        │   ├── County_Arc_Outlines.lyr
        │   ├── County_Poly_Group_Multipart.lyr
        │   └── Massachusetts_Counties_Survey.lyr
        ├── counties_school.xlsx
        ├── everything_shape.csv
        ├── kx-massachusetts-municipalities-SHP
        │   ├── massachusetts-municipalities.cpg
        │   ├── massachusetts-municipalities.dbf
        │   ├── massachusetts-municipalities.prj
        │   ├── massachusetts-municipalities.shp
        │   ├── massachusetts-municipalities.shx
        │   └── massachusetts-municipalities.txt
        ├── lowincome.xlsx
        ├── passing.xlsx
        ├── school_info.xls
        ├── school_info.xlsx
        ├── schooldistricts
        │   ├── CCUV School Districts.lyr
        │   ├── Public School Districts.lyr
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.cpg
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.dbf
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.prj
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.sbn
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.sbx
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.shp
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.shp.xml
        │   ├── SCHOOLDISTRICTS_CCUV_POLY.shx
        │   ├── SCHOOLDISTRICTS_POLY.cpg
        │   ├── SCHOOLDISTRICTS_POLY.dbf
        │   ├── SCHOOLDISTRICTS_POLY.prj
        │   ├── SCHOOLDISTRICTS_POLY.sbn
        │   ├── SCHOOLDISTRICTS_POLY.sbx
        │   ├── SCHOOLDISTRICTS_POLY.shp
        │   ├── SCHOOLDISTRICTS_POLY.shp.xml
        │   ├── SCHOOLDISTRICTS_POLY.shx
        │   ├── SCHOOLDISTRICTS_RglTownLabels.cpg
        │   ├── SCHOOLDISTRICTS_RglTownLabels.dbf
        │   ├── SCHOOLDISTRICTS_RglTownLabels.prj
        │   ├── SCHOOLDISTRICTS_RglTownLabels.sbn
        │   ├── SCHOOLDISTRICTS_RglTownLabels.sbx
        │   ├── SCHOOLDISTRICTS_RglTownLabels.shp
        │   ├── SCHOOLDISTRICTS_RglTownLabels.shp.xml
        │   └── SCHOOLDISTRICTS_RglTownLabels.shx
        ├── tl_2016_25_cousub
        │   ├── tl_2016_25_cousub.cpg
        │   ├── tl_2016_25_cousub.dbf
        │   ├── tl_2016_25_cousub.prj
        │   ├── tl_2016_25_cousub.shp
        │   ├── tl_2016_25_cousub.shp.ea.iso.xml
        │   ├── tl_2016_25_cousub.shp.iso.xml
        │   ├── tl_2016_25_cousub.shp.xml
        │   └── tl_2016_25_cousub.shx
        ├── tl_2017_25_place
        │   ├── tl_2017_25_place.cpg
        │   ├── tl_2017_25_place.dbf
        │   ├── tl_2017_25_place.prj
        │   ├── tl_2017_25_place.shp
        │   ├── tl_2017_25_place.shp.ea.iso.xml
        │   ├── tl_2017_25_place.shp.iso.xml
        │   ├── tl_2017_25_place.shp.xml
        │   └── tl_2017_25_place.shx
        ├── totalstudentcount.xlsx
        ├── townssurvey_shp
        │   ├── MA_Towns_Survey_Bnd_Qual.lyr
        │   ├── MA_Towns_Survey_Dashed_Outlines.lyr
        │   ├── MA_Towns_Survey_Multi_Shaded.lyr
        │   ├── MA_Towns_Survey_Points.lyr
        │   ├── MA_Towns_Survey_Shaded.lyr
        │   ├── MA_Towns_Survey_Shaded_Group.lyr
        │   ├── TOWNSSURVEY_ARC.cpg
        │   ├── TOWNSSURVEY_ARC.dbf
        │   ├── TOWNSSURVEY_ARC.prj
        │   ├── TOWNSSURVEY_ARC.sbn
        │   ├── TOWNSSURVEY_ARC.sbx
        │   ├── TOWNSSURVEY_ARC.shp
        │   ├── TOWNSSURVEY_ARC.shp.xml
        │   ├── TOWNSSURVEY_ARC.shx
        │   ├── TOWNSSURVEY_ARC_GENCOAST.cpg
        │   ├── TOWNSSURVEY_ARC_GENCOAST.dbf
        │   ├── TOWNSSURVEY_ARC_GENCOAST.prj
        │   ├── TOWNSSURVEY_ARC_GENCOAST.sbn
        │   ├── TOWNSSURVEY_ARC_GENCOAST.sbx
        │   ├── TOWNSSURVEY_ARC_GENCOAST.shp
        │   ├── TOWNSSURVEY_ARC_GENCOAST.shp.xml
        │   ├── TOWNSSURVEY_ARC_GENCOAST.shx
        │   ├── TOWNSSURVEY_POLY.cpg
        │   ├── TOWNSSURVEY_POLY.dbf
        │   ├── TOWNSSURVEY_POLY.prj
        │   ├── TOWNSSURVEY_POLY.sbn
        │   ├── TOWNSSURVEY_POLY.sbx
        │   ├── TOWNSSURVEY_POLY.shp
        │   ├── TOWNSSURVEY_POLY.shp.xml
        │   ├── TOWNSSURVEY_POLY.shx
        │   ├── TOWNSSURVEY_POLYM.cpg
        │   ├── TOWNSSURVEY_POLYM.dbf
        │   ├── TOWNSSURVEY_POLYM.prj
        │   ├── TOWNSSURVEY_POLYM.sbn
        │   ├── TOWNSSURVEY_POLYM.sbx
        │   ├── TOWNSSURVEY_POLYM.shp
        │   ├── TOWNSSURVEY_POLYM.shp.xml
        │   ├── TOWNSSURVEY_POLYM.shx
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.cpg
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.dbf
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.prj
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.sbn
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.sbx
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.shp
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.shp.xml
        │   ├── TOWNSSURVEY_POLYM_GENCOAST.shx
        │   ├── TOWNSSURVEY_PT.cpg
        │   ├── TOWNSSURVEY_PT.dbf
        │   ├── TOWNSSURVEY_PT.prj
        │   ├── TOWNSSURVEY_PT.sbn
        │   ├── TOWNSSURVEY_PT.sbx
        │   ├── TOWNSSURVEY_PT.shp
        │   ├── TOWNSSURVEY_PT.shp.xml
        │   └── TOWNSSURVEY_PT.shx
        └── zipcodes_nt
            ├── ZIP Codes (5-Digit) from HERE (Navteq) Outline.lyr
            ├── ZIP Codes (5-Digit) from HERE (Navteq) Shaded.lyr
            ├── ZIPCODES_NT_POLY.cpg
            ├── ZIPCODES_NT_POLY.dbf
            ├── ZIPCODES_NT_POLY.prj
            ├── ZIPCODES_NT_POLY.sbn
            ├── ZIPCODES_NT_POLY.sbx
            ├── ZIPCODES_NT_POLY.shp
            ├── ZIPCODES_NT_POLY.shp.xml
            └── ZIPCODES_NT_POLY.shx
```

# How to Run
Every analysis has either their own ipynb notebooks or Rmd file. 


# Dependencies
1. Pandas
2. Matplotlib
3. Seaborn
4. ydata_profiling
5. geopandas




