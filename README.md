# Alberon Project Management

A web-based project management application with HOAI fee calculation functionality.

## Features

- Project Management Dashboard
- HOAI Fee Calculator with linear interpolation
- Responsive Design
- Local Storage for Data Persistence

## Setup

1. Clone the repository:
```bash
git clone https://github.com/stoiccapital/alberon_project_2.git
```

2. Open the project in your browser:
```bash
python3 -m http.server 8000
```

3. Visit `http://localhost:8000/pages/index.html`

## HOAI Calculator

The HOAI calculator implements the official fee table with linear interpolation for accurate fee calculations between brackets.

### Usage

1. Enter the construction cost in euros
2. Select the honorar zone (1-5)
3. Click "Berechnen" to calculate the fee

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Local Storage API 