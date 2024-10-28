# football-fhir-extensions

This repository contains FHIR (Fast Healthcare Interoperability Resources) extensions designed to capture detailed information about football injuries. The extensions aim to standardize the recording of key data elements related to player injuries in the context of American football, facilitating better data sharing and analysis across various levels of the sport (NFL, college, high school, etc.).

## Key Features

- **Football Injury Extension**: A custom FHIR extension that includes fields for:
  - Position of player (e.g., quarterback, running back)
  - Direction of play (e.g., left, right)
  - Ball yard mark
  - Down and distance
  - Formation
  - Play call

## Usage

This extension can be used in conjunction with existing FHIR resources, such as `Observation`, to enrich player injury data and improve understanding of injury trends and patterns in football.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/football-fhir-extensions.git
