# Northern Trails

A responsive, single-page website for a fictional travel agency based in Islamabad, Pakistan. Northern Trails organizes tours to Hunza, Skardu, and Swat. This was built as a front-end assignment for CS202 at Virtual University of Pakistan.

## Features

- Header with a welcome message and tagline
- Navigation bar with smooth in-page links (Home, Tour Packages, Book a Tour)
- About Us section
- Tour packages list (Hunza, Skardu, Swat)
- Booking form with built-in validation:
  - Customer name
  - Email address
  - Contact number
  - Destination dropdown
  - Preferred travel date
  - Number of travelers (minimum 1)
- Styled footer

## Built With

- HTML5
- CSS3 (embedded in the `<style>` tag)

No frameworks, libraries, or build tools are needed.

## How to Run

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.

```bash
git clone https://github.com/asifriaz03/northern-trails.git
cd northern-trails
```

## Project Structure

```
northern-trails/
├── index.html
└── README.md
```

## Notes

- The booking form uses the HTML `required` attribute and input types (`email`, `tel`, `date`, `number`) for client-side validation.
- The form does not send data to a server. It is a front-end exercise only.

## Author

**Asif**
BS Software Engineering, Virtual University of Pakistan
GitHub: [@asifriaz03](https://github.com/asifriaz03)
