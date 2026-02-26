# Resident GIS Mapping Survey

A comprehensive Geographic Information System (GIS) mapping application for resident surveys, built with React and Leaflet.

## Features

- Interactive GIS mapping with Leaflet
- Complete resident information management
- Survey status tracking (pending, surveyed, verified)
- Location-based data collection
- Comprehensive demographic and socio-economic data
- CRUD operations for resident records

## Database Structure

The application mirrors the `tblresident` structure from biams_db with all 62 fields including:

- Personal Information (firstname, middlename, lastname, alias, birthdate, age, gender, civilstatus)
- Location Data (latitude, longitude, location_accuracy, street, purok, sitio, barangay, municipality, province)
- Contact Information (phone, email)
- Government IDs (philhealth, gsis, tin, pagibig, psa, votersid)
- Socio-economic Data (occupation, monthly income, skills, educational attainment)
- Housing Information (house_type, housestat, landown, wateruse, sanitarytoilet, lighting)
- Survey Details (survey_date, survey_status, surveyed_by)

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/resident-gis-mapping.git
cd resident-gis-mapping
