## uga-mist-group2-project2

## Group Members

Colin Meersman - cmm08294@uga.edu - https://github.com/colinmeersman-uga/uga-mist-group2-project2

Divya Kadiyala - dk94810@uga.edu - https://github.com/dk94810-lang/uga-mist-group2-project2

Aaron Silverman - abs87438@uga.edu - https://github.com/abs87438/uga-mist-group2-project2

Laiba Syed - ls76725@uga.edu - https://github.com/ls76725/uga-mist-group2-project2

Sanjot Bodake - ssb46835@uga.edu - https://github.com/sbodake1/uga-mist-group2-project2

## Objective
Identify a data set and based on the data set and phenomenon ask 2 questions that would highlight something interesting about the data or phenomenon. 

## Dataset Description
The dataset titled “Motor Vehicle Collisions - Crashes” was obtained from the U.S. government’s open data portal at data.gov. The dataset consisted of 1,048,576 rows and 30 columns, where each row corresponds to a single crash event, and each column represents a specific attribute of that event. For example, the date and time of the crash, the borough and ZIP code, geographic coordinates (latitude and longitude), street names, and counts of injuries or fatalities where the individuals were categorized as pedestrian, cyclist, or motorist. The dataset included contributing factors for up to five vehicles (driver inattention, unsafe speed, etc.). And vehicle types (Passenger Vehicle, Taxi, Bus, etc). Data types differed by column. Borough names and contributing factors as strings, geographical data as scientific numbers, and date and time as qualitative data. Essentially, this dataset assists the NYPD in supporting citywide traffic safety in New York, and our group in answering two very important questions.  


## Question 1

How have car crashes changed year over year in the different Boroughs?

Why is this important?

1. Identifies Local Trends and Problem Areas
Each borough has unique traffic patterns, infrastructure, and population density. Analyzing year-over-year changes helps pinpoint where crashes are increasing or decreasing, showing which areas may need more safety interventions or policy attention.

2. Measures the Effectiveness of Safety Initiatives
New York has implemented several traffic safety programs. Tracking changes by borough allows policymakers to evaluate whether these efforts are working in specific areas — for example, if crashes declined more in Manhattan than in Queens, it might suggest that certain local policies are more effective.

3. Reveals Impacts of Major Events or Conditions
Year-over-year data captures how external events — such as state-wide lockdowns, weather patterns, or infrastructure changes — affect crash rates.



<img width="1680" height="1059" alt="image" src="https://github.com/user-attachments/assets/84fa4361-5e98-4fb9-a6e3-814f190df469" />

This map shows the spatial distribution of car crashes across New York City’s five boroughs. Each borough is color-coded, helping visualize where incidents occur most frequently. This geographic overview sets the stage for analyzing how trends differ across areas and over time.

<img width="819" height="1064" alt="image" src="https://github.com/user-attachments/assets/1a88fa3b-d090-42c3-a4ba-aee01194cf21" />

This line chart displays the total number of car crashes in New York City from 2013 to 2024. The data show a steady increase in crashes leading up to 2018–2019, followed by a sharp decline beginning in 2020. The dramatic drop corresponds with the onset of the COVID-19 pandemic, when lockdowns and reduced traffic volume significantly lowered crash counts. Although traffic gradually resumed in subsequent years, crash numbers have remained below pre-pandemic levels, suggesting a lasting shift in driving behavior or commuting patterns.

<img width="1683" height="1064" alt="Screenshot 2025-11-11 201743" src="https://github.com/user-attachments/assets/8cdd80a1-b101-452d-9e46-13d1567bb7b4" />

Before the pandemic, crash levels varied by borough but followed generally stable or slightly declining patterns. Brooklyn and Queens consistently reported the highest crash counts, reflecting their dense populations and extensive road networks. Manhattan and Staten Island showed gradual declines, possibly due to traffic-calming initiatives and enforcement of Vision Zero policies (An effort to have zero injuries or deaths in vehicle related incidents by prioritizing safety in the design of cities). The Bronx exhibited a modest upward trend, indicating localized increases in crash frequency. Overall, this period captures a relatively steady pre-COVID baseline.

<img width="1684" height="1057" alt="image" src="https://github.com/user-attachments/assets/c9ddfc13-7356-423e-9296-c8334cd193f8" />

After 2020, every borough saw a noticeable reduction in crash volume, with the steepest declines occurring in 2020 when travel restrictions were strongest. Brooklyn and Queens still lead in total crashes, but both saw significant downward trends. The Bronx’s crash numbers dropped sharply before stabilizing, while Manhattan’s decrease may reflect reduced commuter and tourist traffic. Staten Island remains comparatively low and stable. These post-COVID years highlight the pandemic’s enduring impact on urban mobility — fewer vehicles on the road have translated to fewer collisions citywide.

## Question 2

What is the leading cause of car crashes in New York?

Why is this important?

1. Improves Road Safety Policies
Knowing what causes most crashes helps city planners and law enforcement design targeted safety measures.

2. Guides Infrastructure and Urban Design
Understanding crash causes helps transportation departments prioritize road improvements.

3. Helps Allocate Resources Effectively
Police, traffic engineers, and city agencies can focus their efforts where they’ll have the biggest impact.

4. Informs Public Awareness and Education
When the city knows which behaviors cause the most crashes, it can educate drivers more effectively.

5. Reduces Economic and Social Costs
Crashes have huge economic costs — from medical bills and property damage to lost productivity.
By addressing root causes, the city can save lives and reduce financial strain on residents and emergency services.

6. Supports Long-Term Vision Zero Goals
New York City’s Vision Zero initiative aims to eliminate traffic deaths. Understanding contributing factors provides the evidence base needed to measure progress and plan future interventions.

<img width="1253" height="1064" alt="image" src="https://github.com/user-attachments/assets/ea7d24ea-c4c0-4e30-bf3d-7c53f7012971" />

This bar chart highlights the leading causes of vehicle collisions in New York. The most significant contributing factor by far is Driver Inattention or Distraction, accounting for approximately 450,000 crashes — more than double any other cause. This emphasizes how behaviors such as texting, phone use, or general lack of focus are the primary risks on New York’s roads.

The next most common factors are Failure to Yield Right of Way and Following Too Closely, each contributing over 100,000 incidents, suggesting that impatience and aggressive driving behaviors play a substantial role in urban collisions. Other noted factors include Backing Unsafely, Passing or Lane Usage Improperly, and Other Vehicular causes, each responsible for tens of thousands of crashes.

Overall, the data indicate that human error — particularly distraction and poor driving decisions — is the dominant cause of car crashes in New York, underscoring the need for ongoing driver awareness campaigns and enforcement of distracted driving laws.

<img width="1054" height="1059" alt="image" src="https://github.com/user-attachments/assets/8ac1fce9-e9c5-4ef6-977a-e0ef919f4f2c" />

This graph shows the total number of collisions by the hour of the day. The X-axis represents the 24 hours of the day (from 0 to 23), and the Y-axis shows the "Count of Collision Id" (the number of crashes).

Lowest Point: Crashes are at their lowest between 3:00 AM and 4:00 AM (hours 3-4).

Morning Peak: There is a significant spike in crashes around 8:00 AM (hour 8), which aligns with the morning rush hour.

Evening Peak: The number of crashes is highest during the evening commute, peaking around 4:00 PM (hour 16) and remaining very high from 2:00 PM to 6:00 PM (hours 14-18).

It is true that time is not a factor in crashes the same way that distracted driving is. However, time plays a factor regarding possible grogginess when individuals are first waking up and going to work as well as the exhaustion of the workday and a correllation of increased crashes at that time.

# Dataset Information

https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes

# Tablaeu Packaged Workbook

Tableau doesn't support .twbx

<?xml version='1.0' encoding='utf-8' ?>

<!-- build 20252.25.1003.1601                               -->
<workbook original-version='18.1' source-build='2025.2.4 (20252.25.1003.1601)' source-platform='win' version='18.1' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <AnimationOnByDefault />
    <MapboxVectorStylesAndLayers />
    <MarkAnimation />
    <ObjectModelEncapsulateLegacy />
    <ObjectModelExtractV2 />
    <ObjectModelTableType />
    <SchemaViewerObjectModel />
    <SheetIdentifierTracking />
    <_.fcp.VConnDownstreamExtractsWithWarnings.true...VConnDownstreamExtractsWithWarnings />
    <WindowsPersistSimpleIdentifiers />
  </document-format-change-manifest>
  <preferences>
    <preference name='ui.encoding.shelf.height' value='24' />
    <preference name='ui.shelf.height' value='26' />
  </preferences>
  <datasources>
    <datasource caption='Motor_Vehicle_Collisions_-_Crashes' inline='true' name='federated.1r8brmi130k32o1d2kah51ldrjx2' version='18.1'>
      <connection class='federated'>
        <named-connections>
          <named-connection caption='Motor_Vehicle_Collisions_-_Crashes' name='textscan.1xm4yu61bbbmm31beeajs01bf2c2'>
            <connection class='textscan' directory='C:/Users/colin/Downloads' filename='Motor_Vehicle_Collisions_-_Crashes.csv' password='' server='' />
          </named-connection>
        </named-connections>
        <relation connection='textscan.1xm4yu61bbbmm31beeajs01bf2c2' name='Motor_Vehicle_Collisions_-_Crashes.csv' table='[Motor_Vehicle_Collisions_-_Crashes#csv]' type='table'>
          <columns character-set='UTF-8' header='yes' locale='en_US' separator=','>
            <column datatype='date' name='CRASH DATE' ordinal='0' />
            <column datatype='datetime' name='CRASH TIME' ordinal='1' />
            <column datatype='string' name='BOROUGH' ordinal='2' />
            <column datatype='integer' name='ZIP CODE' ordinal='3' />
            <column datatype='real' name='LATITUDE' ordinal='4' />
            <column datatype='real' name='LONGITUDE' ordinal='5' />
            <column datatype='string' name='LOCATION' ordinal='6' />
            <column datatype='string' name='ON STREET NAME' ordinal='7' />
            <column datatype='string' name='CROSS STREET NAME' ordinal='8' />
            <column datatype='string' name='OFF STREET NAME' ordinal='9' />
            <column datatype='integer' name='NUMBER OF PERSONS INJURED' ordinal='10' />
            <column datatype='integer' name='NUMBER OF PERSONS KILLED' ordinal='11' />
            <column datatype='integer' name='NUMBER OF PEDESTRIANS INJURED' ordinal='12' />
            <column datatype='integer' name='NUMBER OF PEDESTRIANS KILLED' ordinal='13' />
            <column datatype='integer' name='NUMBER OF CYCLIST INJURED' ordinal='14' />
            <column datatype='integer' name='NUMBER OF CYCLIST KILLED' ordinal='15' />
            <column datatype='integer' name='NUMBER OF MOTORIST INJURED' ordinal='16' />
            <column datatype='integer' name='NUMBER OF MOTORIST KILLED' ordinal='17' />
            <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 1' ordinal='18' />
            <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 2' ordinal='19' />
            <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 3' ordinal='20' />
            <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 4' ordinal='21' />
            <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 5' ordinal='22' />
            <column datatype='integer' name='COLLISION_ID' ordinal='23' />
            <column datatype='string' name='VEHICLE TYPE CODE 1' ordinal='24' />
            <column datatype='string' name='VEHICLE TYPE CODE 2' ordinal='25' />
            <column datatype='string' name='VEHICLE TYPE CODE 3' ordinal='26' />
            <column datatype='string' name='VEHICLE TYPE CODE 4' ordinal='27' />
            <column datatype='string' name='VEHICLE TYPE CODE 5' ordinal='28' />
          </columns>
        </relation>
        <metadata-records>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='character-set'>&quot;UTF-8&quot;</attribute>
              <attribute datatype='string' name='collation'>&quot;en_US&quot;</attribute>
              <attribute datatype='string' name='field-delimiter'>&quot;,&quot;</attribute>
              <attribute datatype='string' name='header-row'>&quot;true&quot;</attribute>
              <attribute datatype='string' name='locale'>&quot;en_US&quot;</attribute>
              <attribute datatype='string' name='single-char'>&quot;&quot;</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRASH DATE</remote-name>
            <remote-type>133</remote-type>
            <local-name>[CRASH DATE]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CRASH DATE</remote-alias>
            <ordinal>0</ordinal>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRASH TIME</remote-name>
            <remote-type>134</remote-type>
            <local-name>[CRASH TIME]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CRASH TIME</remote-alias>
            <ordinal>1</ordinal>
            <local-type>datetime</local-type>
            <aggregation>Hour</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>BOROUGH</remote-name>
            <remote-type>129</remote-type>
            <local-name>[BOROUGH]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>BOROUGH</remote-alias>
            <ordinal>2</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>ZIP CODE</remote-name>
            <remote-type>20</remote-type>
            <local-name>[ZIP CODE]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>ZIP CODE</remote-alias>
            <ordinal>3</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>LATITUDE</remote-name>
            <remote-type>5</remote-type>
            <local-name>[LATITUDE]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>LATITUDE</remote-alias>
            <ordinal>4</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>LONGITUDE</remote-name>
            <remote-type>5</remote-type>
            <local-name>[LONGITUDE]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>LONGITUDE</remote-alias>
            <ordinal>5</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>LOCATION</remote-name>
            <remote-type>129</remote-type>
            <local-name>[LOCATION]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>LOCATION</remote-alias>
            <ordinal>6</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>ON STREET NAME</remote-name>
            <remote-type>129</remote-type>
            <local-name>[ON STREET NAME]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>ON STREET NAME</remote-alias>
            <ordinal>7</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CROSS STREET NAME</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CROSS STREET NAME]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CROSS STREET NAME</remote-alias>
            <ordinal>8</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OFF STREET NAME</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OFF STREET NAME]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>OFF STREET NAME</remote-alias>
            <ordinal>9</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF PERSONS INJURED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF PERSONS INJURED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF PERSONS INJURED</remote-alias>
            <ordinal>10</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF PERSONS KILLED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF PERSONS KILLED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF PERSONS KILLED</remote-alias>
            <ordinal>11</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF PEDESTRIANS INJURED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF PEDESTRIANS INJURED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF PEDESTRIANS INJURED</remote-alias>
            <ordinal>12</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF PEDESTRIANS KILLED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF PEDESTRIANS KILLED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF PEDESTRIANS KILLED</remote-alias>
            <ordinal>13</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF CYCLIST INJURED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF CYCLIST INJURED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF CYCLIST INJURED</remote-alias>
            <ordinal>14</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF CYCLIST KILLED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF CYCLIST KILLED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF CYCLIST KILLED</remote-alias>
            <ordinal>15</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF MOTORIST INJURED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF MOTORIST INJURED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF MOTORIST INJURED</remote-alias>
            <ordinal>16</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NUMBER OF MOTORIST KILLED</remote-name>
            <remote-type>20</remote-type>
            <local-name>[NUMBER OF MOTORIST KILLED]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>NUMBER OF MOTORIST KILLED</remote-alias>
            <ordinal>17</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CONTRIBUTING FACTOR VEHICLE 1</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CONTRIBUTING FACTOR VEHICLE 1]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CONTRIBUTING FACTOR VEHICLE 1</remote-alias>
            <ordinal>18</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CONTRIBUTING FACTOR VEHICLE 2</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CONTRIBUTING FACTOR VEHICLE 2]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CONTRIBUTING FACTOR VEHICLE 2</remote-alias>
            <ordinal>19</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CONTRIBUTING FACTOR VEHICLE 3</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CONTRIBUTING FACTOR VEHICLE 3]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CONTRIBUTING FACTOR VEHICLE 3</remote-alias>
            <ordinal>20</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CONTRIBUTING FACTOR VEHICLE 4</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CONTRIBUTING FACTOR VEHICLE 4]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CONTRIBUTING FACTOR VEHICLE 4</remote-alias>
            <ordinal>21</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CONTRIBUTING FACTOR VEHICLE 5</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CONTRIBUTING FACTOR VEHICLE 5]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>CONTRIBUTING FACTOR VEHICLE 5</remote-alias>
            <ordinal>22</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>COLLISION_ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[COLLISION_ID]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>COLLISION_ID</remote-alias>
            <ordinal>23</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>VEHICLE TYPE CODE 1</remote-name>
            <remote-type>129</remote-type>
            <local-name>[VEHICLE TYPE CODE 1]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>VEHICLE TYPE CODE 1</remote-alias>
            <ordinal>24</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>VEHICLE TYPE CODE 2</remote-name>
            <remote-type>129</remote-type>
            <local-name>[VEHICLE TYPE CODE 2]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>VEHICLE TYPE CODE 2</remote-alias>
            <ordinal>25</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>VEHICLE TYPE CODE 3</remote-name>
            <remote-type>129</remote-type>
            <local-name>[VEHICLE TYPE CODE 3]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>VEHICLE TYPE CODE 3</remote-alias>
            <ordinal>26</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>VEHICLE TYPE CODE 4</remote-name>
            <remote-type>129</remote-type>
            <local-name>[VEHICLE TYPE CODE 4]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>VEHICLE TYPE CODE 4</remote-alias>
            <ordinal>27</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>VEHICLE TYPE CODE 5</remote-name>
            <remote-type>129</remote-type>
            <local-name>[VEHICLE TYPE CODE 5]</local-name>
            <parent-name>[Motor_Vehicle_Collisions_-_Crashes.csv]</parent-name>
            <remote-alias>VEHICLE TYPE CODE 5</remote-alias>
            <ordinal>28</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RUS' />
            <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
          </metadata-record>
        </metadata-records>
      </connection>
      <aliases enabled='yes' />
      <column caption='Borough' datatype='string' name='[BOROUGH]' role='dimension' type='nominal' />
      <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
      <column caption='Contributing Factor Vehicle 1' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 1]' role='dimension' type='nominal' />
      <column caption='Contributing Factor Vehicle 2' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 2]' role='dimension' type='nominal' />
      <column caption='Contributing Factor Vehicle 3' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 3]' role='dimension' type='nominal' />
      <column caption='Contributing Factor Vehicle 4' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 4]' role='dimension' type='nominal' />
      <column caption='Contributing Factor Vehicle 5' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 5]' role='dimension' type='nominal' />
      <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
      <column caption='Crash Time' datatype='datetime' name='[CRASH TIME]' role='dimension' type='ordinal' />
      <column caption='Cross Street Name' datatype='string' name='[CROSS STREET NAME]' role='dimension' type='nominal' />
      <column aggregation='Avg' caption='Latitude' datatype='real' name='[LATITUDE]' role='measure' semantic-role='[Geographical].[Latitude]' type='quantitative' />
      <column caption='Location' datatype='string' name='[LOCATION]' role='dimension' type='nominal' />
      <column aggregation='Avg' caption='Longitude' datatype='real' name='[LONGITUDE]' role='measure' semantic-role='[Geographical].[Longitude]' type='quantitative' />
      <column caption='Number Of Cyclist Injured' datatype='integer' name='[NUMBER OF CYCLIST INJURED]' role='measure' type='quantitative' />
      <column caption='Number Of Cyclist Killed' datatype='integer' name='[NUMBER OF CYCLIST KILLED]' role='measure' type='quantitative' />
      <column caption='Number Of Motorist Injured' datatype='integer' name='[NUMBER OF MOTORIST INJURED]' role='measure' type='quantitative' />
      <column caption='Number Of Motorist Killed' datatype='integer' name='[NUMBER OF MOTORIST KILLED]' role='measure' type='quantitative' />
      <column caption='Number Of Pedestrians Injured' datatype='integer' name='[NUMBER OF PEDESTRIANS INJURED]' role='measure' type='quantitative' />
      <column caption='Number Of Pedestrians Killed' datatype='integer' name='[NUMBER OF PEDESTRIANS KILLED]' role='measure' type='quantitative' />
      <column caption='Number Of Persons Injured' datatype='integer' name='[NUMBER OF PERSONS INJURED]' role='measure' type='quantitative' />
      <column caption='Number Of Persons Killed' datatype='integer' name='[NUMBER OF PERSONS KILLED]' role='measure' type='quantitative' />
      <column caption='Off Street Name' datatype='string' name='[OFF STREET NAME]' role='dimension' type='nominal' />
      <column caption='On Street Name' datatype='string' name='[ON STREET NAME]' role='dimension' type='nominal' />
      <column caption='Vehicle Type Code 1' datatype='string' name='[VEHICLE TYPE CODE 1]' role='dimension' type='nominal' />
      <column caption='Vehicle Type Code 2' datatype='string' name='[VEHICLE TYPE CODE 2]' role='dimension' type='nominal' />
      <column caption='Vehicle Type Code 3' datatype='string' name='[VEHICLE TYPE CODE 3]' role='dimension' type='nominal' />
      <column caption='Vehicle Type Code 4' datatype='string' name='[VEHICLE TYPE CODE 4]' role='dimension' type='nominal' />
      <column caption='Vehicle Type Code 5' datatype='string' name='[VEHICLE TYPE CODE 5]' role='dimension' type='nominal' />
      <column aggregation='Sum' caption='Zip Code' datatype='integer' default-format='*00000' name='[ZIP CODE]' role='dimension' semantic-role='[ZipCode].[Name]' type='ordinal' />
      <column caption='Motor_Vehicle_Collisions_-_Crashes.csv' datatype='table' name='[__tableau_internal_object_id__].[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]' role='measure' type='quantitative' />
      <column-instance column='[CRASH TIME]' derivation='Hour' name='[hr:CRASH TIME:ok]' pivot='key' type='ordinal' />
      <column-instance column='[CRASH DATE]' derivation='Month' name='[mn:CRASH DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[BOROUGH]' derivation='None' name='[none:BOROUGH:nk]' pivot='key' type='nominal' />
      <column-instance column='[CONTRIBUTING FACTOR VEHICLE 1]' derivation='None' name='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' pivot='key' type='nominal' />
      <column-instance column='[CONTRIBUTING FACTOR VEHICLE 2]' derivation='None' name='[none:CONTRIBUTING FACTOR VEHICLE 2:nk]' pivot='key' type='nominal' />
      <column-instance column='[LATITUDE]' derivation='None' name='[none:LATITUDE:qk]' pivot='key' type='quantitative' />
      <column-instance column='[LONGITUDE]' derivation='None' name='[none:LONGITUDE:qk]' pivot='key' type='quantitative' />
      <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
      <group hidden='true' name='[Exclusions (Borough,Latitude,Longitude,MONTH(Crash Date),YEAR(Crash Date))]' name-style='unqualified' user:auto-column='exclude'>
        <groupfilter function='crossjoin'>
          <groupfilter function='level-members' level='[none:BOROUGH:nk]' />
          <groupfilter function='level-members' level='[none:LATITUDE:qk]' />
          <groupfilter function='level-members' level='[none:LONGITUDE:qk]' />
          <groupfilter function='level-members' level='[mn:CRASH DATE:ok]' />
          <groupfilter function='level-members' level='[yr:CRASH DATE:ok]' />
        </groupfilter>
      </group>
      <group hidden='true' name='[Exclusions (Contributing Factor Vehicle 1,Contributing Factor Vehicle 2)]' name-style='unqualified' user:auto-column='exclude'>
        <groupfilter function='crossjoin'>
          <groupfilter function='level-members' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' />
          <groupfilter function='level-members' level='[none:CONTRIBUTING FACTOR VEHICLE 2:nk]' />
        </groupfilter>
      </group>
      <extract _.fcp.VConnDownstreamExtractsWithWarnings.true...user-specific='false' count='-1' enabled='true' object-id='' units='records'>
        <connection access_mode='readonly' author-locale='en_US' class='hyper' dbname='C:/Users/colin/OneDrive/Documents/My Tableau Repository/Workbooks/MIST4610Group2TablaeuWorkbookCarCrashes.twb Files/Data/TableauTemp/#TableauTemp_1coiva20m4kkof1e6unnl0d7rup9.hyper' default-settings='hyper' schema='Extract' sslmode='' tablename='Extract' update-time='11/10/2025 08:36:58 PM' username='tableau_internal_user'>
          <relation name='Extract' table='[Extract].[Extract]' type='table' />
          <metadata-records>
            <metadata-record class='column'>
              <remote-name>CRASH DATE</remote-name>
              <remote-type>133</remote-type>
              <local-name>[CRASH DATE]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CRASH DATE</remote-alias>
              <ordinal>0</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>date</local-type>
              <aggregation>Year</aggregation>
              <approx-count>18291</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CRASH TIME</remote-name>
              <remote-type>134</remote-type>
              <local-name>[CRASH TIME]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CRASH TIME</remote-alias>
              <ordinal>1</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>datetime</local-type>
              <aggregation>Hour</aggregation>
              <approx-count>3910</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>BOROUGH</remote-name>
              <remote-type>129</remote-type>
              <local-name>[BOROUGH]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>BOROUGH</remote-alias>
              <ordinal>2</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>6</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>ZIP CODE</remote-name>
              <remote-type>20</remote-type>
              <local-name>[ZIP CODE]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>ZIP CODE</remote-alias>
              <ordinal>3</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>307</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>LATITUDE</remote-name>
              <remote-type>5</remote-type>
              <local-name>[LATITUDE]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>LATITUDE</remote-alias>
              <ordinal>4</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>real</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>225188</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>LONGITUDE</remote-name>
              <remote-type>5</remote-type>
              <local-name>[LONGITUDE]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>LONGITUDE</remote-alias>
              <ordinal>5</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>real</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>188416</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>LOCATION</remote-name>
              <remote-type>129</remote-type>
              <local-name>[LOCATION]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>LOCATION</remote-alias>
              <ordinal>6</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>273187</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>ON STREET NAME</remote-name>
              <remote-type>129</remote-type>
              <local-name>[ON STREET NAME]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>ON STREET NAME</remote-alias>
              <ordinal>7</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>15858</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CROSS STREET NAME</remote-name>
              <remote-type>129</remote-type>
              <local-name>[CROSS STREET NAME]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CROSS STREET NAME</remote-alias>
              <ordinal>8</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>18562</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>OFF STREET NAME</remote-name>
              <remote-type>129</remote-type>
              <local-name>[OFF STREET NAME]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>OFF STREET NAME</remote-alias>
              <ordinal>9</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>365966</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF PERSONS INJURED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF PERSONS INJURED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF PERSONS INJURED</remote-alias>
              <ordinal>10</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>10</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF PERSONS KILLED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF PERSONS KILLED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF PERSONS KILLED</remote-alias>
              <ordinal>11</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>3</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF PEDESTRIANS INJURED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF PEDESTRIANS INJURED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF PEDESTRIANS INJURED</remote-alias>
              <ordinal>12</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>4</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF PEDESTRIANS KILLED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF PEDESTRIANS KILLED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF PEDESTRIANS KILLED</remote-alias>
              <ordinal>13</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>2</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF CYCLIST INJURED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF CYCLIST INJURED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF CYCLIST INJURED</remote-alias>
              <ordinal>14</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>3</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF CYCLIST KILLED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF CYCLIST KILLED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF CYCLIST KILLED</remote-alias>
              <ordinal>15</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>2</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF MOTORIST INJURED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF MOTORIST INJURED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF MOTORIST INJURED</remote-alias>
              <ordinal>16</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>10</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>NUMBER OF MOTORIST KILLED</remote-name>
              <remote-type>20</remote-type>
              <local-name>[NUMBER OF MOTORIST KILLED]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>NUMBER OF MOTORIST KILLED</remote-alias>
              <ordinal>17</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>3</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CONTRIBUTING FACTOR VEHICLE 1</remote-name>
              <remote-type>129</remote-type>
              <local-name>[CONTRIBUTING FACTOR VEHICLE 1]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CONTRIBUTING FACTOR VEHICLE 1</remote-alias>
              <ordinal>18</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>93</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CONTRIBUTING FACTOR VEHICLE 2</remote-name>
              <remote-type>129</remote-type>
              <local-name>[CONTRIBUTING FACTOR VEHICLE 2]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CONTRIBUTING FACTOR VEHICLE 2</remote-alias>
              <ordinal>19</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>74</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CONTRIBUTING FACTOR VEHICLE 3</remote-name>
              <remote-type>129</remote-type>
              <local-name>[CONTRIBUTING FACTOR VEHICLE 3]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CONTRIBUTING FACTOR VEHICLE 3</remote-alias>
              <ordinal>20</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>129</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CONTRIBUTING FACTOR VEHICLE 4</remote-name>
              <remote-type>129</remote-type>
              <local-name>[CONTRIBUTING FACTOR VEHICLE 4]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CONTRIBUTING FACTOR VEHICLE 4</remote-alias>
              <ordinal>21</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>8</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>CONTRIBUTING FACTOR VEHICLE 5</remote-name>
              <remote-type>129</remote-type>
              <local-name>[CONTRIBUTING FACTOR VEHICLE 5]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>CONTRIBUTING FACTOR VEHICLE 5</remote-alias>
              <ordinal>22</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>44</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>COLLISION_ID</remote-name>
              <remote-type>20</remote-type>
              <local-name>[COLLISION_ID]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>COLLISION_ID</remote-alias>
              <ordinal>23</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>integer</local-type>
              <aggregation>Sum</aggregation>
              <approx-count>2218631</approx-count>
              <contains-null>true</contains-null>
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>VEHICLE TYPE CODE 1</remote-name>
              <remote-type>129</remote-type>
              <local-name>[VEHICLE TYPE CODE 1]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>VEHICLE TYPE CODE 1</remote-alias>
              <ordinal>24</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>539</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>VEHICLE TYPE CODE 2</remote-name>
              <remote-type>129</remote-type>
              <local-name>[VEHICLE TYPE CODE 2]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>VEHICLE TYPE CODE 2</remote-alias>
              <ordinal>25</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>654</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>VEHICLE TYPE CODE 3</remote-name>
              <remote-type>129</remote-type>
              <local-name>[VEHICLE TYPE CODE 3]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>VEHICLE TYPE CODE 3</remote-alias>
              <ordinal>26</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>80</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>VEHICLE TYPE CODE 4</remote-name>
              <remote-type>129</remote-type>
              <local-name>[VEHICLE TYPE CODE 4]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>VEHICLE TYPE CODE 4</remote-alias>
              <ordinal>27</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>53</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
            <metadata-record class='column'>
              <remote-name>VEHICLE TYPE CODE 5</remote-name>
              <remote-type>129</remote-type>
              <local-name>[VEHICLE TYPE CODE 5]</local-name>
              <parent-name>[Extract]</parent-name>
              <remote-alias>VEHICLE TYPE CODE 5</remote-alias>
              <ordinal>28</ordinal>
              <family>Motor_Vehicle_Collisions_-_Crashes.csv</family>
              <local-type>string</local-type>
              <aggregation>Count</aggregation>
              <approx-count>8</approx-count>
              <contains-null>true</contains-null>
              <collation flag='0' name='LEN_RUS' />
              <object-id>[Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257]</object-id>
            </metadata-record>
          </metadata-records>
        </connection>
      </extract>
      <layout dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='true' />
      <style>
        <style-rule element='mark'>
          <encoding attr='color' field='[yr:CRASH DATE:ok]' type='palette'>
            <map to='#4e79a7'>
              <bucket>2012</bucket>
            </map>
            <map to='#76b7b2'>
              <bucket>2015</bucket>
            </map>
            <map to='#e15759'>
              <bucket>2014</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>2013</bucket>
            </map>
          </encoding>
          <encoding attr='color' field='[none:BOROUGH:nk]' type='palette'>
            <map to='#4e79a7'>
              <bucket>%null%</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;BRONX&quot;</bucket>
            </map>
            <map to='#76b7b2'>
              <bucket>&quot;STATEN ISLAND&quot;</bucket>
            </map>
            <map to='#e15759'>
              <bucket>&quot;QUEENS&quot;</bucket>
            </map>
            <map to='#edc948'>
              <bucket>&quot;MANHATTAN&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;BROOKLYN&quot;</bucket>
            </map>
          </encoding>
          <encoding attr='color' field='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' type='palette'>
            <map to='#499894'>
              <bucket>&quot;Cell Phone (hand-Held)&quot;</bucket>
            </map>
            <map to='#499894'>
              <bucket>&quot;Other Electronic Device&quot;</bucket>
            </map>
            <map to='#499894'>
              <bucket>&quot;Tow Hitch Defective&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;Backing Unsafely&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;Glare&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;Prescription Medication&quot;</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;Lane Marking Improper/Inadequate&quot;</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;Other Vehicular&quot;</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;Steering Failure&quot;</bucket>
            </map>
            <map to='#76b7b2'>
              <bucket>&quot;Following Too Closely&quot;</bucket>
            </map>
            <map to='#79706e'>
              <bucket>&quot;Driver Inexperience&quot;</bucket>
            </map>
            <map to='#79706e'>
              <bucket>&quot;Oversized Vehicle&quot;</bucket>
            </map>
            <map to='#79706e'>
              <bucket>&quot;Unsafe Lane Changing&quot;</bucket>
            </map>
            <map to='#86bcb6'>
              <bucket>&quot;Cell Phone (hand-held)&quot;</bucket>
            </map>
            <map to='#86bcb6'>
              <bucket>&quot;Other Lighting Defects&quot;</bucket>
            </map>
            <map to='#86bcb6'>
              <bucket>&quot;Traffic Control Device Improper/Non-Working&quot;</bucket>
            </map>
            <map to='#8cd17d'>
              <bucket>&quot;Alcohol Involvement&quot;</bucket>
            </map>
            <map to='#8cd17d'>
              <bucket>&quot;Listening/Using Headphones&quot;</bucket>
            </map>
            <map to='#8cd17d'>
              <bucket>&quot;Texting&quot;</bucket>
            </map>
            <map to='#9d7660'>
              <bucket>&quot;Fell Asleep&quot;</bucket>
            </map>
            <map to='#a0cbe8'>
              <bucket>&quot;Accelerator Defective&quot;</bucket>
            </map>
            <map to='#a0cbe8'>
              <bucket>&quot;Headlights Defective&quot;</bucket>
            </map>
            <map to='#a0cbe8'>
              <bucket>&quot;Reaction to Other Uninvolved Vehicle&quot;</bucket>
            </map>
            <map to='#b07aa1'>
              <bucket>&quot;Eating or Drinking&quot;</bucket>
            </map>
            <map to='#b07aa1'>
              <bucket>&quot;Pavement Defective&quot;</bucket>
            </map>
            <map to='#b07aa1'>
              <bucket>&quot;View Obstructed/Limited&quot;</bucket>
            </map>
            <map to='#b6992d'>
              <bucket>&quot;Animals Action&quot;</bucket>
            </map>
            <map to='#b6992d'>
              <bucket>&quot;Lost Consciousness&quot;</bucket>
            </map>
            <map to='#b6992d'>
              <bucket>&quot;Tinted Windows&quot;</bucket>
            </map>
            <map to='#bab0ac'>
              <bucket>&quot;Driverless/Runaway Vehicle&quot;</bucket>
            </map>
            <map to='#bab0ac'>
              <bucket>&quot;Passenger Distraction&quot;</bucket>
            </map>
            <map to='#bab0ac'>
              <bucket>&quot;Unsafe Speed&quot;</bucket>
            </map>
            <map to='#d37295'>
              <bucket>&quot;Drugs (Illegal)&quot;</bucket>
            </map>
            <map to='#d37295'>
              <bucket>&quot;Physical Disability&quot;</bucket>
            </map>
            <map to='#d37295'>
              <bucket>&quot;Using On Board Navigation Device&quot;</bucket>
            </map>
            <map to='#d4a6c8'>
              <bucket>&quot;Failure to Keep Right&quot;</bucket>
            </map>
            <map to='#d4a6c8'>
              <bucket>&quot;Fatigued/Drowsy&quot;</bucket>
            </map>
            <map to='#d4a6c8'>
              <bucket>&quot;Windshield Inadequate&quot;</bucket>
            </map>
            <map to='#d7b5a6'>
              <bucket>&quot;Pavement Slippery&quot;</bucket>
            </map>
            <map to='#e15759'>
              <bucket>&quot;Failure to Yield Right-of-Way&quot;</bucket>
            </map>
            <map to='#e15759'>
              <bucket>&quot;Pedestrian/Bicyclist/Other Pedestrian Error/Confusion&quot;</bucket>
            </map>
            <map to='#e15759'>
              <bucket>&quot;Traffic Control Disregarded&quot;</bucket>
            </map>
            <map to='#edc948'>
              <bucket>&quot;Passing or Lane Usage Improper&quot;</bucket>
            </map>
            <map to='#f1ce63'>
              <bucket>&quot;Brakes Defective&quot;</bucket>
            </map>
            <map to='#f1ce63'>
              <bucket>&quot;Obstruction/Debris&quot;</bucket>
            </map>
            <map to='#f1ce63'>
              <bucket>&quot;Tire Failure/Inadequate&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;Driver Inattention/Distraction&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;Illnes&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;Reaction to Uninvolved Vehicle&quot;</bucket>
            </map>
            <map to='#fabfd2'>
              <bucket>&quot;Drugs (illegal)&quot;</bucket>
            </map>
            <map to='#fabfd2'>
              <bucket>&quot;Passing Too Closely&quot;</bucket>
            </map>
            <map to='#fabfd2'>
              <bucket>&quot;Vehicle Vandalism&quot;</bucket>
            </map>
            <map to='#ff9d9a'>
              <bucket>&quot;Cell Phone (hands-free)&quot;</bucket>
            </map>
            <map to='#ff9d9a'>
              <bucket>&quot;Outside Car Distraction&quot;</bucket>
            </map>
            <map to='#ff9d9a'>
              <bucket>&quot;Turning Improperly&quot;</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>&quot;Aggressive Driving/Road Rage&quot;</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>&quot;Illness&quot;</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>&quot;Shoulders Defective/Improper&quot;</bucket>
            </map>
          </encoding>
          <encoding attr='color' field='[hr:CRASH TIME:ok]' type='palette'>
            <map to='#499894'>
              <bucket>8</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>0</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>20</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>4</bucket>
            </map>
            <map to='#79706e'>
              <bucket>12</bucket>
            </map>
            <map to='#86bcb6'>
              <bucket>9</bucket>
            </map>
            <map to='#8cd17d'>
              <bucket>5</bucket>
            </map>
            <map to='#9d7660'>
              <bucket>18</bucket>
            </map>
            <map to='#a0cbe8'>
              <bucket>1</bucket>
            </map>
            <map to='#a0cbe8'>
              <bucket>21</bucket>
            </map>
            <map to='#b07aa1'>
              <bucket>16</bucket>
            </map>
            <map to='#b6992d'>
              <bucket>6</bucket>
            </map>
            <map to='#bab0ac'>
              <bucket>13</bucket>
            </map>
            <map to='#d37295'>
              <bucket>14</bucket>
            </map>
            <map to='#d4a6c8'>
              <bucket>17</bucket>
            </map>
            <map to='#d7b5a6'>
              <bucket>19</bucket>
            </map>
            <map to='#e15759'>
              <bucket>10</bucket>
            </map>
            <map to='#f1ce63'>
              <bucket>7</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>2</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>22</bucket>
            </map>
            <map to='#fabfd2'>
              <bucket>15</bucket>
            </map>
            <map to='#ff9d9a'>
              <bucket>11</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>3</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>23</bucket>
            </map>
          </encoding>
        </style-rule>
      </style>
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;United States&quot;' />
      </semantic-values>
      <object-graph>
        <objects>
          <object caption='Motor_Vehicle_Collisions_-_Crashes.csv' id='Motor_Vehicle_Collisions_-_Crashes.csv_B94B7D8B49864DE6A8CD03E652A71257'>
            <properties context=''>
              <relation connection='textscan.1xm4yu61bbbmm31beeajs01bf2c2' name='Motor_Vehicle_Collisions_-_Crashes.csv' table='[Motor_Vehicle_Collisions_-_Crashes#csv]' type='table'>
                <columns character-set='UTF-8' header='yes' locale='en_US' separator=','>
                  <column datatype='date' name='CRASH DATE' ordinal='0' />
                  <column datatype='datetime' name='CRASH TIME' ordinal='1' />
                  <column datatype='string' name='BOROUGH' ordinal='2' />
                  <column datatype='integer' name='ZIP CODE' ordinal='3' />
                  <column datatype='real' name='LATITUDE' ordinal='4' />
                  <column datatype='real' name='LONGITUDE' ordinal='5' />
                  <column datatype='string' name='LOCATION' ordinal='6' />
                  <column datatype='string' name='ON STREET NAME' ordinal='7' />
                  <column datatype='string' name='CROSS STREET NAME' ordinal='8' />
                  <column datatype='string' name='OFF STREET NAME' ordinal='9' />
                  <column datatype='integer' name='NUMBER OF PERSONS INJURED' ordinal='10' />
                  <column datatype='integer' name='NUMBER OF PERSONS KILLED' ordinal='11' />
                  <column datatype='integer' name='NUMBER OF PEDESTRIANS INJURED' ordinal='12' />
                  <column datatype='integer' name='NUMBER OF PEDESTRIANS KILLED' ordinal='13' />
                  <column datatype='integer' name='NUMBER OF CYCLIST INJURED' ordinal='14' />
                  <column datatype='integer' name='NUMBER OF CYCLIST KILLED' ordinal='15' />
                  <column datatype='integer' name='NUMBER OF MOTORIST INJURED' ordinal='16' />
                  <column datatype='integer' name='NUMBER OF MOTORIST KILLED' ordinal='17' />
                  <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 1' ordinal='18' />
                  <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 2' ordinal='19' />
                  <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 3' ordinal='20' />
                  <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 4' ordinal='21' />
                  <column datatype='string' name='CONTRIBUTING FACTOR VEHICLE 5' ordinal='22' />
                  <column datatype='integer' name='COLLISION_ID' ordinal='23' />
                  <column datatype='string' name='VEHICLE TYPE CODE 1' ordinal='24' />
                  <column datatype='string' name='VEHICLE TYPE CODE 2' ordinal='25' />
                  <column datatype='string' name='VEHICLE TYPE CODE 3' ordinal='26' />
                  <column datatype='string' name='VEHICLE TYPE CODE 4' ordinal='27' />
                  <column datatype='string' name='VEHICLE TYPE CODE 5' ordinal='28' />
                </columns>
              </relation>
            </properties>
            <properties context='extract'>
              <relation name='Extract' table='[Extract].[Extract]' type='table' />
            </properties>
          </object>
        </objects>
      </object-graph>
    </datasource>
  </datasources>
  <mapsources>
    <mapsource name='Tableau' />
  </mapsources>
  <worksheets>
    <worksheet name='#Crashes'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Number of Crashes over time</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column-instance column='[COLLISION_ID]' derivation='CountD' name='[ctd:COLLISION_ID:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[yr:CRASH DATE:ok]' />
              <groupfilter function='union'>
                <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2012' />
                <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2025' />
              </groupfilter>
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane id='1' selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[ctd:COLLISION_ID:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</cols>
      </table>
      <simple-id uuid='{91D33D9D-1689-4815-8C9D-6DE1246243C3}' />
    </worksheet>
    <worksheet name='#Injuries'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Number of Car Crashes</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column caption='Number Of Motorist Injured' datatype='integer' name='[NUMBER OF MOTORIST INJURED]' role='measure' type='quantitative' />
            <column-instance column='[NUMBER OF MOTORIST INJURED]' derivation='Sum' name='[sum:NUMBER OF MOTORIST INJURED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[yr:CRASH DATE:ok]' />
              <groupfilter function='union'>
                <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2012' />
                <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2025' />
              </groupfilter>
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[sum:NUMBER OF MOTORIST INJURED:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</cols>
      </table>
      <simple-id uuid='{EA823218-5D59-4C27-BEC0-1A21F45AA91B}' />
    </worksheet>
    <worksheet name='Bouroughs'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Collisions By Borough</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Borough' datatype='string' name='[BOROUGH]' role='dimension' type='nominal' />
            <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
            <column-instance column='[COLLISION_ID]' derivation='CountD' name='[ctd:COLLISION_ID:qk]' pivot='key' type='quantitative' />
            <column-instance column='[BOROUGH]' derivation='None' name='[none:BOROUGH:nk]' pivot='key' type='nominal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:BOROUGH:nk]' />
              <groupfilter function='member' level='[none:BOROUGH:nk]' member='%null%' />
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <color column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' />
            </encodings>
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[ctd:COLLISION_ID:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]</cols>
      </table>
      <simple-id uuid='{1AE7F94F-C5F7-4441-ACAE-2AF8EF81B226}' />
    </worksheet>
    <worksheet name='Crashes By Factor'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Contributing Factor to Crash - Time</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
            <column caption='Contributing Factor Vehicle 1' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 1]' role='dimension' type='nominal' />
            <column caption='Contributing Factor Vehicle 2' datatype='string' name='[CONTRIBUTING FACTOR VEHICLE 2]' role='dimension' type='nominal' />
            <column caption='Crash Time' datatype='datetime' name='[CRASH TIME]' role='dimension' type='ordinal' />
            <column-instance column='[COLLISION_ID]' derivation='Count' name='[cnt:COLLISION_ID:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH TIME]' derivation='Hour' name='[hr:CRASH TIME:ok]' pivot='key' type='ordinal' />
            <column-instance column='[CONTRIBUTING FACTOR VEHICLE 1]' derivation='None' name='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' pivot='key' type='nominal' />
            <column-instance column='[CONTRIBUTING FACTOR VEHICLE 2]' derivation='None' name='[none:CONTRIBUTING FACTOR VEHICLE 2:nk]' pivot='key' type='nominal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[Exclusions (Contributing Factor Vehicle 1,Contributing Factor Vehicle 2)]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='crossjoin'>
                <groupfilter function='level-members' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' />
                <groupfilter function='level-members' level='[none:CONTRIBUTING FACTOR VEHICLE 2:nk]' />
              </groupfilter>
              <groupfilter function='reorder-dimensionality'>
                <groupfilter function='crossjoin'>
                  <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 2:nk]' member='&quot;Unspecified&quot;' />
                  <groupfilter function='union'>
                    <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;Backing Unsafely&quot;' />
                    <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;Driver Inattention/Distraction&quot;' />
                    <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;Failure to Yield Right-of-Way&quot;' />
                    <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;Following Too Closely&quot;' />
                  </groupfilter>
                </groupfilter>
                <order>
                  <hierarchy name='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' />
                  <hierarchy name='[none:CONTRIBUTING FACTOR VEHICLE 2:nk]' />
                </order>
              </groupfilter>
            </groupfilter>
          </filter>
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[cnt:COLLISION_ID:qk]' included-values='in-range'>
            <min>1</min>
            <max>466037</max>
          </filter>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CONTRIBUTING FACTOR VEHICLE 1:nk]'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' />
              <groupfilter function='union'>
                <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='%null%' />
                <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;1&quot;' />
                <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;80&quot;' />
                <groupfilter function='member' level='[none:CONTRIBUTING FACTOR VEHICLE 1:nk]' member='&quot;Unspecified&quot;' />
              </groupfilter>
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CONTRIBUTING FACTOR VEHICLE 1:nk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[cnt:COLLISION_ID:qk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[Exclusions (Contributing Factor Vehicle 1,Contributing Factor Vehicle 2)]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Line' />
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[cnt:COLLISION_ID:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[hr:CRASH TIME:ok]</cols>
      </table>
      <simple-id uuid='{AD3C1D5E-3419-4D65-A7BA-FFDAC760BE71}' />
    </worksheet>
    <worksheet name='Deaths'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Arbitrary numbers bc y axis is small numbers</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column caption='Number Of Motorist Killed' datatype='integer' name='[NUMBER OF MOTORIST KILLED]' role='measure' type='quantitative' />
            <column-instance column='[NUMBER OF MOTORIST KILLED]' derivation='Sum' name='[sum:NUMBER OF MOTORIST KILLED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[yr:CRASH DATE:ok]' />
              <groupfilter function='union'>
                <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2012' />
                <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2025' />
              </groupfilter>
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[sum:NUMBER OF MOTORIST KILLED:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</cols>
      </table>
      <simple-id uuid='{BADC4AF7-4218-484D-A8C8-BF14F9DFF541}' />
    </worksheet>
    <worksheet name='GEO'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Crashes in Different Bouroughs</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Borough' datatype='string' name='[BOROUGH]' role='dimension' type='nominal' />
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column aggregation='Avg' caption='Latitude' datatype='real' name='[LATITUDE]' role='measure' semantic-role='[Geographical].[Latitude]' type='quantitative' />
            <column aggregation='Avg' caption='Longitude' datatype='real' name='[LONGITUDE]' role='measure' semantic-role='[Geographical].[Longitude]' type='quantitative' />
            <column caption='Number Of Motorist Injured' datatype='integer' name='[NUMBER OF MOTORIST INJURED]' role='measure' type='quantitative' />
            <column caption='Number Of Motorist Killed' datatype='integer' name='[NUMBER OF MOTORIST KILLED]' role='measure' type='quantitative' />
            <column caption='Number Of Pedestrians Injured' datatype='integer' name='[NUMBER OF PEDESTRIANS INJURED]' role='measure' type='quantitative' />
            <column caption='Number Of Pedestrians Killed' datatype='integer' name='[NUMBER OF PEDESTRIANS KILLED]' role='measure' type='quantitative' />
            <column caption='Number Of Persons Injured' datatype='integer' name='[NUMBER OF PERSONS INJURED]' role='measure' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Month' name='[mn:CRASH DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[BOROUGH]' derivation='None' name='[none:BOROUGH:nk]' pivot='key' type='nominal' />
            <column-instance column='[CRASH DATE]' derivation='None' name='[none:CRASH DATE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[LATITUDE]' derivation='None' name='[none:LATITUDE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[LONGITUDE]' derivation='None' name='[none:LONGITUDE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[NUMBER OF PERSONS INJURED]' derivation='None' name='[none:NUMBER OF PERSONS INJURED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[NUMBER OF MOTORIST INJURED]' derivation='Sum' name='[sum:NUMBER OF MOTORIST INJURED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[NUMBER OF MOTORIST KILLED]' derivation='Sum' name='[sum:NUMBER OF MOTORIST KILLED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[NUMBER OF PEDESTRIANS INJURED]' derivation='Sum' name='[sum:NUMBER OF PEDESTRIANS INJURED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[NUMBER OF PEDESTRIANS KILLED]' derivation='Sum' name='[sum:NUMBER OF PEDESTRIANS KILLED:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[Exclusions (Borough,Latitude,Longitude,MONTH(Crash Date),YEAR(Crash Date))]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='crossjoin'>
                <groupfilter function='level-members' level='[none:BOROUGH:nk]' />
                <groupfilter function='level-members' level='[none:LATITUDE:qk]' />
                <groupfilter function='level-members' level='[none:LONGITUDE:qk]' />
                <groupfilter function='level-members' level='[mn:CRASH DATE:ok]' />
                <groupfilter function='level-members' level='[yr:CRASH DATE:ok]' />
              </groupfilter>
              <groupfilter function='reorder-dimensionality'>
                <groupfilter function='union'>
                  <groupfilter function='crossjoin'>
                    <groupfilter function='member' level='[none:BOROUGH:nk]' member='&quot;BRONX&quot;' />
                    <groupfilter function='union'>
                      <groupfilter function='crossjoin'>
                        <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2016' />
                        <groupfilter function='union'>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='3' />
                            <groupfilter function='union'>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.647309999999997' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.980125000000001' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.673999999999999' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.872100000000003' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.674053000000001' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.872110000000006' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.7136' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.009100000000004' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.724400000000003' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.981800000000007' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.725549999999998' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.982569999999996' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.776899999999998' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.941299999999998' />
                              </groupfilter>
                            </groupfilter>
                          </groupfilter>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='4' />
                            <groupfilter function='crossjoin'>
                              <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.722000000000001' />
                              <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.981999999999999' />
                            </groupfilter>
                          </groupfilter>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='6' />
                            <groupfilter function='crossjoin'>
                              <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.584533999999998' />
                              <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.822329999999994' />
                            </groupfilter>
                          </groupfilter>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='10' />
                            <groupfilter function='crossjoin'>
                              <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.709299999999999' />
                              <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.002899999999997' />
                            </groupfilter>
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                      <groupfilter function='crossjoin'>
                        <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2018' />
                        <groupfilter function='crossjoin'>
                          <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='3' />
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.685609999999997' />
                            <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.75027' />
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                      <groupfilter function='crossjoin'>
                        <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2019' />
                        <groupfilter function='crossjoin'>
                          <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='8' />
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.696734999999997' />
                            <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.969859999999997' />
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                      <groupfilter function='crossjoin'>
                        <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2020' />
                        <groupfilter function='crossjoin'>
                          <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='11' />
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.709522' />
                            <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.005790000000005' />
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                    </groupfilter>
                  </groupfilter>
                  <groupfilter function='crossjoin'>
                    <groupfilter function='member' level='[none:BOROUGH:nk]' member='&quot;BROOKLYN&quot;' />
                    <groupfilter function='union'>
                      <groupfilter function='crossjoin'>
                        <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2016' />
                        <groupfilter function='union'>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='3' />
                            <groupfilter function='union'>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.713560000000001' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.009039999999999' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.7136' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.009100000000004' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.724400000000003' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.981800000000007' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.752395999999997' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.972329999999999' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.776899999999998' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.941299999999998' />
                              </groupfilter>
                            </groupfilter>
                          </groupfilter>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='4' />
                            <groupfilter function='union'>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.7136' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.009100000000004' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.715622000000003' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.007384999999999' />
                              </groupfilter>
                            </groupfilter>
                          </groupfilter>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='5' />
                            <groupfilter function='union'>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.596103999999997' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.760413999999997' />
                              </groupfilter>
                              <groupfilter function='crossjoin'>
                                <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.724494999999997' />
                                <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.72775' />
                              </groupfilter>
                            </groupfilter>
                          </groupfilter>
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='10' />
                            <groupfilter function='crossjoin'>
                              <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.711055999999999' />
                              <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.003203999999997' />
                            </groupfilter>
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                      <groupfilter function='crossjoin'>
                        <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2017' />
                        <groupfilter function='crossjoin'>
                          <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='8' />
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.790035000000003' />
                            <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-73.94896' />
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                    </groupfilter>
                  </groupfilter>
                  <groupfilter function='crossjoin'>
                    <groupfilter function='member' level='[none:BOROUGH:nk]' member='&quot;QUEENS&quot;' />
                    <groupfilter function='crossjoin'>
                      <groupfilter function='member' level='[yr:CRASH DATE:ok]' member='2016' />
                      <groupfilter function='union'>
                        <groupfilter function='crossjoin'>
                          <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='6' />
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.623910000000002' />
                            <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.167410000000004' />
                          </groupfilter>
                        </groupfilter>
                        <groupfilter function='crossjoin'>
                          <groupfilter function='member' level='[mn:CRASH DATE:ok]' member='12' />
                          <groupfilter function='crossjoin'>
                            <groupfilter function='member' level='[none:LATITUDE:qk]' member='40.610259999999997' />
                            <groupfilter function='member' level='[none:LONGITUDE:qk]' member='-74.097496000000007' />
                          </groupfilter>
                        </groupfilter>
                      </groupfilter>
                    </groupfilter>
                  </groupfilter>
                </groupfilter>
                <order>
                  <hierarchy name='[none:BOROUGH:nk]' />
                  <hierarchy name='[none:LATITUDE:qk]' />
                  <hierarchy name='[none:LONGITUDE:qk]' />
                  <hierarchy name='[mn:CRASH DATE:ok]' />
                  <hierarchy name='[yr:CRASH DATE:ok]' />
                </order>
              </groupfilter>
            </groupfilter>
          </filter>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:BOROUGH:nk]' />
              <groupfilter function='member' level='[none:BOROUGH:nk]' member='%null%' />
            </groupfilter>
          </filter>
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' included-values='in-range'>
            <min>#2012-07-01#</min>
            <max>#2016-04-16#</max>
          </filter>
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:LONGITUDE:qk]' included-values='non-null' />
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:NUMBER OF PERSONS INJURED:qk]' included-values='in-range'>
            <min>0</min>
            <max>43</max>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:LONGITUDE:qk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:NUMBER OF PERSONS INJURED:qk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[Exclusions (Borough,Latitude,Longitude,MONTH(Crash Date),YEAR(Crash Date))]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <encoding attr='space' class='0' field='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:LONGITUDE:qk]' field-type='quantitative' max='32091466.67663705' min='31589309.949846782' projection='EPSG:3857' range-type='fixed' scope='cols' type='space' />
            <encoding attr='space' class='0' field='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:LATITUDE:qk]' field-type='quantitative' max='5154279.3583990801' min='4803544.3564260704' projection='EPSG:3857' range-type='fixed' scope='rows' type='space' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
        </style>
        <panes>
          <pane id='4' selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <color column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' />
              <lod column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]' />
              <lod column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[mn:CRASH DATE:ok]' />
              <lod column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[sum:NUMBER OF MOTORIST KILLED:qk]' />
              <lod column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[sum:NUMBER OF MOTORIST INJURED:qk]' />
              <lod column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[sum:NUMBER OF PEDESTRIANS INJURED:qk]' />
              <lod column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[sum:NUMBER OF PEDESTRIANS KILLED:qk]' />
            </encodings>
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:LATITUDE:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:LONGITUDE:qk]</cols>
      </table>
      <simple-id uuid='{45646240-861C-4CE6-B9CF-50A55625B53F}' />
    </worksheet>
    <worksheet name='Sheet 8'>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column-instance column='[COLLISION_ID]' derivation='CountD' name='[ctd:COLLISION_ID:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Month' name='[mn:CRASH DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[CRASH DATE]' derivation='None' name='[none:CRASH DATE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' included-values='in-range'>
            <min>#2013-01-01#</min>
            <max>#2015-12-31#</max>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='width' field='[federated.1r8brmi130k32o1d2kah51ldrjx2].[mn:CRASH DATE:ok]' value='28' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Bar' />
            <encodings>
              <color column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]' />
            </encodings>
            <style>
              <style-rule element='pane'>
                <format attr='minwidth' value='-1' />
                <format attr='maxwidth' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[ctd:COLLISION_ID:qk]</rows>
        <cols>([federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok] / [federated.1r8brmi130k32o1d2kah51ldrjx2].[mn:CRASH DATE:ok])</cols>
      </table>
      <simple-id uuid='{D058B96A-C461-4EA4-9398-8E5CAF495FD3}' />
    </worksheet>
    <worksheet name='TrendLines'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Crashes by Bourough</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Borough' datatype='string' name='[BOROUGH]' role='dimension' type='nominal' />
            <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column-instance column='[COLLISION_ID]' derivation='CountD' name='[ctd:COLLISION_ID:qk]' pivot='key' type='quantitative' />
            <column-instance column='[BOROUGH]' derivation='None' name='[none:BOROUGH:nk]' pivot='key' type='nominal' />
            <column-instance column='[CRASH DATE]' derivation='None' name='[none:CRASH DATE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:BOROUGH:nk]' />
              <groupfilter function='member' level='[none:BOROUGH:nk]' member='%null%' />
            </groupfilter>
          </filter>
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' included-values='in-range'>
            <min>#2020-01-01#</min>
            <max>#2024-12-31#</max>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <color column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' />
            </encodings>
            <trendline enable-confidence-bands='false' enable-instant-analytics='true' enabled='true' exclude-color='false' exclude-intercept='false' fit='linear' />
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[ctd:COLLISION_ID:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</cols>
      </table>
      <simple-id uuid='{839789BB-EF56-470A-9BE2-311BA993D4D1}' />
    </worksheet>
    <worksheet name='TrendLines (2)'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Crashes by Bourough</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Motor_Vehicle_Collisions_-_Crashes' name='federated.1r8brmi130k32o1d2kah51ldrjx2' />
          </datasources>
          <datasource-dependencies datasource='federated.1r8brmi130k32o1d2kah51ldrjx2'>
            <column caption='Borough' datatype='string' name='[BOROUGH]' role='dimension' type='nominal' />
            <column caption='Collision Id' datatype='integer' name='[COLLISION_ID]' role='dimension' type='ordinal' />
            <column caption='Crash Date' datatype='date' name='[CRASH DATE]' role='dimension' type='ordinal' />
            <column-instance column='[COLLISION_ID]' derivation='CountD' name='[ctd:COLLISION_ID:qk]' pivot='key' type='quantitative' />
            <column-instance column='[BOROUGH]' derivation='None' name='[none:BOROUGH:nk]' pivot='key' type='nominal' />
            <column-instance column='[CRASH DATE]' derivation='None' name='[none:CRASH DATE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[CRASH DATE]' derivation='Year' name='[yr:CRASH DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:BOROUGH:nk]' />
              <groupfilter function='member' level='[none:BOROUGH:nk]' member='%null%' />
            </groupfilter>
          </filter>
          <filter class='quantitative' column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' included-values='in-range'>
            <min>#2013-01-01#</min>
            <max>#2019-12-31#</max>
          </filter>
          <slices>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]</column>
            <column>[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <color column='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' />
            </encodings>
            <trendline enable-confidence-bands='false' enable-instant-analytics='true' enabled='true' exclude-color='false' exclude-intercept='false' fit='linear' />
          </pane>
        </panes>
        <rows>[federated.1r8brmi130k32o1d2kah51ldrjx2].[ctd:COLLISION_ID:qk]</rows>
        <cols>[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]</cols>
      </table>
      <simple-id uuid='{63465315-B3DD-4D77-A577-02265C1F0CB0}' />
    </worksheet>
  </worksheets>
  <windows saved-dpi-scale-factor='1.5' source-height='44'>
    <window class='worksheet' name='GEO' tab-color='#4f779a'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:NUMBER OF PERSONS INJURED:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
            <card pane-specification-id='4' param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' type='color' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='1' />
      </viewpoint>
      <simple-id uuid='{269EF870-C2F1-4195-B58F-33BB8CE89681}' />
    </window>
    <window class='worksheet' name='Deaths' tab-color='#f66273'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{453FF642-ECE3-4A82-83E2-6B048F7F3DE3}' />
    </window>
    <window class='worksheet' name='#Injuries' tab-color='#a65200'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{0EF14AA4-47C2-434A-892F-EE9DC24BF775}' />
    </window>
    <window class='worksheet' name='#Crashes' tab-color='#dec77b'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]' type='filter' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{9B03973B-798A-4593-A6B3-38A818D54023}' />
    </window>
    <window class='worksheet' name='Bouroughs' tab-color='#6e597f'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card pane-specification-id='0' param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' type='color' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{D4C63E59-A093-4A56-B8FE-7DD7850E2C5A}' />
    </window>
    <window class='worksheet' name='TrendLines' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
            <card pane-specification-id='0' param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' type='color' />
            <card AVG='true' KURTOSIS='false' MAX='true' MEDIAN='true' MIN='true' QUART1='false' QUART3='false' SKEWNESS='false' STDEV='false' SUM='true' type='summary' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{3A9AB457-2557-41B7-B92F-6EF428D7BD12}' />
    </window>
    <window class='worksheet' name='TrendLines (2)' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
            <card pane-specification-id='0' param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:BOROUGH:nk]' type='color' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{FC0B5391-483E-43A8-A505-B55169D59002}' />
    </window>
    <window class='worksheet' maximized='true' name='Crashes By Factor' tab-color='#72bcbb'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[cnt:COLLISION_ID:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{E2835FCD-FF1E-4E8A-9183-3109DA8BEC58}' />
    </window>
    <window class='worksheet' name='Sheet 8'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[none:CRASH DATE:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
            <card pane-specification-id='0' param='[federated.1r8brmi130k32o1d2kah51ldrjx2].[yr:CRASH DATE:ok]' type='color' />
          </strip>
        </edge>
      </cards>
      <simple-id uuid='{11C4061F-0E9B-419A-BD5F-978AB859650D}' />
    </window>
  </windows>
  <thumbnails>
    <thumbnail height='192' name='Crashes By Factor' width='192'>
      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
      /wNU8GV2WXo+EQAAAABJRU5ErkJggg==
    </thumbnail>
  </thumbnails>
</workbook>
