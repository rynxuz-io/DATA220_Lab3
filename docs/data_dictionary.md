Data dictionary for 'campus_spaces.csv'

File: 'data/sample/campus_spaces.csv'
Format: comma-separated values, one header row
Rows: 12

Column | Type | Description | Range | Example

'space_id' | Text | Unique identifier for the study space. One row per ID. | `S101' to 'S112'
'building' | Text | Building where the space is located. | 'Building A' to 'Building F'
'space_type' | Text (category) | Kind of study space. | 'Quiet study', 'Group study', 'Computer Lab', 'Lounge' | 'Computer Lab`
'seats' | Integer | Total seating capacity of the space. | 16 to 32 | '30'
'occupied' | Integer | Number of seats in use at the time of observation. Must be between 0 and 'seats'. | 11 to 27 | '15'
'noise_level' | Text (ordered category) | Observed noise level in the space. | 'Low', 'Medium', 'High' | 'Medium'

