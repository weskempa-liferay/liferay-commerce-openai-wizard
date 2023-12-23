# Liferay OpenAI Content Creation Wizard 

With this application, creating content for Liferay demo purposes is a breeze!

Consider this scenario: You can create 15 products across 5 categories in just 35 seconds with a single prompt from you. The magic happens through the integration of OpenAI's API for content creation and Liferay's APIs for seamless storage based on your prompts.

Utilizing this OpenAI Wizard doesn't just speed up content creation, which many of us are already doing with AI. It goes the extra mile by seamlessly loading it into the demo instance through our Liferay APIs. Big kudos to **Steven Lu**, who, alongside contributing significantly to Commerce and its related APIs, identified the potential to optimize the time spent on setting up commerce products, categories, and SKUs.
  
![AIWizard-Screenshot](https://github.com/weskempa-liferay/liferay-openai-demo-wizard/assets/68334638/eafd4327-492c-4fcf-81e8-2d3abfa9f8f7)

## The Liferay Content Wizard currently supports generating these asset types: 

- **Accounts**
- **Blogs with Images**
- **Commerce Categories and Products with Images**
- **FAQs**
- **Images Only**
- **News Articles with Images**
- **Knowledge Base Folders and Articles**
- **Message Board Sections, Threads, and Messages**
- **Custom Liferay Objects Schemas**
- **Users (CSV and OpenAI)**

As we move forward, expect more options for different content types. A big shoutout to Steven Lu for the inspiration and knowledge that brought this functionality to life! Cheers!

![Screen Shot 2023-12-12 at 10 07 11 AM](https://github.com/weskempa-liferay/liferay-openai-demo-wizard/assets/68334638/fc303b12-9bf9-4d94-b3d2-e3e638793317)
![Screenshot 2023-11-30 at 6 09 19 PM](https://github.com/weskempa-liferay/liferay-openai-demo-wizard/assets/68334638/3d733f48-a6cc-48e6-af4c-b0578542befa)
![Screenshot 2023-11-30 at 6 02 49 PM](https://github.com/weskempa-liferay/liferay-openai-demo-wizard/assets/68334638/7b60a262-e9af-47b4-bbae-7b58d30ee367)


Technologies used:

- [OpenAI API](https://openai.com/api/)
- [Node.js](https://nodejs.org/en/)
- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Highlight.js](https://highlightjs.org/)

## Setup

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/en/)

1. Clone this repository

1. Navigate into the project directory

```bash
cd liferay-openai-demo-wizard
```  

1. Install the requirements

```bash
npm install
```

1. Make a copy of the example environment variables file

```bash
cp .env.example .env
```

1. Add your OpenAI [API key]([https://beta.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)) to the newly created `.env` file as well as fill in the details of your server.

1. Run the app

```bash
npm run dev
```

You should now be able to access the app at [http://localhost:3000](http://localhost:3000). 

## Deployment

Once you have this up and running locally, make sure to fill in the required Environment Details. These might become UI-based configurations, but for now it is required to configure these settings in your environment variables. 

```bash
OPENAI_API_KEY= <key goes here>
LIFERAY_PATH= <HTTP: or HTTPS: URL for the server, example: 'http://localhost:8080' >
LIFERAY_ADMIN_EMAIL_ADDRESS=
LIFERAY_ADMIN_PASSWORD=
```

## Note: Recent package updates require re-running npm install

# Lets build great things!
