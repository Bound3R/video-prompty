# VIDEO-PROMPTY – Prompt JSON Generator

## What is this project?

This project is a **minimal web tool** that dynamically generates a structured JSON prompt for Veo 3 video generation.  

It collects all key parameters (scene, technical specs, camera, lighting, style, characters, negatives, etc.) through simple form inputs and outputs a ready-to-use JSON.  

The design is inspired by the **JSON prompting methodology** for professional video generation described in the article:  
👉 [Mastering Veo 3 Consistency – The Complete Guide to JSON Prompting](https://medium.com/@ai.in.motion.blog/mastering-veo-3-consistency-the-complete-guide-to-json-prompting-for-professional-video-generation-8ab45ee7239b).  

---

## Features

- Clean interface.  
- Form fields for all essential JSON parameters from the Veo 3 prompting guide.  
- Instant JSON generation, ready to copy.  
- Copy-to-clipboard functionality.  
- Minimal, lightweight, and easy to adapt.

---

## JSON Structure Example

```jsonc
{
  "scene": {
    "subject": "",
    "environment": "",
    "action": "",
    "objects": ""
  },
  "technicalSpecifications": {
    "resolution": "",
    "frameRate": "",
    "aspectRatio": "",
    "quality": ""
  },
  "camera": {
    "cameraType": "",
    "lens": "",
    "movement": "",
    "framing": ""
  },
  "lighting": {
    "timeOfDay": "",
    "mood": "",
    "colorTemperature": "",
    "shadows": ""
  },
  "style": {
    "visualReference": "",
    "rendering": "",
    "postProcessing": "",
    "continuity": ""
  },
  "character": {
    "appearance": "",
    "clothing": "",
    "ageDemographic": "",
    "actionConsistency": ""
  },
  "negativeParameters": {
    "unwantedElements": "",
    "styleExclusions": "",
    "artifacts": "",
    "movementRestrictions": ""
  }
}
```


## How to use

1. Clone the repository:
```bash
git clone [repository-url]
cd google-calendar-codewords
```

2. Open your browser and navigate to the `index.html` file in the project directory.

## File Structure

```
video-prompty/
├── css/
│   └── styles.css         # Application styles
├── js/
│   └── app.js             # Main application logic
├── locales/
│   ├── en.json            # English translations
│   └── es.json            # Spanish translations
├── images/                # Image files
└── index.html             # Main HTML file
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- i18next for internationalization

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/missing-keywords`)
3. Commit your changes (`git commit -m 'Add some missing keywords'`)
4. Push to the branch (`git push origin feature/missing-keywords`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.


