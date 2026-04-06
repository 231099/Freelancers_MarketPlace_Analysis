<h1>Freelancers MarketPlace Analysis</h1>

<h2>Project Overview</h2>
<p>
This project presents a data-driven look at a global freelancer marketplace. By transforming a fragmented raw dataset, I developed an interactive Power BI dashboard that enables recruiters and stakeholders to filter talent by seniority, skill set, and geography.
</p>

<h3>Key Objectives:</h3>
<p>
Standardize inconsistent categorical and numerical data.

Analyze freelancer demographics (Gender, Age, Experience).

Identify top-performing talent based on Rating and Client Satisfaction.

Visualize geographical distribution of specialized skills.
</p>


<h2>Data Cleaning And Transformation</h2>
<p>
The raw dataset was highly inconsistent, requiring several advanced cleaning steps in Excel and Power Query before visualization:

1) Gender Standardization: Converted mixed values (e.g., "f", "female", "M", "male") into uniform "MALE" and "FEMALE" categories.
2) Hourly Rate Cleaning: Used string manipulation to remove symbols like $ and USD, converting the column into a pure numerical format for calculations.
3) Satisfaction Score Normalization: Standardized a mix of percentages (84%), decimals (0.84), and whole numbers (84) into a consistent decimal scale (0-1).
4) Handling Nulls & Placeholders:

   Replaced empty status cells with "Unknown".

   Analyzed 0.0 ratings—discovered they represented "Unrated" high-performers (avg. 81% satisfaction) and handled them as nulls in specific calculations to avoid skewing the global average.

5) Feature Engineering: Created new grouping columns:
   
   Age Groups: Categorized ages into '20-30', '31-45', and '45+'.

   Experience Levels: Segmented years of experience into 'Junior', 'Senior', and 'Executive'

6) Boolean Standardization (Is Active): Handled a highly fragmented is_active column:

   Problem: Data was entered in multiple formats including numeric (0, 1), shorthand (y, n), full text (yes, no), and logical values (True, False).

   Solution: Consolidated all variations into a clean, binary "YES" / "NO" format. This allowed for accurate filtering of the freelancer pool and the creation of "Active vs. Inactive" KPIs.
</p>

<h2>Business Insights</h2>
<p>
  The final dashboard reveals several critical insights for talent acquisition:

  Talent Hubs: South Korea and Canada emerged as the leading hubs for "Executive" level talent, specifically in high-demand fields like UI/UX and DevOps.

  Specialization Trends: The Donut Chart reveals that DevOps and UI/UX Design are the most saturated skills, indicating a highly technical talent pool.

  Workforce Demographics: The Age Group Pie Chart shows a robust "mid-career" workforce, with the 31-45 group representing a significant portion of the platform.

  Top-Tier Quality: The Top 10 Rated visual confirms that perfect 5.0 ratings are achievable across various skills, though often correlated with high client satisfaction scores.
</p>

<h2>Technologies Used</h2>
<p>
Excel: Initial data auditing and formula-based cleaning.

Power Query: Advanced data transformation and null handling.

Power BI: Data modeling, DAX measures (Tie-breakers for Top 10), and Interactive Dashboarding.</p>

<h2>Project Files</h2>
<p>
  Raw Data.csv
  
  Processed Data.xlsx
  
  Freelancers-Fullproject.pbix
  
  Dashboard.png
</p>
