### AI-Core-Simplified - https://phplaravel-1109775-4163586.cloudwaysapps.com/ai2/generate/1/true/true/Archiytect/Chisinua/spa%20center
### AI-Core-Simplified - https://c304aec941ac.ngrok.app/ai2/generate/1/true/true/Archiytect/Chisinua/spa%20center

### Logo: https://www.loom.com/share/c2accfee7baf4e3abfe10faf47d75096
### Global Project Prompt: https://www.loom.com/share/e71077e4fe794dcab3b2d2e70b8ebde6
### Texts: https://www.loom.com/share/d276ebb5255243f89dbde62c5f8231bf
### Images: https://www.loom.com/share/a42bd9f5864944c789af3274690b7c46
### Background Images: https://www.loom.com/share/20e581809e5541bb8cf5dff925d5327c



# DEPRECATED - OLD MODELS
____________________________________

## Fine tuned models & prompts examples

## Hero Title

(#model-hero-title)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8ovu1ygK`
- `{{x="1" model="#model-hero-title" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

## Hero Title with Location and company name

(#model-hero-title-location)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8pbytUGJ`,
- `{{x="2" model="#model-hero-title-location" user="Company Name: ^^^, Type of Business: %%%, Description: &&&, Location: ***"}}` +

## Hero Description

(#model-hero-description)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8pFN962o`
- `{{x="3" model="#model-hero-description" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}` +

## Hero Description with Locatiom

(#model-hero-description-location)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8pYIP7sm`
- `{{x="4" model="#model-hero-description-location" user="Company Name: ^^^, Type of Business: %%%, Description: &&&, Location: ***}}` +


## Single Testimonial

(#model-testimonial)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8pH9ZneA`
- `{{x="5" model="#model-testimonial" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}` +

## Service/Feature name

(#model-service-name)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8np4WOYh`
- `{{x="6" model="#model-service-name" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

## Feature/Service description

(#model-service-description)
- Model: `ft:gpt-3.5-turbo-1106:brizy::8ouGs4ca`
- `{{x="7" model="#model-service-description" user="Company Name: ^^^, Type of Business: %%%, Description: &&&, Item: [item name]"}}`


# NEW MODELS
____________________________________

# ft:gpt-3.5-turbo-1106:brizy:v2-subhead-heading:9Bfs2joO

### Generate 1 `SUBHEADING` based on provided `HEADING`
### Placeholder: `{{x="1" model="#model-subhead-heading" user="Company Name: ^^^, Type of Business: %%%, Description: &&&, Item: 6"}}`
### Additional Info: Item is the id of the heading

```js
Type of Business: required
Description: optional
Heading: required
```

Example Prompt: `Type of Business: Website Builder, Heading: White Label Website Builder for Agencies & SaaS`

```js
Response: 
{
    "0":"Customizable Website Builder Solution for Agencies and SaaS Companies"
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-testimonials:9AHwixMO

### Generates N samples of testimonials
### Placeholder example: `{{x="2" model="#model-testimonial" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}

```js
Company Name: required
Type of Business: required
Description: optional
Samples Amount: required (number)
```

Example Prompt: `Company Name: Brizy, Type of Business: Website Builder, Samples Amount: 3`

```js
Response
{
    "0": "I had a fantastic experience using Brizy to build my website. The platform is incredibly user-friendly and the design options are endless. I was able to create a stunning and professional-looking site in no time, and the customer support team was always there to assist with any questions I had. I highly recommend Brizy to anyone looking for a top-notch website builder.",
    "1": "Brizy is a game-changer! I've tried other website builders in the past, but none compare to the ease and flexibility of Brizy. The intuitive interface and diverse range of templates made the whole design process a breeze. I'm thrilled with the final result and have received so many compliments on my new website. Thank you, Brizy, for making it all possible!",
    "2": "I can't speak highly enough of Brizy and its powerful website building capabilities. I'm not tech-savvy, but this platform guided me through the entire process, enabling me to craft a beautiful and functional website without any hassle. The pre-made blocks and elements are so versatile, and the final outcome exceeded my expectations. Brizy truly empowers anyone to create a stunning online presence."
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-service-names:9AIDq9ti

### Generates N samples of service names
### Placeholder example: `{{x="3" model="#model-service-name" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

```js
Type of Business: required
Description: optional
Samples Amount: required (number)
```

Example Prompt: `Type of Business: Website Builder, Samples Amount: 6`

```js
Response
{
    "0":"Custom Templates",
    "1":"Drag and Drop Interface",
    "2":"Responsive Design",
    "3":"E-commerce Integration",
    "4":"SEO Optimization",
    "5":"Social Media Integration"
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-service-desc:9Ae08JAe

### Generates service description for provided service names
### Placeholder example: `{{x="4" model="#model-service-description" user="Company Name: ^^^, Type of Business: %%%, Description: &&&, Item: 26"}}`
### Additional Info: Item is the id of the service name

```js
Type of Business: required
Description: optional
Item: required - Array of service names
```

Example Prompt: `Type of Business: Painting, Item: ['Color Consultation','Surface Preparation']`

```js
Response
{
    "Color Consultation":"Enrich your space with expert color consultation, tailored to your unique style and design preferences.",
    "Surface Preparation":"Achieve flawless results with meticulous surface preparation, ensuring a smooth and durable foundation for your painting project."
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-headings:9AHoQahj

### Generates N samples of headings
### Placeholder example: `{{x="5" model="#model-heading" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

```js
Company Name: optional
Type of Business: required
Description: optional
Samples Amount: required (number)
```

Example Prompt: `Company Name: Renewed Treasures, Type of Business: Furniture Restoration, Description: We breathe new life into your worn-out furniture, restoring their original charm and ensuring they become cherished pieces once again., Samples Amount: 2`

```js
Response:
{
    "0":"Revive Your Furniture's Charm",
    "1":"Cherished Pieces Restored to Perfection"
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-subheadings-y:9JJE7zCO

### Generates N samples of subheadings (random)
### Placeholder example: `{{x="6" model="#model-subhead" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

```js
Company Name: optional
Type of Business: required
Description: optional
Samples Amount: required (number)
```

Example Prompt: `Company Name: Vitality Solutions, Type of Business: Wellness, Samples Amount: 2`

```js
Response:
{
    "0":"Holistic Wellness Programs for Optimal Mind-Body Balance and Vitality",
    "1":"Personalized Wellness Coaching to Elevate Your Health and Well-being"
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-subheadings-loc:9GpdjVUK

### Generates N samples of subheadings with location (random)
### Placeholder example: `{{x="7" model="#model-subheading-loc" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

```js
Company Name: optional
Type of Business: required
Description: optional
Samples Amount: required (number)
Location: required
```

Example Prompt: `Company Name: Brizy, Type of Business: Archeology, Samples Amount: 5, Location: India`

```js
Response:
{
  "0": "Uncover India's Rich History with Brizy's Excavation and Archeology Services",
  "1": "Explore Ancient Civilizations with Brizy's Archeology Expertise in India",
  "2": "Brizy: Unearthing India's Cultural Heritage through Archeological Discoveries",
  "3": "Experience the Wonders of India's Past with Brizy's Archeology Exploration",
  "4": "Discover Hidden Treasures of Indian History with Brizy's Archeological Expeditions"
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-headings-loc:9H6zgQmS

### Generates N samples of headings with location (random)
### Placeholder example: `{{x="8" model="#model-heading-loc" user="Company Name: ^^^, Type of Business: %%%, Description: &&&"}}`

```js
Company Name: optional
Type of Business: required
Description: optional
Samples Amount: required (number)
Location: required
```

Example Prompt: `Company Name: GeoBrizy, Type of Business: Geology, Samples Amount: 3, Location: Palermo`

```js
Response:
{
  "0": "Explore Geological Wonders in Palermo",
  "1": "Unearth the Earth's Secrets in Palermo",
  "2": "Discover Dynamic Geology in Palermo"
}
```

# ft:gpt-3.5-turbo-1106:brizy:v2-sub-head-loc:9H6p5hU9

### Generates N SUBHEADING with location based on Heading
### Placeholder example: `{{x="9" model="#model-subhead-heading-loc" user="Company Name: ^^^, Type of Business: %%%, Description: &&&, Item: 6"}}`
### Additional Info: Item is the id of the heading

```js
Company Name: optional
Type of Business: required
Description: optional
Location: required
```

Example Prompt: `Company Name: GeoBrizy, Type of Business: Geology, Heading: Unearth the Earth's Secrets in Palermo, Location: Palermo`

```js
Response:
{
  "0":"Discover Palermo's Geologic Wonders with GeoBrizy: Unearthing Earth's Ancient Secrets"
}
```
